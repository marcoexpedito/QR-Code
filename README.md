# 🧠 Desafio DIO - QR Code Generator

Este repositório contém a solução para o desafio proposto pela [Digital Innovation One (DIO)](https://www.dio.me/) onde o objetivo era **gerar um QR Code com base em uma entrada do usuário**, **sem o uso de HTML5 e CSS3**.

## 📝 Descrição do Desafio

Neste desafio, o usuário deve inserir um link (ou outro dado) e, a partir disso, o sistema retorna um QR Code correspondente. A proposta serve como exercício de lógica e integração com bibliotecas externas no ecossistema JavaScript.

## 🧩 Abordagem do Projeto
O projeto foi desenvolvido utilizando JavaScript com execução no ambiente Node.js, com foco na manipulação de entrada do usuário e geração de QR Codes diretamente no terminal. Uma forma prática de exercitar o uso de bibliotecas do ecossistema Node e interação via linha de comando.

📦 Uso da biblioteca qrcode-terminal

💻 Execução 100% via terminal

🧠 Foco na lógica e manipulação de dados com JavaScript

🛠️ Ideal para praticar integração de bibliotecas externas e entrada/saída de dados

## 🛠️ Tecnologias e Ferramentas

- JavaScript (ES6+)
- [qrcode-terminal](https://www.npmjs.com/package/qrcode-terminal) (para gerar QR no terminal)
- Ambiente Node.js

## 🚀 Como Executar

### 1. Clone o repositório
``bash
git clone https://github.com/marcoexpedito/QR-Code.git
cd QR-Code

npm install

node index.js

📂 Estrutura do Projeto

QR-Code/
├── index.js           # Script principal
├── package.json       # Informações do projeto e dependências
└── README.md          # Este arquivo


📸 Exemplo de Saída no Terminal

Digite o link para gerar o QR Code:
https://dio.me

█████████████████████████████
██ ▄▄▄▄▄ ██ ▄▄▄ █ ▄▄▄▄▄ ██
██ █   █ ██ █ █ █ █   █ ██
██ █▄▄▄█ ██ █ █▄█ █▄▄▄█ ██
██▄▄▄▄▄█ ██▄▄▄█▄█▄▄▄▄▄█ ██
...

👨‍💻 Autor
Desenvolvido por Marco Expedito 🚀
Desafio realizado durante o bootcamp da Digital Innovation One.
