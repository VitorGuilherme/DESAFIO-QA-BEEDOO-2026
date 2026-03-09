# 🧪 DESAFIO-QA-BEEDOO-2026

Este repositório contém a análise, os cenários de teste e os resultados obtidos durante o desafio técnico de QA proposto pela Beedoo.

O objetivo foi avaliar o funcionamento do módulo de **cadastro e listagem de cursos**, identificando possíveis falhas, inconsistências e oportunidades de melhoria na aplicação.

---

# 🔎 1. Análise da aplicação

## 🎯 Objetivo da aplicação

A aplicação tem como objetivo permitir o **cadastro e a visualização de cursos**, exibindo suas informações em formato de **cards** na interface.

Cada curso pode conter informações como:

- Nome do curso
- Descrição
- Instrutor
- URL da imagem de capa
- Data de início
- Data de fim
- Número de vagas
- Tipo de curso

Após o cadastro, os cursos são exibidos na página de listagem, onde também é possível **excluir cursos cadastrados**.

---

## 🔄 Principais fluxos disponíveis

Durante a exploração da aplicação foram identificados os seguintes fluxos principais:

📌 **Cadastro de cursos**

- Acessar a página de cadastro
- Preencher as informações do curso
- Enviar o formulário para criação

📌 **Listagem de cursos**

- Visualizar os cursos cadastrados
- Conferir as informações exibidas nos cards

📌 **Exclusão de cursos**

- Remover cursos através do botão **Excluir curso**

---

## ⚠️ Pontos críticos para testes

Durante a análise exploratória, alguns pontos foram considerados mais críticos para validação:

🧩 **Cadastro de cursos**

- Validação dos campos do formulário
- Consistência dos dados cadastrados

📋 **Exibição das informações**

- Conferência das informações exibidas nos cards
- Integridade entre dados cadastrados e exibidos

🗑️ **Exclusão de cursos**

- Verificar se o curso é realmente removido da listagem
- Conferir consistência entre mensagens exibidas e comportamento do sistema

🎨 **Comportamento da interface**

- Testar textos muito longos
- Verificar possíveis quebras de layout

---

# 🧪 2. Criação de cenários e casos de teste

Com base na análise exploratória da aplicação, foram definidos cenários de teste para validar o funcionamento do módulo de cursos.

Os testes foram elaborados considerando:

- Fluxo principal de cadastro de curso
- Listagem de cursos
- Cenários negativos
- Validações de campos
- Comportamentos inesperados

A estratégia adotada foi baseada em **testes exploratórios**, seguidos da criação de cenários focados nos fluxos principais da aplicação.

---

# 📊 3. Casos de teste

Todos os cenários e casos de teste foram documentados em uma planilha no **Google Sheets**, contendo:

- ID do teste
- Descrição do cenário
- Pré-condições
- Passos para execução
- Resultado esperado
- Resultado obtido
- Status do teste
- Severidade
- Evidências

🔗 **Acesse os casos de teste:**

👉 https://docs.google.com/spreadsheets/d/15WiWkEXvoz0qM1qhHZGLFmw2Erl43vK_ULsqnb33d1k/edit?usp=sharing

---

# 🧪 4. Execução dos testes

Os cenários documentados foram executados manualmente na aplicação.

Durante a execução foram registradas:

- Evidências dos testes realizados
- Resultados obtidos
- Bugs identificados

---

# 🐞 5. Relatório de Bugs

Durante os testes exploratórios foram identificados alguns problemas no sistema.

### 🧩 Principais problemas encontrados

- ⚠️ Exclusão de curso retorna sucesso mas não remove o card (HTTP 405)
- ⚠️ Cadastro de curso permitido sem validação de campos
- 🐞 Campo **Instrutor** não aparece no card de listagem
- 🎨 Títulos muito grandes quebram o layout do card
- ⚠️ Número de vagas negativo permitido
- ⚠️ Data final menor que a data inicial permitida

O relatório completo contendo descrição detalhada dos bugs pode ser acessado abaixo:

🔗 **Relatório completo de bugs**

👉 https://www.notion.so/Beedoo-QA-Challenge-Relat-rio-de-Bugs-31e1763e039880c5bc5ef42f9973ed65?source=copy_link

---

# 📂 Evidências

As evidências dos testes executados podem ser encontradas nos materiais anexados ao relatório de bugs e na planilha de casos de teste.

---

# ✅ Conclusão

Através da análise exploratória e execução dos cenários de teste foi possível identificar inconsistências no comportamento da aplicação, principalmente relacionadas a:

- ausência de validações no formulário de cadastro
- inconsistência na exclusão de cursos
- problemas de exibição de dados
- falhas visuais na interface

A documentação apresentada neste repositório reúne os cenários testados, evidências coletadas e os bugs identificados durante o processo de teste.
