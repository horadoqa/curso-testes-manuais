# Testes Manuais - Do Requisito ao Relatório

**Objetivo da aula:**  
Planejamento, execução e documentação de testes manuais com base nos requisitos de uma funcionalidade (página de login).

---

## 1. Informações Gerais

- **Público-alvo**: Iniciantes ou iniciantes intermediários em QA
- **Pré-requisitos**: Conhecimentos básicos de web e noções de testes

---

## 2. Estrutura

### **1. Introdução aos Testes Manuais**

**O que são testes manuais?**

O teste manual, como o próprio nome nos indica, é feito manualmente por um analista, desenvolvedor ou especialista em qualidade. Nessa situação, a pessoa responsável pelos testes irá executar cada passo necessário para que o teste seja realizado com sucesso, sempre atento para as condições que o teste precisa para ser realizado da forma correta.

O teste manual costuma ter baixo valor de investimento e também permite que a pessoa que os realiza experimente condições semelhantes às do ambiente de produção, já que pode definir os parâmetros do teste manualmente.

Em compensação, testes manuais são mais lentos e como dependem totalmente da interação humana, sempre existe uma alta possibilidade de um problema passar despercebido por quem testa.

### 🧪 Diferença entre Teste Manual e Teste Automatizado

---

### 🔹 **Teste Manual**

**Definição:**  
O tester executa os testes **manualmente**, passo a passo, sem usar scripts ou ferramentas de automação.

**Características:**
- Baseado em **interação humana**.
- Ideal para **testes exploratórios**, usabilidade, testes pontuais ou que mudam com frequência.
- Exige **mais tempo** por teste.
- Pode ser mais propenso a **erros humanos**.

**Exemplo:**  
Você acessa a página de login, digita o e-mail e a senha, clica em "Entrar" e observa o comportamento do sistema.

---

### 🔸 **Teste Automatizado**

**Definição:**  
Os testes são executados automaticamente por meio de **scripts e ferramentas**, sem precisar de interação humana após estarem configurados.

**Características:**
- Baseado em **código/script**.
- Ideal para testes repetitivos, de regressão ou com grande volume.
- **Mais rápido** e escalável.
- Requer **conhecimento técnico** (linguagens, ferramentas como Selenium, Cypress, Playwright etc.).

**Exemplo:**  
Você escreve um script que acessa a página de login, insere e-mail e senha automaticamente, clica em "Entrar" e verifica se a página redirecionou corretamente.

---

### 🆚 Comparação Rápida:

| Aspecto              | Teste Manual                   | Teste Automatizado               |
|----------------------|-------------------------------|----------------------------------|
| Execução             | Manual (por um tester)        | Automática (por scripts)         |
| Velocidade           | Mais lento                    | Mais rápido                      |
| Custo inicial        | Baixo                         | Alto (precisa de tempo e ferramentas) |
| Manutenção           | Baixa                         | Alta (atualizar scripts)         |
| Erros humanos        | Pode acontecer                | Reduzido                         |
| Ideal para           | Usabilidade, testes pontuais  | Testes de regressão, carga etc.  |

---

### **2. Análise de Requisitos da Página de Login**

- Exemplo de requisitos funcionais:
  - O sistema deve permitir que o usuário insira e-mail e senha.
  - O sistema deve validar e-mail e senha obrigatórios.
  - Mensagens de erro devem ser exibidas em casos de falha.
  - Após login bem-sucedido, o usuário será redirecionado à página inicial.

- **Atividade:** Destacar possíveis cenários de teste com base nos requisitos.
  - O botão "Entrar" só será habilitado após o preenchimento correto.

---

### **3. Criação de Casos de Teste**

- Introdução ao conceito de caso de teste
- Estrutura:
  - ID
  - Título
  - Pré-condições
  - Passos
  - Resultado esperado
  - Resultado real
  - Status
- **Exemplo de Caso de Teste**:
  - **ID:** TC001
  - **Título:** Login com credenciais válidas
  - **Passos:**
    1. Acessar a página de login
    2. Informar e-mail válido
    3. Informar senha válida
    4. Clicar em "Entrar"
  - **Resultado esperado:** Usuário redirecionado para a home

---

### **4. Execução dos Testes**

- Execução prática dos testes em um protótipo ou sistema fictício
- Registro de bugs e observações
- Status do caso de teste: Passou, Falhou, Bloqueado

---

### **5. Registro de Bugs**

- Como reportar um bug corretamente
- Boas práticas:
  - Passos para reprodução
  - Comportamento esperado x comportamento real
  - Print da tela ou gravação
- Ferramentas sugeridas: Trello, Jira, Notion (simulado em aula)

---

### **6. Criação de Relatório de Testes**

- O que é um relatório de testes?
- Informações essenciais:
  - Funcionalidade testada
  - Número de casos de teste
  - Quantos passaram / falharam
  - Principais bugs encontrados
- Modelo simples de relatório em Excel ou Google Sheets

---

### **7. Discussão Final e Dúvidas**

- Dicas de carreira em QA Manual
- Próximos passos: testes exploratórios, automação, testes de API

---

## 3. Materiais e Recursos

### Login
- Requisitos e relatório: https://drive.google.com/drive/folders/1_4GC9upitDw7BKdn-yGjrXJ7F7RADsGl

### Cadastro
- Requisitos e relatório: https://drive.google.com/drive/folders/1XQaIyen5Pc8NfTwlGagp6oABFGdW85Fo

---