# Helpdesk Automation

## 🚀 Descrição do Projeto

Este projeto demonstra a automação de tarefas comuns em um ambiente de Help Desk de TI utilizando **Python**. Ele simula o processamento de chamados, categorizando-os por urgência, gerando um relatório de **Service Level Agreement (SLA)** em formato HTML e simulando o envio de notificações por e-mail. 

O objetivo é apresentar habilidades em automação, manipulação de dados e geração de relatórios, competências essenciais para qualquer profissional de TI, especialmente em busca da primeira oportunidade de estágio.

## ✨ Funcionalidades

*   **Leitura de Chamados:** Processa uma lista de chamados a partir de um arquivo CSV utilizando a biblioteca Pandas.
*   **Categorização Automática:** Classifica os chamados com base em sua prioridade (Alta, Média, Baixa) em categorias de urgência (Crítico, Urgente, Normal).
*   **Monitoramento de SLA:** Calcula e exibe o status de conformidade com o SLA para cada chamado.
*   **Relatório Visual:** Gera um relatório HTML moderno e responsivo com estatísticas gerais e detalhes dos chamados através do motor de templates Jinja2.
*   **Notificação por E-mail:** Estrutura pronta para envio de e-mails via SMTP para gestores ou equipes de suporte.

## 🛠️ Tecnologias Utilizadas

*   **Python 3.x:** Linguagem base para toda a lógica de automação.
*   **Pandas:** Manipulação e análise de dados eficiente.
*   **Jinja2:** Criação de templates dinâmicos para o relatório HTML.
*   **smtplib:** Comunicação com servidores de e-mail (SMTP).
*   **HTML/CSS:** Estilização do relatório de SLA.

## 📁 Estrutura do Projeto

```text
helpdesk-automation/
├── main.py              # Script principal com a lógica de automação
├── tickets.csv          # Banco de dados simulado (CSV)
├── requirements.txt     # Dependências do projeto
├── README.md            # Documentação do projeto
└── templates/
    └── report.html      # Template HTML para o relatório
