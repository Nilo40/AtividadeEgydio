<h1 align="center">
  <img src="logoCallmeapp.png" alt="Callme App" width="150"/>
  <br>
  Callme App
</h1>

<p align="center">🚀 O futuro do atendimento com inteligência artificial</p>

<div align="center">

[![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)]()
[![License](https://img.shields.io/badge/license-MIT-green)]()
[![React Native](https://img.shields.io/badge/React%20Native-0.72-blue)]()
[![TypeScript](https://img.shields.io/badge/TypeScript-✓-3178C6)]()

</div>

---

## 📖 Sobre o Projeto  

O **Callme App** é um aplicativo mobile para **abertura e gerenciamento de chamados** por funcionários para a assistência técnica, com suporte integrado de **IA**.  

🔹 Funcionários abrem chamados no app.  
🔹 A **IA** recebe o chamado e sugere uma solução imediata.  
🔹 Caso não seja resolvido, o chamado é **encaminhado automaticamente ao técnico responsável**.  

O desenvolvimento foi feito com **React Native + TypeScript**, utilizando **Scrum** como metodologia ágil.  

> 🎯 Motivação: A ideia surgiu devido à insatisfação com softwares existentes que não oferecem integração com inteligência artificial.  

---
##🧠 Resumo do Desafio

O CallMe App nasceu para resolver a dificuldade da empresa parceira em gerenciar e acompanhar chamados técnicos de forma eficiente. O processo manual gerava atrasos, falhas de comunicação e retrabalho.
Com o uso de Inteligência Artificial, o sistema automatiza a classificação dos chamados e sugere soluções, oferecendo agilidade, organização e inteligência operacional em plataformas desktop, web e mobile.

---

##  Backlog do Produto

### Sprint 1: Estrutura e Preparação do Ambiente
- Configuração completa do ambiente de desenvolvimento e integração com ferramentas de versionamento (Git).
- Criação e configuração do banco de dados SQL Server, definindo tabelas e relacionamentos iniciais.
- Definição da arquitetura modular do sistema, garantindo escalabilidade e facilidade de manutenção.
- Implementação das primeiras camadas de segurança, incluindo criptografia de senhas e autenticação básica.

### Sprint 2: Módulo de Usuários e Autenticação
- Desenvolvimento do cadastro de usuários com validação de dados e tratamento de erros.
- Implementação do sistema de login e autenticação, contemplando diferentes níveis de permissão (usuário comum, técnico, administrador).
- Realização de testes unitários e de integração para assegurar estabilidade e funcionamento correto

### Sprint 3: Gestão de Chamados
- Criação da funcionalidade para abertura e acompanhamento de chamados.
- Desenvolvimento da interface de exibição e filtragem de chamados por status e prioridade.
- Integração com o banco de dados e realização de testes de consistência e desempenho. 

### Sprint 4: Inteligência Artificial e Automação
- Treinamento inicial da IA de classificação, utilizando histórico de chamados (com dados simulados, se necessário).
- Implementação da sugestão automática de soluções com base em padrões identificados.
- Ajustes e refinamentos no modelo de IA a partir dos resultados dos testes.

### Sprint 5: Otimização, Segurança e Entrega Final
- Aplicação de melhorias de segurança avançadas (como tokens JWT e políticas de acesso).
- Refatoração do código e ajustes na arquitetura para otimizar desempenho e legibilidade.
- Elaboração da documentação técnica e do usuário, além de testes finais de validação e usabilidade.
- Configuração de logs e monitoramento básico do sistema para manutenção contínua.

---
## Cronograma de Evolução
<img src="Callme/Cronograma.png" alt="Cronograma"/>

---
## Tabela das Sprints

| Sprint | Período (2025) | Objetivos | Entregas | Documentação |
|--------|----------------|-----------|----------|--------------|
| *Sprint 1 — Estrutura e Preparação do Ambiente* | *19-08/26-08* | Configuração do ambiente de desenvolvimento, integração com Git, criação e configuração do banco de dados SQL Server, definição da arquitetura modular, implementação de segurança inicial. | Ambiente dev configurado, Git integrado, SQL Server com tabelas e relacionamentos, arquitetura modular definida, criptografia de senhas. | Documentação do ambiente, arquitetura e configuração inicial do banco de dados. |
| *Sprint 2 — Módulo de Usuários e Autenticação* | *26/08-02/09* | Desenvolvimento do cadastro de usuários, validação de dados, sistema de login e autenticação com níveis de permissão, testes unitários e de integração. | CRUD de usuários, login/logout com diferentes permissões (usuário, técnico, admin), testes unitários realizados. | Documentação do sistema de autenticação, níveis de permissão e testes realizados. |
| *Sprint 3 — Gestão de Chamados* | *02/09-09/09* | Criação da funcionalidade de abertura e acompanhamento de chamados, interface para exibição e filtragem de chamados, integração com banco de dados, testes de consistência e desempenho. | Formulário de abertura de chamados, listagem filtrável por status e prioridade, integração com DB, testes realizados. | Documentação da funcionalidade de chamados, filtragem e integração com o banco de dados. |
| *Sprint 4 — Inteligência Artificial e Automação* | *16/09 – 23/09* | Treinamento inicial da IA de classificação, implementação de sugestões automáticas de soluções, ajustes no modelo de IA com base nos testes. | Modelo de IA para classificação de chamados, endpoint de sugestão automática de soluções, ajustes e métricas iniciais. | Documentação sobre IA, fluxos de sugestões automáticas e melhorias realizadas. |
| *Sprint 5 — Otimização, Segurança e Entrega Final* | *23/09 – 30/09* | Melhorias de segurança avançadas (JWT, políticas de acesso), refatoração de código, ajustes na arquitetura para otimização, documentação técnica e do usuário, testes finais de validação e usabilidade. | Segurança otimizada, código refatorado, arquitetura melhorada, sistema estável, documentação completa. | Documentação técnica e do usuário, guia de segurança, resultados de testes finais. |
| *Entrega Final* | *07/10* | Versão 1.0 do sistema finalizada e entregue. | Sistema funcional e protótipo completo, documentação pronta. | Documentação final do sistema e plano de manutenção. |

---

## 🛠️ Tecnologias Utilizadas  

- [React Native](https://reactnative.dev/)  
- [TypeScript](https://www.typescriptlang.org/)  
- [Node.js](https://nodejs.org/pt)  
- [Android Studio](https://developer.android.com/studio)  
- [Astah UML](https://astah.net/products/astah-uml/)  
- [Trello](https://trello.com/)  

---

## 📂 Estrutura do Repositório  

- **/Callme/Modelagem_de_Requisitos** → Diagramas, backlog, casos de uso  
- **/Callme/PIM** → Documentação acadêmica (PIM 3º semestre)  
- **/Callme/code** → Código-fonte do app  

---

## 🗒️ Documentação  

- [📌 Diagramas UML](https://github.com/Nilo40/AtividadeEgydio/Callme/Modelagem_de_Requisitos/Diagrama_de_caso_de_uso_sistema_corrigido.asta)  
- [📌 Sprint Backlog](https://github.com/Devluisgsouza/Callme_App/blob/main/Callme/Modelagem_de_Requisitos/Sprints_Backlog.docx)  
- [📌 Casos de Uso](https://github.com/Devluisgsouza/Callme_App/blob/main/Callme/Modelagem_de_Requisitos/Descrição_caso_de_uso.docx)  
- [📌 Documentação Completa](https://github.com/Devluisgsouza/Callme_App/blob/main/Callme/PIM/PIM%203%20SEMESTRE.doc)  

<img src="Callme/Diagrama.jpg" alt="Diagrama"/>

---

## 🚀 Como Rodar o Projeto  

### Pré-requisitos  
- [Android Studio](https://developer.android.com/studio)  
- [Node.js](https://nodejs.org/pt)  
- [Expo CLI](https://expo.dev/)  

### Passo a passo  

```bash
# Clone o projeto
$ git clone https://github.com/Devluisgsouza/Callme_App.git 

# Entre no diretório
$ cd Callme/code

# Instale as dependências
$ npm install

# Instale o Expo CLI (caso não tenha)
$ npm install -g expo-cli

# Inicie o projeto
$ npx expo start

```bash
    # Conectar o código ao emulador android
    $ npm run android
```

## Dev do Projeto

| Nome do Aluno         | RA      | Turma   |
|-----------------------|---------|---------|
| Danilo Alves da Silva | R080CJ4 | DS4P48  |
