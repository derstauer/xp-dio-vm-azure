# Desafio: Criando máquinas Virtuais na Azure - bootcamp DIO + XP Inc.

Este laboratório tem como objetivo de consolidar conhecimentos em máquinas virtuais da Azure.
--

Objetivos de Aprendizagem 
- Aplicar os conceitos aprendidos em um ambiente prático; 
- Documentar processos técnicos de forma clara e estruturada;
- Utilizar o GitHub como ferramenta para compartilhamento de documentação técnica;

------------------------------------------------------------------------
## Passo a Passo

### 1. Acessar o Portal Azure

Acessar [https://portal.azure.com](https://portal.azure.com) e entrar com sua conta Microsoft com assinatura Azure.

---

### 2. Criação da VM

Na home, clicar em **"Máquinas Virtuais"** e após em **"Criar"** selecionando **"Máquina Virtual"**.

---

### 3. Configurando a máquina virtual

Na tela criar uma máquina virtual, informar:

#### Aba **"Básico"**

- **Assinatura**: Escolher assinatura ativa da conta.
- **Grupo de recursos**: Selecione um grupo ou crie um novo.
- **Nome da máquina virtual**: Nome da VM.
- **Região**: Escolher região mais próxima ou que atenda sua necessidade.
- **Opções de disponibilidade**: Selecionado **Nenhuma redundância infraestrutura necessária** para garantir custos baixo.
- **Tipo de segurança**: Selecionado **Padrão**.
- **Imagem**: Escolha o aplicativo ou sistema operacional (selecionado **Ubuntu Server 24.04 LTS - x64 Gen2**).
- **Arquitetura de VM**: Selecionado x64 (maior compatibilidade).
- **Tamanho**: Selecione o tamanho da VM (cpu, mémoria,etc) selecionado Standart_B2ats_v2 para garantir custos baixo.
- **Usuário e senha/SSH**: Escolha entre criar usuário/senha ou chave SSH para acesso.
- Clicar em Revisar + criar.
---

### 4. Acesso à máquina virtual

- Acesso por `ssh` usando o IP público:
```bash
ssh userVM@<IP_VM>
```
- Ou acesso via RDP, no caso do Windows.

## Screenshots

As imagens que demonstram o processo estão no diretório `/images`.

## Autor
Wellington José Schmitt – bootcamp DIO + XP Inc.
