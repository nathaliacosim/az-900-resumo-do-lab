# 📘 Resumo do Lab - Formação AZ-900 (DIO)

Durante esta formação, estou explorando os principais conceitos e serviços da plataforma **Microsoft Azure**, aprendendo a navegar no portal, entender os modelos de serviço em nuvem e criar recursos essenciais como máquinas virtuais, contas de armazenamento e bancos de dados.

---

## 🌐 Portal do Azure

- Como **acessar e personalizar** o portal do Azure.
- Fixar e remover recursos e dashboards na página inicial.
- Uso da **barra de pesquisa** para encontrar serviços de forma rápida.
- Navegação organizada por categorias, como:
  - **Computação** (ex: Máquinas Virtuais);
  - **Redes** (ex: VNet);
  - **Armazenamento** (ex: Blob Storage);
  - **Bancos de Dados** (ex: Azure SQL);
  - **DevOps**, **Segurança** e outros.
- Dica: O portal apresenta ícones com a letra **“i”** que fornecem explicações e links para a documentação oficial, facilitando a aprendizagem.

---

## ☁️ Modelos de Serviço em Nuvem

### 🔧 IaaS — *Infrastructure as a Service*
- Infraestrutura como serviço.
- O cliente tem **controle total sobre máquinas, redes e discos**.
- Toda a configuração e manutenção são responsabilidade do cliente.
- Exemplo: **Máquinas Virtuais (VMs)**.

### 🧱 PaaS — *Platform as a Service*
- Plataforma como serviço.
- O provedor oferece um ambiente pronto para desenvolvimento.
- O cliente **foca no código**, sem se preocupar com servidores ou atualizações.
- Exemplo: **App Services**, **Azure Functions**, **Azure SQL Database**.

### 💻 SaaS — *Software as a Service*
- Software como serviço.
- O usuário acessa o software já pronto, via navegador.
- Recursos variam conforme o **tipo de licença adquirida**.
- Exemplo: **Microsoft 365**, **Outlook**, **Teams**, **Dynamics 365**.

---

## 🖥️ Máquinas Virtuais (VMs) no Azure

- Durante a criação de uma VM, é possível selecionar a **imagem do sistema operacional** (Windows, Ubuntu, etc.).
  - O portal **exibe o custo estimado mensal automaticamente**, facilitando o planejamento financeiro.
- O campo **Zona de Disponibilidade** permite distribuir a VM entre até **3 zonas diferentes**, aumentando a resiliência contra falhas.
- O campo **"Opção de disponibilidade"** exibe diferentes estratégias (como conjuntos de disponibilidade), cada uma com sua própria **SLA (Service Level Agreement)**.
- **Quanto mais próximo de 100% for a SLA, menor o tempo de indisponibilidade esperado**.

---

## 🧠 Aula Prática: VM + Banco de Dados SQL

- Após configurar a VM, seguimos para a criação de uma instância gerenciada do **Azure SQL**.
- Na etapa de configuração de **redundância dos dados**, o portal mostra como **cada opção impacta no custo**.
- Esse nível de transparência ajuda a **tomar decisões técnicas mais conscientes**, equilibrando **disponibilidade e orçamento**.

---

## 📦 Armazenamento e Redundância

- Ao criar uma **Conta de Armazenamento**, é possível configurar o tipo de **redundância**:
  - **LRS (Local Redundant Storage)**: réplica no mesmo datacenter.
  - **GRS (Geo-Redundant Storage)**: réplica entre regiões diferentes.
- A **redundância geográfica** aumenta a **disponibilidade, resiliência e performance** em ambientes distribuídos.

---

## 📊 SLA – Service Level Agreement

- A **SLA indica o nível de disponibilidade** garantido por um serviço.
- Exemplos:
  - **99%**: até ~7h/mês de indisponibilidade.
  - **99,9% (três noves)**: até ~43min/mês.
  - **99,99% (quatro noves)**: até ~4min/mês.
- **Quanto mais alta a SLA, menor o tempo aceitável de falha**, o que é fundamental para aplicações críticas.

---

## 💡 Conclusão

Esse primeiro contato com o Azure está sendo fundamental para entender a **estrutura da plataforma, os modelos de serviço e a criação de recursos essenciais**.

A cada aula, me sinto mais segura para navegar, configurar e tomar decisões alinhadas à **performance, custo e disponibilidade** de aplicações em nuvem.

---

## 🤓 Dica do Dia

> **"Não use nada que esteja como prévia!"**  
> — Porque no Azure, o que é *Preview* hoje, pode estar diferente (ou fora) amanhã! 😂
