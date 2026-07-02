# SST_Cloud_Pro
# ☁️ SST Cloud Pro – Template de Portfólio

Um sistema de gestão de produção e Kanban focado em documentos de Saúde e Segurança do Trabalho (SST). 

Este repositório contém uma **versão de demonstração (Mock/Template)** de um sistema desenvolvido para otimizar o fluxo de trabalho de equipes técnicas. A aplicação roda 100% no navegador (Client-side), utilizando uma API simulada (`Mock Data`) para fins de exibição em portfólio.

---

## 🎯 O Desafio
Equipes de engenharia de segurança ocupacional lidam com múltiplos documentos complexos (PGR, PCMSO, LTCAT) e prazos rigorosos. O desafio foi criar uma interface leve e intuitiva que permitisse aos gestores acompanhar o status de cada documento em tempo real, calcular o tempo de produção e gerenciar serviços secundários.

---

## 🚀 Funcionalidades Demonstradas

* **Kanban Dinâmico:** Visualização do fluxo de trabalho em 8 colunas (Aguardando, Elaboração, Revisão, Aprovação, etc).
* **Cronômetro de SLA:** Contadores em tempo real baseados em *timestamps* que alertam se um card está parado além do tempo ideal (verde, amarelo e vermelho).
* **Cálculo de Complexidade:** Algoritmo simples que dimensiona a complexidade e o tempo de elaboração com base na quantidade de GHEs (Grupos Homogêneos de Exposição).
* **Serviços Secundários:** Painel isolado para check-list de serviços paralelos (ex: Dosimetria de Ruído, Varredura de Metais).
* **Dashboard e Relatórios:** Gráficos e tabelas gerados dinamicamente mostrando produtividade por técnico e alertas de atraso.

---

## 🛠️ Tecnologias Utilizadas

Para manter a aplicação leve e independente, optei por uma abordagem *Vanilla*:

* **HTML5:** Estrutura semântica e formulários.
* **CSS3:** Variáveis nativas (Custom Properties) para padronização de temas, layout em Grid/Flexbox e animações `@keyframes`.
* **JavaScript (ES6+):** Manipulação de DOM, manipulação de datas, simulação de requisições assíncronas (Promises) e lógica de negócio.

---

## 🕹️ Como testar o projeto (Live Demo)

Como o sistema foi adaptado para rodar de forma autônoma sem um backend real, testá-lo é muito simples:

1. Acesse o link do projeto (se hospedado no GitHub Pages) ou baixe o arquivo `index.html`.
2. Abra o arquivo no seu navegador preferido.
3. Na tela de login, digite **qualquer usuário e senha** (ex: `admin` / `admin`).
4. Navegue pelas abas, mova os cards, edite status e crie novas tarefas para ver a simulação da API funcionando.

---

> **Nota:** O sistema original foi desenvolvido integrando este frontend a um backend *Serverless* baseado em Google Apps Script e Google Sheets, utilizando integrações via API (requisições HTTP/REST). Os dados aqui presentes são fictícios para proteção de confidencialidade (LGPD).
