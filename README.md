# Web Chat Application

![Project Status](https://img.shields.io/badge/status-active-brightgreen.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

## 📖 Sobre o Projeto

Web Chat é uma aplicação de chat em tempo real desenvolvida como um fork de um projeto original (insira o nome do projeto original, se aplicável). Este fork adiciona melhorias, novas funcionalidades e correções para oferecer uma experiência de comunicação instantânea robusta e escalável. A aplicação permite que usuários criem salas de chat, enviem mensagens em tempo real e interajam de forma segura e eficiente.

### Principais Funcionalidades
- **Chat em Tempo Real**: Comunicação instantânea usando WebSockets.
- **Salas de Chat**: Crie ou entre em salas públicas ou privadas.
- **Autenticação de Usuários**: Suporte a login/registro (se aplicável).
- **Interface Intuitiva**: Design responsivo construído com [insira tecnologias de front-end, ex.: HTML, CSS, JavaScript, React].
- **Personalizações**: [Adicione funcionalidades específicas do seu fork, ex.: suporte a emojis, envio de arquivos, etc.].

## 🛠 Tecnologias Utilizadas

- **Back-end**: [nestJs, typeScript, PrismaORM ]

- **Outras Ferramentas**: [Docker]

## 🚀 Como Começar

Siga as instruções abaixo para configurar e executar o projeto localmente.

### Pré-requisitos
- [Node.js](https://nodejs.org/) (versão 21 ou superior)
- [npm](https://www.npmjs.com/) ou [Yarn](https://yarnpkg.com/)
- [Opcional: MongoDB, se aplicável] ou outra dependência específica

### Instalação

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/Guikino/web_chat-fork.git
   cd web_chat-fork
   ```

2. **Instale as dependências**:
   ```bash
   npm install
   ```

3. **Configure as variáveis de ambiente**:
   Crie um arquivo `.env` na raiz do projeto e adicione as configurações necessárias, como:
   ```
   PORT=3000
   DATABASE_URL=mongodb://localhost:27017/web_chat
   SECRET_KEY=sua_chave_secreta
   ```


4. **Inicie o servidor**:
   ```bash
   npm start
   ```

5. **Acesse a aplicação**:
   Abra seu navegador e vá para `http://localhost:3000`.

### Executando com Docker (se aplicável)
1. Certifique-se de ter o [Docker](https://www.docker.com/) instalado.
2. Construa e inicie os contêineres:
   ```bash
   docker-compose up --build
   ```

## 🤝 Como Contribuir

Contribuições são bem-vindas! Siga os passos abaixo para contribuir:

1. Faça um fork do repositório.
2. Crie uma branch para sua feature ou correção:
   ```bash
   git checkout -b minha-nova-feature
   ```
3. Commit suas alterações:
   ```bash
   git commit -m "Adiciona minha nova feature"
   ```
4. Envie para o repositório remoto:
   ```bash
   git push origin minha-nova-feature
   ```
5. Abra um Pull Request descrevendo suas alterações.

## 🐛 Reportando Bugs

Se encontrar algum problema, por favor, abra uma [issue](https://github.com/Guikino/web_chat-fork/issues) descrevendo o bug, incluindo:
- Passos para reproduzir
- Comportamento esperado
- Capturas de tela, se aplicável



## 🌟 Agradecimentos

- Ao projeto original [https://github.com/GmfSouza/web_chat].
- A todos os contribuidores que ajudaram a melhorar este fork.

---

**Contato**:  macedoguilherme55@gmail.com
**Repositório**: https://github.com/Guikino/web_chat-fork