# 🐍 Snake Game — Jogo da Cobrinha

Um jogo clássico da cobrinha, desenvolvido com tecnologias web nativas, combinando simplicidade, desempenho e uma interface moderna. O projeto funciona diretamente no navegador, sem necessidade de instalação, dependências externas ou servidor.

## 📌 Sobre o projeto

O **Snake Game** é uma aplicação web inspirada no clássico jogo da cobrinha, no qual o jogador controla uma serpente pelo tabuleiro, coleta frutas para aumentar sua pontuação e seu tamanho, evitando colisões com as paredes e com o próprio corpo.

O projeto foi desenvolvido utilizando exclusivamente **HTML5, CSS3 e JavaScript Vanilla**, com toda a aplicação concentrada em um único arquivo HTML.

A proposta é oferecer uma experiência de jogo intuitiva, responsiva e visualmente agradável, tanto em computadores quanto em dispositivos móveis.

## ✨ Funcionalidades

- 🎮 **Jogabilidade clássica:** movimentação da cobrinha em quatro direções.
- 🍎 **Sistema de alimentação:** coleta de frutas para aumentar o tamanho da cobrinha.
- 🏆 **Sistema de pontuação:** ganho de 10 pontos a cada fruta consumida.
- 🥇 **Recorde pessoal:** armazenamento automático da maior pontuação utilizando LocalStorage.
- ⏸️ **Sistema de pausa:** possibilidade de pausar e continuar a partida.
- 🔄 **Reinicialização:** permite iniciar uma nova partida a qualquer momento.
- ⚡ **Dificuldade progressiva:** aumento automático da velocidade conforme a pontuação evolui.
- 💥 **Detecção de colisões:** encerramento da partida ao atingir as paredes ou o próprio corpo.
- 📱 **Controles para dispositivos móveis:** botões direcionais e gestos de deslizar na área do jogo.
- ⌨️ **Controles por teclado:** suporte às setas direcionais e teclas WASD.
- 🎨 **Interface moderna:** tema escuro, elementos visuais com gradientes, animações e efeitos de brilho.
- ♿ **Acessibilidade básica:** utilização de atributos ARIA e suporte à preferência por movimento reduzido do sistema operacional.

## 🛠️ Tecnologias utilizadas

| Tecnologia | Aplicação |
|---|---|
| HTML5 | Estrutura e organização da interface |
| CSS3 | Estilização, layout responsivo, animações e efeitos visuais |
| JavaScript (Vanilla) | Lógica do jogo, movimentação, pontuação e controles |
| HTML5 Canvas | Renderização gráfica do tabuleiro, cobrinha e frutas |
| LocalStorage | Armazenamento local do recorde |
| requestAnimationFrame | Atualização e execução do ciclo de animação |

### Características técnicas

- Aplicação Front-End independente.
- Arquitetura Single File Application (arquivo único).
- JavaScript sem frameworks ou bibliotecas.
- CSS incorporado diretamente no documento HTML.
- Renderização gráfica através do elemento Canvas.
- Layout responsivo com CSS Grid, Flexbox e Media Queries.
- Gerenciamento de estados da partida: `ready`, `running`, `paused` e `over`.
- Atualização do jogo baseada em `requestAnimationFrame` e acumulador de tempo.
- Persistência local de dados através da API LocalStorage.
- Tratamento de erros no acesso ao armazenamento local.

## 🎮 Como jogar

### Controles no computador

| Tecla | Ação |
|---|---|
| ⬆️ Seta para cima / W | Movimentar para cima |
| ⬇️ Seta para baixo / S | Movimentar para baixo |
| ⬅️ Seta para esquerda / A | Movimentar para esquerda |
| ➡️ Seta para direita / D | Movimentar para direita |
| Espaço | Pausar ou continuar |

### Controles em dispositivos móveis

- Utilize os botões direcionais apresentados abaixo do tabuleiro.
- Também é possível deslizar o dedo diretamente sobre a área do jogo para alterar a direção da cobrinha.

### Regras do jogo

1. Inicie a partida pelo botão **Iniciar jogo**.
2. Movimente a cobrinha pelo tabuleiro.
3. Colete as frutas para ganhar 10 pontos e aumentar seu tamanho.
4. Evite atingir as paredes ou qualquer segmento do próprio corpo.
5. A cada 50 pontos, a velocidade aumenta progressivamente.
6. Tente superar seu recorde pessoal!

## 🚀 Como executar o projeto

O projeto não exige instalação de ferramentas, configuração de ambiente ou servidor.

**1. Clone o repositório:**

```bash
git clone https://github.com/SEU-USUARIO/snake-game.git
```

**2. Acesse a pasta do projeto:**

```bash
cd snake-game
```

**3. Execute o jogo:**

Abra o arquivo `index.html` diretamente em qualquer navegador moderno.

Também é possível utilizar a extensão Live Server do Visual Studio Code, caso prefira executar o projeto por um servidor local de desenvolvimento.

## 📁 Estrutura do projeto

```text
snake-game/
│
├── index.html      # Aplicação completa
└── README.md       # Documentação do projeto
```

### Organização interna do arquivo

O arquivo `index.html` está organizado em três partes principais:

- **HTML:** estrutura dos componentes, placar, tabuleiro, botões e controles.
- **CSS:** identidade visual, responsividade, animações e efeitos.
- **JavaScript:** regras do jogo, movimentação, pontuação, colisões, controles e persistência do recorde.

## 📱 Compatibilidade

Desenvolvido para funcionar em navegadores modernos com suporte a HTML5 Canvas, JavaScript ES6+, CSS3 e LocalStorage.

Compatível com:
- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Safari

Também oferece suporte a dispositivos móveis com interação por toque.

## 🔒 Privacidade e armazenamento

O jogo não realiza comunicação com servidores externos, não coleta informações pessoais e não utiliza serviços de terceiros.

O único dado persistido é o recorde de pontuação, armazenado localmente no navegador por meio do LocalStorage, utilizando a chave:

```javascript
snakeHighScore
```

O recorde permanece disponível no mesmo navegador e dispositivo enquanto os dados locais não forem removidos.

## 📄 Licença

Este projeto é disponibilizado para fins de estudo, aprendizado e demonstração de desenvolvimento Front-End.

A licença de distribuição e utilização deverá ser definida pelo responsável pelo repositório.

---

**Desenvolvido com HTML5, CSS3 e JavaScript Vanilla.**

🐍 *Divirta-se, desafie seus limites e supere seu recorde!* 
