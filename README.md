## 🔎 Análise inicial da aplicação

### 🎯 Objetivo da aplicação

A aplicação aparenta ter como objetivo permitir o **cadastro e a visualização de cursos**, exibindo as informações em formato de **cards na interface**.

Cada curso contém informações como:

- Nome do curso
- Descrição
- Instrutor
- URL da imagem de capa
- Datas de início e término
- Número de vagas
- Tipo de curso

Após o cadastro, os cursos são exibidos em uma **lista visual**, permitindo que o usuário visualize os dados cadastrados e também realize a **exclusão do curso**.

---

### 🔄 Principais fluxos disponíveis

Durante a exploração da aplicação, foram identificados os seguintes fluxos principais:

📌 **Cadastro de cursos**

- Usuário acessa a página de cadastro
- Preenche as informações do curso
- Envia o formulário para criar um novo curso

📌 **Listagem de cursos**

- Os cursos cadastrados são exibidos na página de listagem
- Cada curso aparece em formato de **card**, contendo suas principais informações

📌 **Exclusão de cursos**

- O usuário pode excluir um curso diretamente pela listagem
- A ação é realizada através do botão **"Excluir curso"** presente no card

---

### ⚠️ Pontos críticos do sistema para teste

Durante a análise exploratória, alguns pontos foram considerados **mais críticos para testes**, pois impactam diretamente no funcionamento do sistema:

🧩 **Cadastro de cursos**

- Validação dos campos obrigatórios
- Aceitação de dados inválidos ou incompletos
- Consistência das informações enviadas no formulário

📋 **Exibição das informações na listagem**

- Verificar se todos os dados cadastrados são exibidos corretamente nos cards
- Garantir que as informações apresentadas correspondam aos dados inseridos

🗑️ **Exclusão de cursos**

- Verificar se a exclusão remove corretamente o curso da listagem
- Garantir consistência entre a mensagem de sucesso exibida e o comportamento do sistema

📐 **Comportamento visual da interface**

- Testar como o sistema lida com textos muito longos
- Verificar possíveis quebras de layout nos cards

---

A partir dessa análise inicial foi possível identificar **possíveis falhas de comportamento e oportunidades de melhoria**.
