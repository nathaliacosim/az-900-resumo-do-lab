# 📘 Resumo do Lab - Formação AZ-900 (DIO)

Durante esta formação, estou explorando os principais conceitos e serviços da plataforma **Microsoft Azure**, aprendendo a navegar no portal, entender os modelos de serviço em nuvem e criar recursos essenciais como máquinas virtuais, contas de armazenamento e bancos de dados.

---

## 🎯 AZ-900: Os 3 Pilares Fundamentais

### 1. ☁️ Conceitos de Computação em Nuvem
- Diferença entre **IaaS, PaaS e SaaS**.
- Modelos de nuvem: **Pública, Privada e Híbrida**.
- Princípios como **escalabilidade, elasticidade, tolerância a falhas e agilidade**.
- Alta disponibilidade e continuidade dos negócios.

### 2. 🔐 Segurança, Conformidade e Confiança
- Segurança física e lógica no Azure.
- Identidade e controle de acesso com **Azure AD e RBAC**.
- Serviços de conformidade, como **Microsoft Defender for Cloud**.
- Confiança baseada em **transparência, compliance e privacidade de dados**.

### 3. 💰 Preços, SLA e Suporte
- Estimativas de custo com a **Calculadora do Azure**.
- Modelos de cobrança: **consumo, reserva e licenciamento**.
- Níveis de suporte técnico.
- Conceito de **SLA (Service Level Agreement)** e impacto na operação.

---

## 🌐 Navegação no Portal do Azure

- Acesso ao portal: [https://portal.azure.com](https://portal.azure.com)
- Fixar/remover recursos e dashboards personalizados.
- Busca por serviços e recursos usando a **barra superior**.
- Categorias comuns:
  - **Computação**: Máquinas Virtuais;
  - **Rede**: VNet, Load Balancer;
  - **Armazenamento**: Blob, File Share;
  - **Banco de Dados**: Azure SQL, Cosmos DB;
  - **DevOps**, **Segurança**, **Monitoramento**, etc.

> 💡 Os ícones com a letra “i” fornecem explicações úteis e links para a documentação oficial.

---

## 🗂️ Criando um Grupo de Recursos + Zonas de Disponibilidade

Um **Grupo de Recursos** é o contêiner lógico onde todos os recursos relacionados de um projeto são organizados e gerenciados em conjunto.

### ✅ Etapas para criar:
1. No portal, vá até **"Grupos de recursos"**.
2. Clique em **Criar**.
3. Selecione:
   - Assinatura;
   - Nome do grupo;
   - Região (ex: *Brazil South*).
4. Confirme em **"Revisar + Criar"** e depois clique em **Criar**.

> 📌 A localização define onde os metadados do grupo serão armazenados, mas os recursos podem estar distribuídos globalmente.

### 🌍 Zonas de Disponibilidade

As **Availability Zones** são locais físicos independentes dentro de uma mesma região. São projetadas para **reduzir o risco de falhas generalizadas** e garantir alta disponibilidade.

Para verificar quais regiões oferecem suporte:
🔗 [Mapa de Regiões e Zonas do Azure](https://azure.microsoft.com/pt-br/explore/global-infrastructure/geographies/)

---

## ☁️ Modelos de Serviço em Nuvem

### 🔧 IaaS (Infrastructure as a Service)
- Controle total sobre infraestrutura.
- Exemplo: **Máquinas Virtuais**.

### 🧱 PaaS (Platform as a Service)
- Ambiente gerenciado para desenvolvimento e deployment.
- Exemplo: **App Services, Azure SQL, Azure Functions**.

### 💻 SaaS (Software as a Service)
- Aplicações prontas para uso, via navegador.
- Exemplo: **Microsoft 365, Teams, Outlook**.

---

## 🖥️ Máquinas Virtuais no Azure

- Escolha do sistema operacional (Windows/Linux).
- Estimativa de custo exibida durante a criação.
- Configuração de disponibilidade:
  - **Zonas de Disponibilidade**;
  - **Conjuntos de Disponibilidade** (Availability Sets);
  - **SLA específico** por opção escolhida.

---

## 🧠 Aula Prática: VM + Banco de Dados SQL

- Após configurar a VM, criamos uma instância do **Azure SQL Database**.
- Exploramos configurações de redundância e como elas afetam o custo e a performance.

---

## 📦 Armazenamento no Azure

- Criação de uma **Conta de Armazenamento** e seleção do tipo de **redundância**:
  - **LRS (Local Redundant Storage)**;
  - **GRS (Geo-Redundant Storage)**.
- Redundância aumenta a **resiliência e disponibilidade**.

---

## 📊 SLA – Service Level Agreement

- Indica a disponibilidade mínima garantida pelo Azure.
- Exemplos:
  - **99%** ≈ até 7h de indisponibilidade/mês.
  - **99,9%** ≈ até 43min/mês.
  - **99,99%** ≈ até 4min/mês.

> 🎯 Quanto mais alta a SLA, menor a chance de indisponibilidade – ideal para aplicações críticas.

---

## 💡 Conclusão

Esse primeiro contato com o Azure está sendo essencial para construir uma base sólida sobre computação em nuvem. Entender **modelos de serviço, infraestrutura, disponibilidade e custos** permite tomar decisões mais estratégicas e conscientes ao desenvolver soluções baseadas em nuvem.

---

## 🤓 Dica do Dia

> **"Evite usar serviços em *Preview* em ambientes de produção!"**  
> Porque no Azure, o que é *Preview* hoje, pode mudar ou sair do ar amanhã! 😂
