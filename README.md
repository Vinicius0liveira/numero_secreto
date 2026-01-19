# Jogo do Número Secreto

## Descrição
O Jogo do Número Secreto é um jogo simples de adivinhação onde o jogador tenta descobrir um número secreto gerado aleatoriamente entre 1 e 10.

## Como Jogar
1. Abra o arquivo `index.html` em um navegador web.
2. O jogo exibirá uma mensagem inicial pedindo para escolher um número entre 1 e 10.
3. Digite um número no campo de entrada.
4. Clique no botão "Chutar" para fazer sua tentativa.
5. O jogo fornecerá dicas:
   - Se o seu chute for maior que o número secreto, dirá "O número secreto é menor".
   - Se o seu chute for menor, dirá "O número secreto é maior".
6. Continue tentando até acertar.
7. Quando acertar, o jogo mostrará "Acertou!" e o número de tentativas usadas.
8. Clique no botão "Novo jogo" para reiniciar e jogar novamente.

## Funcionalidades
- Geração aleatória de números secretos.
- Contagem de tentativas.
- Dicas para guiar o jogador.
- Texto em português brasileiro.
- Síntese de voz para ler as mensagens (usando ResponsiveVoice).
- Prevenção de repetição de números secretos até que todos sejam usados.

## Arquivos
- `index.html`: Estrutura da página web.
- `app.js`: Lógica do jogo em JavaScript.
- `style.css`: Estilos visuais.
- `img/`: Pasta com imagens usadas no jogo.

## Requisitos
- Navegador web com suporte a JavaScript.
- Conexão à internet para carregar a biblioteca ResponsiveVoice (para síntese de voz).

## Como Executar
Simplesmente abra o arquivo `index.html` em qualquer navegador moderno.
