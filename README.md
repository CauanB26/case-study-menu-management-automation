# Case Study: Menu Management Automation Tool (Domino's Brazil)

![Python](https://img.shields.io/badge/Python-3.x-blue.svg?style=for-the-badge&logo=python)
![Tkinter](https://img.shields.io/badge/Tkinter-GUI-orange.svg?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-1.x-green.svg?style=for-the-badge&logo=pandas)
![SQL Server](https://img.shields.io/badge/SQL%20Server-T--SQL-red.svg?style=for-the-badge&logo=microsoft-sql-server)

> **⚠️ Confidentiality Note:** This is a case study of a proprietary project developed for Domino's Brazil. The source code, exact table names, and other sensitive details cannot be shared publicly due to confidentiality and intellectual property agreements.

---

### 🎯 Project Goal

The objective of this project was to develop a robust desktop application to automate the product activation and deactivation process in the "Pulse" menu management system for Domino's Brazil stores, eliminating a critical operational bottleneck and freeing up the team for more strategic activities.

---

### 📈 The Scenario: A Daily Operational Challenge

As a developer and analyst, I identified a manual, slow, and repetitive process that consumed valuable time from the operations team. To manage a store's menu, the workflow was:

* Access two different Virtual Machines (VMs): the store's VM and the central "Pulse" system VM.
* Manually navigate through the slow Pulse system interface to locate and change each product, one by one.

The daily impact on the business was significant:

* **Volume of Demands:** An average of **15 to 20 stores** requested changes per day.
* **Complexity:** Each request contained an average of **5 products** to be modified.
* **Time Spent:** Each service ticket took about **6 minutes** to resolve, resulting in over **1.5 hours per day** dedicated exclusively to this task.

---

### ✨ The Solution: A Desktop Application with Python

To solve this problem, I developed a complete Python application that directly addresses the pain points of the manual process. The tool was built with the following technical features:

* **✅ Intuitive Graphical User Interface with `Tkinter`:**
    * I developed a GUI that allows the operations team to select the store and products visually and quickly.
    * I implemented category filters and checkboxes for bulk selection, completely eliminating the need to navigate the legacy Pulse interface.

* **✅ Data Manipulation with `Pandas`:**
    * The application uses Excel spreadsheets as a data source, containing product codes and names.
    * `Pandas` is used to read, filter, and efficiently prepare the data for the database update step.

* **✅ Optimized Batch SQL Script Generation:**
    * The core of the application dynamically generates Transact-SQL (T-SQL) scripts based on the selections made in the interface.
    * The logic ensures that all changes for a single ticket are grouped into a single atomic transaction, updating the database tables safely and efficiently.

---

### 🚀 Results and Impact

The implementation of this tool led to a drastic and measurable optimization of the process.

| Metric | Before Automation | After Automation | Percentage Gain |
| :--- | :--- | :--- | :---: |
| **Time per Ticket** | ~6 minutes (360s) | **~20 seconds** | **~94%** |
| **Total Daily Time** | > 1.5 hours | < 10 minutes | **~90%** |
| **Process** | Manual, via VMs and clicks | Automated, via GUI | N/A |

The main result was freeing up more than an hour of the team's daily work, which could be reallocated to more analytical and strategic activities.

---

### 🔮 Next Steps and Future Vision

The project is evolving. The next goal is to transform the application into an even more integrated automation solution:

* **Remote Execution:** Allow the script to be executed over the network directly in the store's environment with a single click in the interface, using only the Pulse ID provided by the user.
* **Total Elimination of VMs:** The ultimate goal is to completely remove the need for any manual access to virtual machines, creating a "one-click" workflow that is fully automated, fast, and scalable.

---

### 💡 Skills and Competencies Demonstrated

* **Robotic Process Automation (RPA):** Analysis and optimization of manual workflows.
* **GUI Development:** Building desktop interfaces with `Tkinter`.
* **Data Manipulation:** Reading, processing, and filtering data with `Pandas`.
* **Database:** Dynamic generation of SQL scripts and knowledge of T-SQL.
* **Business Analysis:** Identifying operational bottlenecks and proposing technical solutions with a direct impact on the business.
* **Solution Architecture:** Planning the evolution of the tool towards a distributed architecture.

&nbsp;
&nbsp;

---
---

&nbsp;
&nbsp;

## **Versão em Português**

---

# Case Study: Ferramenta de Automação para Gestão de Cardápios (Domino's Brasil)

![Python](https://img.shields.io/badge/Python-3.x-blue.svg?style=for-the-badge&logo=python)
![Tkinter](https://img.shields.io/badge/Tkinter-GUI-orange.svg?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-1.x-green.svg?style=for-the-badge&logo=pandas)
![SQL Server](https://img.shields.io/badge/SQL%20Server-T--SQL-red.svg?style=for-the-badge&logo=microsoft-sql-server)

> **⚠️ Nota de Confidencialidade:** Este é um case study de um projeto proprietário desenvolvido para a Domino's Brasil. O código-fonte, nomes exatos de tabelas e outros detalhes sensíveis não podem ser compartilhados publicamente devido a acordos de confidencialidade e propriedade intelectual.

---

### 🎯 Objetivo do Projeto

O objetivo deste projeto foi desenvolver uma aplicação de desktop robusta para automatizar o processo de ativação e desativação de produtos no sistema de gestão de cardápios (Pulse) das lojas Domino's Brasil, eliminando um gargalo operacional crítico e liberando a equipe para atividades de maior valor estratégico.

---

### 📈 O Cenário: Um Desafio Operacional Diário

Como desenvolvedor e analista, identifiquei um processo manual, lento e repetitivo que consumia um tempo valioso da equipe de operações. Para gerenciar o cardápio de uma loja, o fluxo era:

* Acessar duas Máquinas Virtuais (VMs) distintas: a VM da loja e a VM do sistema central "Pulse".
* Navegar manualmente pela interface lenta do sistema Pulse para localizar e alterar cada produto, um por um.

O impacto diário no negócio era significativo:

* **Volume de Demandas:** Em média, **15 a 20 lojas** solicitavam alterações por dia.
* **Complexidade:** Cada solicitação continha, em média, **5 produtos** a serem alterados.
* **Tempo Gasto:** Cada atendimento consumia cerca de **6 minutos**, resultando em mais de **1.5 horas por dia** dedicadas exclusivamente a esta tarefa.

---

### ✨ A Solução: Uma Aplicação Desktop com Python

Para resolver este problema, desenvolvi uma aplicação completa em Python que ataca diretamente os pontos de dor do processo manual. A ferramenta foi construída com os seguintes recursos técnicos:

* **✅ Interface Gráfica Intuitiva com `Tkinter`:**
    * Desenvolvi uma GUI que permite à equipe de operações selecionar a loja e os produtos de forma visual e rápida.
    * Implementei filtros por categoria e checkboxes para seleção em massa, eliminando completamente a necessidade de navegar na interface legada do Pulse.

* **✅ Manipulação de Dados com `Pandas`:**
    * A aplicação utiliza planilhas Excel como fonte de dados, contendo os códigos e nomes dos produtos.
    * O `Pandas` é usado para ler, filtrar e preparar os dados de forma eficiente para a etapa de atualização no banco de dados.

* **✅ Geração de SQL Otimizado em Lote:**
    * O núcleo da aplicação gera scripts Transact-SQL (T-SQL) dinamicamente com base nas seleções feitas na interface.
    * A lógica garante que todas as alterações de um chamado sejam agrupadas em uma única transação, atualizando as tabelas do banco de dados de forma atômica e segura.

---

### 🚀 Resultados e Impacto

A implementação da ferramenta gerou uma otimização drástica e mensurável no processo.

| Métrica | Antes da Automação | Depois da Automação | Ganho Percentual |
| :--- | :--- | :--- | :---: |
| **Tempo por Atendimento** | ~6 minutos (360s) por loja | **~20 segundos** | **~94%** |
| **Tempo Total Diário** | > 1.5 horas | < 10 minutos | **~90%** |
| **Processo** | Manual, via VMs e cliques | Automatizado, via GUI | N/A |

O principal resultado foi a liberação de mais de uma hora de trabalho diário da equipe, que pôde ser realocada para atividades mais analíticas e estratégicas.

---

### 🔮 Próximos Passos e Visão de Futuro

O projeto está em evolução. O próximo objetivo é transformar a aplicação em uma solução de automação ainda mais integrada:

* **Execução Remota:** Permitir que, com um clique na interface, o script seja executado via rede diretamente no ambiente da loja, usando apenas o ID do Pulse como parâmetro.
* **Eliminação Total de VMs:** O objetivo final é remover por completo a necessidade de qualquer acesso manual a máquinas virtuiais, criando um fluxo "one-click" totalmente automatizado e escalável.

---

### 💡 Habilidades e Competências Demonstradas

* **Automação de Processos (RPA):** Análise e otimização de fluxos de trabalho manuais.
* **Desenvolvimento de GUI:** Construção de interfaces de desktop com `Tkinter`.
* **Manipulação de Dados:** Leitura, tratamento e filtragem de dados com `Pandas`.
* **Banco de Dados:** Geração dinâmica de scripts SQL e conhecimento de T-SQL.
* **Análise de Negócios:** Identificação de gargalos operacionais e proposição de soluções técnicas com impacto direto no negócio.
* **Arquitetura de Soluções:** Planejamento da evolução da ferramenta para uma arquitetura distribuída.
