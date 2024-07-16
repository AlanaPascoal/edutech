# PLANO DE TRABALHO

**Nome do Projeto:** EduTech  
**Versão:** 2.0  
**Status:** Em andamento  
**Executor Principal:** Kayth Kariny  
**Coordenador do Projeto:** Andrey Rodrigues  

---

## HISTÓRICO DE VERSÕES

| Versão | Descrição                   | Autor       | Data |
|--------|-----------------------------|-------------|------|
| 1.0    | Elaboração do Plano de Trabalho | Kayth Kariny | 8/06/2024 |
| 2.0    | Correção do Plano de Trabalho | Kayth Kariny | 14/07/2024 |
---

## ÍNDICE

---

## 1. INTRODUÇÃO

### 1.1 Objeto

Desenvolver um sistema em que professores possam compartilhar cursos online de maneira eficiente e intuitiva. A plataforma incluirá suporte para vídeos educacionais, quizzes interativos, fóruns de discussão e ferramentas avançadas para monitoramento do progresso dos alunos.

### 1.2 Motivação, Justificativa e Oportunidade

Este projeto surge da alta demanda por plataformas educacionais online, especialmente devido à crescente adoção do ensino a distância. Nosso objetivo é desenvolver uma plataforma que não só facilite, mas também enriqueça o aprendizado técnico e prático. Implementaremos ferramentas interativas e integradas para melhorar significativamente a experiência de aprendizado e a aplicação do conhecimento.

### 1.3 Caracterização do Projeto

#### 1.3.1 Classe

| Classe    | Detalhamento                                                                         |
|-----------|--------------------------------------------------------------------------------------|
| Plataforma web | Desenvolvimento de uma plataforma web responsiva para facilitar a criação e interação de conteúdos educacionais entre professores e alunos. |

#### 1.3.2 Enquadrabilidade

| Enquadrabilidade           | Detalhamento                                                                                                           |
|----------------------------|------------------------------------------------------------------------------------------------------------------------|
| LGPD (Lei Geral de Proteção de Dados) | Garante a privacidade e proteção dos dados dos usuários.|
| LDB (Lei de Diretrizes e Bases da Educação)| Alinha a plataforma com as diretrizes educacionais nacionais.|
| Acessibilidade | Atende aos padrões de acessibilidade para garantir que a plataforma seja utilizável por todos os alunos, inclusive aqueles com deficiência.|
| Segurança | Implementa medidas de segurança para proteger os dados e a integridade do sistema.|

#### 1.3.3 Tipo

| Tipo                    | Detalhamento                                                                 |
|-------------------------|------------------------------------------------------------------------------|
| Desenvolvimento Software | Desenvolvimento de uma plataforma educacional online com recursos personalizados para atender às necessidades de professores e alunos com integração com gateways de pagamento. |

---

## 2. INFORMAÇÕES GERAIS

### 2.1 Objetivo

Desenvolver uma plataforma educacional online com funcionalidades avançadas, focada em facilitar a interação entre professores e alunos, promovendo um ambiente de aprendizado interativo e eficaz.

### 2.2 Escopo Geral

Desenvolvimento de um sistema abrangente de educação online, incluindo funcionalidades como upload e gerenciamento de vídeos, criação de quizzes, monitoramento de progresso, gestão de tarefas e feedback contínuo para melhorar a experiência de aprendizado.

#### 2.2.1 Escopo Específico

Implementação de funcionalidades para:
- Upload e gerenciamento de vídeos educacionais
- Criação de quizzes interativos
- Acompanhamento do progresso dos alunos
- Criação e automação de desafios de programação
- Feedback automático e contínuo
- Avaliação por pares
- Notificações e alertas
- Personalização de perfis de alunos
- Sistema de mensagens privadas
- Análise de sentimento de feedback
- Relatórios de acessibilidade
- Assistente de planejamento de curso

#### 2.2.2 Escopo Negativo

- A plataforma será exclusivamente web responsiva; não serão desenvolvidas versões nativas para iOS/Android.
- Não está planejada integração com sistemas externos como LMS já existentes ou ferramentas de videoconferência como Zoom ou Google Meet.
- A plataforma não fornecerá conteúdos educacionais próprios; seu objetivo é permitir que professores criem e compartilhem seus materiais.
- Não serão incluídas funcionalidades avançadas de inteligência artificial, como tutoriais adaptativos baseados em aprendizado de máquina.

### 2.3 Ambiente de Desenvolvimento

| Ferramentas e Tecnologias          | Modelo e Especificações                                                     |
|------------------------------------|------------------------------------------------------------------------------|
| Desenvolvimento                    | IDE: Visual Studio Code, Linguagem de Programação: JavaScript, Frameworks: Next.js, NestJS, Banco de Dados: Postgres, Firebase, Hospedagem Backend: Render, Hospedagem Frontend: Vercel, Modelagem do Sistema: Draw.io |
| Design                             | UI/UX Design: Figma                                                         |
| Teste                              | Teste Automatizado: Selenium, Cypress, Appium, Gestão de Testes e Rastreamento de Bugs: Github Projects, Teste de Performance: SonarQube |

### 2.4 Características Inovadoras do Projeto

- Interface de usuário intuitiva e responsiva:** Focada na facilidade de uso e acessibilidade.
- Quizzes interativos:** Ferramentas para criação de quizzes que tornam o aprendizado mais dinâmico.
- Análise de sentimento de feedback:** Utilização de técnicas de análise de sentimento para entender a opinião dos alunos sobre os conteúdos.
- Ferramentas avançadas de monitoramento de progresso:** Relatórios detalhados e visualizações sobre o desempenho dos alunos.

### 2.5 Resultados Esperados

Aumento da eficiência e eficácia do ensino a distância, maior engajamento dos alunos e uma plataforma robusta que atende plenamente às necessidades de professores e alunos.

---

## 3. METODOLOGIA DE PROJETO

### 3.1 Estrutura do Projeto

O projeto será dividido em fases, cada uma com entregas específicas e um cronograma detalhado para garantir um progresso organizado e eficiente.

### 3.2 Equipe de Projeto: Papéis e Responsabilidades dos Integrantes

| Responsabilidade | Profissional          |
|------------------|-----------------------|
| PO               | Andrey Rodrigues      |
| Scrum Master     | Andrey Rodrigues      |
| UX/UI Designer   | Alana Pascoal         |
| Desenvolvedor Frontend | Jhonatha Torres  |
| Tester           | Kayth Kariny          |
| Desenvolvedor Backend  | Leyvijane Ferreira |
| Desenvolvedor Frontend | Thiago Bruce     |

### 3.3 Fases, Atividades e Cronograma

**Fase I: Especificação – Janeiro/Fevereiro:**
- Definição dos requisitos do sistema
- Criação dos documentos de especificação

**Fase II: Inspeção – Março/Abril:**
- Revisão e validação dos requisitos
- Aprovação da especificação

**Fase III: Projeto e Arquitetura – Maio/Junho:**
- Definição da arquitetura do sistema
- Criação de protótipos iniciais

**Fase IV: Prototipagem e Refinamento – Julho:**
- Desenvolvimento de protótipos funcionais
- Feedback e refinamento dos protótipos

**Fase V: Desenvolvimento Completo – Agosto:**
- Desenvolvimento de protótipos funcionais
- Feedback e refinamento dos protótipos

**Fase VI: Encerramento – Setembro:**
- Testes finais e validação
- Implementação e lançamento

### 3.4 Entregas de cada Fase

| Fase                      | Mês    | Entregável                             |
|---------------------------|--------|----------------------------------------|
| I. Especificação          | Jan/Fev | Documentos de Requisitos               |
| II. Inspeção              | Mar/Abr | Revisão e Aprovação da Especificação   |
| III. Projeto e Arquitetura | Mai/Jun | Protótipos e Documentação de Arquitetura |
| IV. Prototipagem e Refinamento | Jul | Protótipos Funcionais Refinados         |
| V. Desenvolvimento Completo | Agos  | Funcionalidades Implementadas e Testadas |
| VI. Encerramento          | Set    | Sistema Implementado e Validado        |

### 3.5 Controle de Mudanças

O monitoramento e controle do escopo do projeto serão realizados a partir das seguintes diretrizes:
- Requisitos do projeto devem ser compreendidos por todos os membros da equipe.
- Todas as questões técnicas, de entregas e do cronograma que a equipe do projeto possui devem ser respondidas.
- Todas as entregas devem ser acordadas pela equipe do projeto e entidades parceiras.
- Todas as informações devem estar atualizadas no escopo e não-escopo.
- Nenhum trabalho fora do escopo do projeto deve ser feito.
- Solicitações de mudança no escopo do projeto devem ser efetivamente comunicadas e compreendidas.

---
