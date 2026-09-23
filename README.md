# 🐪 SOUQ

> **Um jogo tático de comércio, risco e negociação para 2 jogadores.**  
> Inspirado no aclamado jogo de tabuleiro **Jaipur** (criado por Sébastien Pauchon).

Disponível para jogar online em: **[https://souq-455x.onrender.com/](https://souq-455x.onrender.com/)**

---

## 📌 Sumário

- [Sobre o Jogo](#-sobre-o-jogo)
- [Onde Jogar](#-onde-jogar)
- [Modos de Jogo](#-modos-de-jogo)
- [Regras e Como Jogar](#-regras-e-como-jogar)
  - [Objetivo](#objetivo)
  - [Ações Disponíveis](#ações-disponíveis-escolha-uma-por-turno)
  - [Bônus de Combos](#bônus-de-combos)
  - [O Rebanho de Camelos](#o-rebanho-de-camelos)
  - [Fim de Rodada e Vitória](#fim-de-rodada-e-vitória)
- [Recursos da Plataforma](#-recursos-da-plataforma)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Como Rodar o Projeto Localmente](#-como-rodar-o-projeto-localmente)
- [Estrutura do Repositório](#-estrutura-do-repositório)
- [Créditos e Inspiração](#-créditos-e-inspiração)

---

## 📜 Sobre o Jogo

**Souq** (termo em árabe para mercado tradicional/bazar) coloca dois mercadores frente a frente competindo pelo título de comerciante oficial do Sultão.

Gerencie seus recursos com sabedoria, antecipe os movimentos do adversário, controle o rebanho de camelos no deserto e decida o momento ideal de liquidar seus bens antes que os preços caiam!

---

## 🌐 Onde Jogar

Você pode jogar diretamente pelo navegador em qualquer dispositivo (desktop, tablet ou smartphone), sem necessidade de instalação ou cadastro:

👉 **[https://souq-455x.onrender.com/](https://souq-455x.onrender.com/)**

---

## 🎮 Modos de Jogo

### 1. 👥 Multiplayer Online (Amigos)

- Crie uma sala e receba um **código numérico de 4 dígitos**.
- Compartilhe o código com um amigo para jogarem em tempo real, cada um em sua tela.
- Inclui suporte à **reconexão automática**: se sua conexão cair por instabilidade de rede ou troca de aba, a partida é preservada por até 2 minutos.

### 2. 🤖 Single Player contra Bot (CPU)

Jogue partidas solo instantâneas contra a inteligência artificial, disponível em 3 níveis de desafio:

- 🟢 **Comerciante Distraído (Fácil):** Joga de forma leve e casual, com jogadas espontâneas.
- 🟡 **Mercador Experiente (Médio):** Equilibrado e calculista.
- 🔴 **Mestre do Souq (Difícil):** Extremamente competitivo e tático.

---

## 📖 Regras e Como Jogar

### Objetivo

A partida é disputada em uma série de **melhor de 3 rodadas**. O primeiro mercador a conquistar **2 Selos de Excelência** vence o jogo. Em cada rodada, o objetivo é acumular o maior valor em **Rúpias** através de fichas de mercadorias, fichas bônus e o bônus de rebanho.

---

### Componentes em Jogo

- **Baralho de 55 Cartas:**
  - 💎 Diamantes (6 cartas) — _Mercadoria Nobre_
  - 🪙 Ouros (6 cartas) — _Mercadoria Nobre_
  - 🥈 Pratas (6 cartas) — _Mercadoria Nobre_
  - 👘 Tecidos (8 cartas) — _Mercadoria Comum_
  - 🌶️ Especiarias (8 cartas) — _Mercadoria Comum_
  - 👜 Couros (10 cartas) — _Mercadoria Comum_
  - 🐪 Camelos (11 cartas no total: 3 iniciam sempre no mercado e 8 no deck)
- **Mercado:** Sempre mantido com 5 cartas visíveis no centro da mesa.
- **Limite de Mão:** Cada jogador pode ter no máximo **7 cartas de mercadoria na mão**. Camelos ficam no seu rebanho e **não** contam para esse limite.

---

### Ações Disponíveis (Escolha UMA por turno)

No seu turno, você deve obrigatoriamente realizar **apenas uma** das seguintes ações:

#### 1. 🖐️ Comprar 1 Mercadoria

- Pegue 1 carta de mercadoria do mercado para a sua mão.
- O mercado é imediatamente reposto com uma nova carta do topo do baralho.
- _Restrição:_ Não é permitido se a sua mão já tiver 7 cartas. Camelos não podem ser pegos individualmente por esta ação.

#### 2. 🐪 Recolher Camelos

- Pegue **todos** os camelos presentes no mercado de uma única vez para o seu rebanho pessoal.
- O mercado é reabastecido do baralho.
- Camelos são essenciais para viabilizar trocas maiores sem consumir as mercadorias da sua mão.

#### 3. 🔄 Trocar Mercadorias (Troca Múltipla)

- Troque 2 ou mais cartas do mercado por igual número de cartas da sua mão e/ou camelos do seu rebanho.
- _Regras de Troca:_
  - Você deve entregar exatamente a mesma quantidade de cartas que retirar.
  - Não é permitido retirar e entregar cartas do mesmo tipo.
  - O tamanho da sua mão após a troca não pode ultrapassar 7 cartas.

#### 4. 💰 Vender Mercadorias

- Escolha cartas de um **único tipo** da sua mão e descarte-as para recolher as fichas de rúpias correspondentes do topo da pilha daquela mercadoria.
- Os valores das fichas diminuem conforme são vendidas (vender primeiro rende mais!).
- _Regra de Luxo:_ Para vender **Diamante, Ouro ou Prata**, você deve vender **no mínimo 2 cartas** daquele tipo juntas.

---

### 🎁 Bônus de Combos

Vender cartas em grandes lotes garante fichas de bônus surpresa (valores ocultos durante a rodada):

- **3 Cartas:** Ganha 1 ficha de bônus de 3 (valores: 1, 2 ou 3 rúpias).
- **4 Cartas:** Ganha 1 ficha de bônus de 4 (valores: 4, 5 ou 6 rúpias).
- **5 Cartas ou mais:** Ganha 1 ficha de bônus de 5 (valores: 8, 9 ou 10 rúpias).

---

### 🐫 O Rebanho de Camelos

Ao final de cada rodada, o mercador que tiver o **maior número de camelos no rebanho** recebe a Ficha de Rebanho, que vale **+5 Rúpias**. Em caso de empate na contagem de camelos, nenhum jogador recebe a ficha.

---

### 🏁 Fim de Rodada e Vitória

A rodada termina imediatamente quando:

1. **3 pilhas de fichas de mercadorias** estiverem completamente esgotadas; **OU**
2. O **baralho de compras se esgotar** e não for possível repor o mercado para 5 cartas.

#### Contagem de Pontos e Desempate:

Soma-se o valor de todas as fichas de mercadorias, fichas bônus e a ficha de camelos. O jogador com mais rúpias recebe 1 **Selo de Excelência**.

Em caso de empate na pontuação:

1. Vence quem tiver mais **fichas de bônus**.
2. Persistindo o empate, vence quem tiver mais **fichas de mercadoria**.

O primeiro jogador a acumular **2 Selos de Excelência** sagra-se o vencedor supremo do Souq!

---

## ✨ Recursos da Plataforma

- 🌓 **Tema Claro e Escuro (Dark Mode):** Alternância instantânea com clique no botão de sol/lua, preservando sua preferência no navegador.
- 📱 **Interface Responsiva:**
  - _Telas Grandes (Desktop/Tablet):_ Grid panorâmico estilo mesa de jogo com visão ampla do mercado, pilhas e oponentes.
  - _Dispositivos Móveis (Smartphones):_ Disposição vertical otimizada com cartas compactas e toque intuitivo.
- 🛡️ **Segurança e Fair Play:** Toda a lógica de regras e validação reside no servidor; cartas da mão do adversário e bônus secretos não são expostos no tráfego de rede até o momento correto.
- 👁️ **Modo "Ver a Mesa":** Ao fim de cada rodada, você pode inspecionar livremente o tabuleiro final antes de avançar para a próxima rodada.
- 📜 **Log de Ações ao Vivo:** Histórico em tempo real de cada compra, venda e troca realizada na mesa.

---

## 🛠️ Tecnologias Utilizadas

### Frontend

- **[React 18](https://react.dev/):** Biblioteca para interfaces dinâmicas em componentes.
- **[Tailwind CSS](https://tailwindcss.com/):** Estilização moderna e utilitária com suporte nativo a dark mode.
- **[Framer Motion](https://www.framer.com/motion/):** Animações suaves de cartas, transições de estado e modais.
- **[Socket.IO Client](https://socket.io/):** Conexão bidirecional em tempo real com o servidor.
- **[React Icons](https://react-icons.github.io/react-icons/):** Conjunto abrangente de ícones para ações e status.

### Backend

- **[Node.js](https://nodejs.org/) & [Express](https://expressjs.com/):** Servidor HTTP e distribuição de arquivos estáticos.
- **[Socket.IO](https://socket.io/):** Gerenciamento de eventos de rede, salas (_rooms_), turnos e reconexões.

### Hospedagem & Deploy

- **[Render](https://render.com/):** Deploy contínuo da aplicação full-stack (Web Service Node.js que atende a API Socket.io e serve o build do React).

---

## 💻 Como Rodar o Projeto Localmente

### Pré-requisitos

- [Node.js](https://nodejs.org/) (versão 16 ou superior)
- `npm` instalado

### Passo a Passo

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/carvalhojonathan/souq.git
   cd souq
   ```

2. **Instale as dependências da raiz, backend e frontend:**

   ```bash
   # Na raiz do projeto:
   npm run build
   ```

   _(Este comando roda a instalação e compilação do frontend e a instalação do backend)._

3. **Inicie o servidor:**

   ```bash
   npm start
   ```

4. **Abra no navegador:**
   - Acesse: `http://localhost:3000`

---

## 📂 Estrutura do Repositório

```text
souq/
├── backend/
│   ├── cpuBot.js          # Inteligência artificial (3 níveis de dificuldade)
│   ├── gameLogic.js        # Motor central das regras do jogo e pontuação
│   ├── server.js           # Servidor Express, gerenciador de salas e eventos Socket.io
│   └── package.json        # Dependências do servidor
├── frontend/
│   ├── public/
│   │   ├── images/         # Ilustrações de cartas, fichas e logos
│   │   └── index.html      # Documento HTML base
│   ├── src/
│   │   ├── components/
│   │   │   ├── ActionLog.js      # Painel de histórico de ações
│   │   │   ├── ActionPanel.js    # Botões e validações das ações do turno
│   │   │   ├── Card.js           # Componente visual e animado das cartas
│   │   │   ├── GameBoard.js      # Tabuleiro principal integrador
│   │   │   ├── GameHeader.js     # Cabeçalho com status, tema e saída
│   │   │   ├── HelpModal.js      # Modal explicativo das regras
│   │   │   ├── MarketArea.js     # Área do mercado e baralho de compras
│   │   │   ├── PlayerArea.js     # Mão e rebanho dos jogadores
│   │   │   ├── RoundEndModal.js  # Resumo detalhado de pontuação por rodada
│   │   │   ├── ScoreBoard.js     # Placar parcial e mini-fichas
│   │   │   └── TokenArea.js      # Exibição de pilhas de fichas de rúpias
│   │   ├── App.js          # Ponto de entrada, lobby e orquestrador de telas
│   │   ├── App.css         # Configurações de grid e layout responsivo
│   │   └── index.js        # Montagem do React
│   └── package.json        # Dependências do cliente
├── .gitignore
├── package.json            # Scripts de automação e orquestração do monorepo
└── README.md               # Documentação completa do projeto
```

---

## 🎨 Créditos e Inspiração

- Jogo original: **Jaipur**, criado por **Sébastien Pauchon** e publicado pela Space Cowboys / Asmodee.
- Implementação e Adaptação Digital: **Souq**.
- Imagens e recursos visuais temáticos adaptados para a atmosfera dos mercados orientais.

---

_Bons negócios no Souq! Que seus camelos sejam velozes e seus diamantes alcancem o melhor preço!_ 🐪✨
