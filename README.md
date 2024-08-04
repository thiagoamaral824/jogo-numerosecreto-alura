# Jogo do Número Secreto

## Introdução

O **Jogo do Número Secreto** é um jogo simples desenvolvido em HTML, CSS e JavaScript, onde o objetivo é adivinhar um número secreto gerado aleatoriamente pelo sistema. O jogo oferece feedback sobre o palpite do usuário, informando se o número secreto é maior ou menor que o chute dado. O usuário tem a opção de reiniciar o jogo após acertar o número.

## Funcionalidades

- **Adivinhar o Número Secreto:** O usuário deve inserir um número entre 1 e 10 e clicar em "Chutar" para tentar adivinhar o número secreto.
- **Feedback Imediato:** O jogo informa se o número secreto é maior ou menor que o palpite do usuário.
- **Contagem de Tentativas:** O número de tentativas é mostrado quando o usuário acerta o número secreto.
- **Reiniciar Jogo:** Após acertar o número, o usuário pode clicar em "Novo jogo" para reiniciar o jogo e tentar novamente.

## Estrutura do Projeto

### Arquivos Principais

- **index.html**: Contém a estrutura HTML da aplicação.
- **style.css**: Contém os estilos CSS para a interface do usuário.
- **app.js**: Contém a lógica JavaScript para o jogo.

### HTML (index.html)

A estrutura HTML inclui:
- Um título e uma mensagem inicial.
- Um campo de entrada para o chute do usuário.
- Botões para chutar e reiniciar o jogo.

### CSS (style.css)

Define os estilos para os elementos da interface, incluindo o layout e o design dos botões e das mensagens.

### JavaScript (app.js)

O arquivo JavaScript contém as seguintes funções:
- **exibirTextoNaTela(tag, texto)**: Atualiza o texto na tela e usa a API de voz para ler o texto.
- **ExibirMensagemInicial()**: Exibe uma mensagem inicial para o usuário.
- **verificarChute()**: Verifica o palpite do usuário e atualiza o estado do jogo.
- **gerarNumeroAleatorio()**: Gera um número aleatório que ainda não foi sorteado.
- **limparCampo()**: Limpa o campo de entrada.
- **reiniciarJogo()**: Reinicia o jogo e gera um novo número secreto.

## Como Usar

1. Abra o arquivo `index.html` em um navegador.
2. Insira um número entre 1 e 10 no campo de entrada e clique em "Chutar".
3. O jogo informará se o número secreto é maior ou menor que o seu palpite.
4. Após adivinhar corretamente, o número de tentativas será exibido e o botão "Novo jogo" será ativado para iniciar um novo jogo.

## Exemplo de Uso

Ao clicar em "Chutar" e adivinhar corretamente o número secreto, a mensagem "Acertou!" será exibida junto com o número de tentativas. Se o número não for correto, o jogo informará se o número secreto é maior ou menor e solicitará outro palpite. Após acertar, você pode clicar em "Novo jogo" para reiniciar o jogo.


