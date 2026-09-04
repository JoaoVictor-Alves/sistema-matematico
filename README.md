### Sistema Matemático 🧮

Um sistema simples desenvolvido em JavaScript (Node.js) contendo utilitários matemáticos, com foco no cálculo da equação de Bhaskara e operações de divisão. 

### 🚀 Funcionalidades

* **Fórmula de Bhaskara:** Calcula automaticamente o valor de Delta (

Δcap delta
Δ
), 

X1cap X sub 1
𝑋1
 e 

X2cap X sub 2
𝑋2
 a partir dos coeficientes a, b e c.
* **Validações de segurança:** 

  * Impede o cálculo se o coeficiente a for igual a zero (equações de 2º grau inválidas).
  * Trata cenários onde o Delta é negativo (raízes reais inexistentes).
* **Módulo de Calculadora:** Contém operações básicas como divisão, com validação para impedir divisões por zero.

### 🛠️ Tecnologias Utilizadas

* **JavaScript (ES6+)**
* **Node.js** (ambiente de execução)

### 📂 Estrutura do Projeto

* bhaskara.js — Módulo responsável pela lógica e validações da Equação de Bhaskara.
* calculadora.js — Módulo com operações matemáticas como a divisão estruturada.
* index.js — Arquivo principal que executa e testa as funções do sistema.

### 💻 Como Executar o Projeto

1. Certifique-se de ter o [Node.js](https://nodejs.org/) instalado em sua máquina.
2. Abra o terminal na pasta do projeto.
3. Execute o comando principal: 

bash

node index.js

Use o código com cuidado.