# 🎮 Jogo da Velha (Tic-Tac-Toe) com React

Este projeto implementa o clássico Jogo da Velha usando React, seguindo o tutorial oficial do React. É um projeto educacional que demonstra os conceitos fundamentais do React através de uma aplicação interativa e funcional.

## 📋 Índice

- [Funcionalidades](#-funcionalidades)
- [Pré-requisitos](#-pré-requisitos)
- [Instalação](#-instalação)
- [Como Executar](#-como-executar)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Conceitos Aprendidos](#-conceitos-aprendidos)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Referência](#-referência)
- [Licença](#-licença)

## ✨ Funcionalidades

- ✅ Tabuleiro 3x3 exibido no navegador
- ✅ Alternância entre os jogadores "X" e "O"
- ✅ Indicação do próximo jogador ou vencedor
- ✅ Lista de jogadas anteriores clicáveis (time travel)
- ✅ Histórico completo de jogadas
- ✅ Interface responsiva e moderna
- ✅ Detecção automática de vencedor

## 📦 Pré-requisitos

Antes de começar, certifique-se de ter instalado:

- [Node.js](https://nodejs.org/) (versão 16 ou superior)
- [npm](https://www.npmjs.com/) (geralmente vem com o Node.js)

## 🚀 Instalação

1. Clone o repositório ou baixe os arquivos do projeto

2. Instale as dependências:
```bash
npm install
```

## ▶️ Como Executar

### Modo de Desenvolvimento

Execute o servidor de desenvolvimento:
```bash
npm run dev
```

O projeto estará disponível em `http://localhost:5173`

### Build para Produção

Para criar uma versão otimizada para produção:
```bash
npm run build
```

Os arquivos serão gerados na pasta `dist/`

### Preview da Build

Para visualizar a build de produção localmente:
```bash
npm run preview
```

## 📁 Estrutura do Projeto

```
exercicio-2/
├── src/
│   ├── Square.jsx      # Componente que representa um quadrado do tabuleiro
│   ├── Board.jsx       # Controla o estado dos quadrados e lógica do jogo
│   ├── Game.jsx        # Gerencia histórico e renderiza o tabuleiro
│   ├── main.jsx        # Ponto de entrada da aplicação
│   └── styles.css      # Estilos da aplicação
├── index.html          # HTML principal
├── package.json        # Dependências e scripts do projeto
├── vite.config.js      # Configuração do Vite
├── README.md           # Este arquivo
└── LICENSE             # Licença do projeto
```

## 🎓 Conceitos Aprendidos

Este projeto demonstra os seguintes conceitos fundamentais do React:

- **Componentização e hierarquia de componentes** - Organização do código em componentes reutilizáveis
- **Props e callbacks de eventos (onClick)** - Comunicação entre componentes
- **Gerenciamento de estado com useState** - Controle do estado da aplicação
- **Imutabilidade de arrays (slice())** - Criação de novas versões dos dados
- **Lifting state up** - Elevação do estado para controle centralizado
- **Renderização condicional e map() para listas** - Renderização dinâmica de elementos
- **Histórico e time travel no React** - Navegação pelo histórico de estados

## 🛠️ Tecnologias Utilizadas

- [React](https://react.dev/) - Biblioteca JavaScript para construção de interfaces
- [Vite](https://vitejs.dev/) - Ferramenta de build e desenvolvimento
- HTML5 e CSS3 - Estrutura e estilização

## 📚 Referência

Este conteúdo foi adaptado com fins educacionais a partir do tutorial oficial:
**[Tutorial: Tic-Tac-Toe - React Docs (pt-BR)](https://pt-br.react.dev/learn/tutorial-tic-tac-toe)**

© Meta Platforms / React Team. Utilização mediante autorização para fins de ensino.

## 📄 Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
