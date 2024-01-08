---
Javascript: Escolha um número de 1 a 10
---

# 1. Introdução
O arquivo **app.js** contém a implementação de um simples jogo de
adivinhação em Javascript. O objetivo do jogo é que o jogador adivinhe um número secreto gerado aleatoriamente entre 1 e 10.

# 2. Variáveis GLobais
- **listaDeNumerosSorteados**: Array que armazena os números sorteados para garantir que nenhum número seja repetido.
- **numeroLimite**: Limite superior para o número secreto (no jogo, varia de 1 a 10).
- **numeroSecreto**: Número aleatório a ser adivinhado pelo jogador.
- **tentativas**: Contador de tentativas realizadas pelo jogador.

# 3. Funções Principais

## 3.1 exibirNaTela(tag, texto)
### Parâmetros:
**tag**: Tag HTML onde o texto deve ser exibido.
**texto**: Texto a ser exibido na tela.

### Descrição:
- Atualiza o conteúdo da tag especificada com o texto fornecido.
- Utiliza a biblioteca responsiveVoice para sintetizar o texto em voz.

## 3.2 exibirMensagemInicial()
### Descrição:
- Exibe mensagens iniciais na tela, indicando o início do jogo.

## 3.3 verificarChute()
### Descrição:
- Obtém o valor do chute do jogador a partir de um campo de input.
- Compara o chute com o número secreto e exibe mensagens adequadas.
- Atualiza o número de tentativas.
- Habilita o botão de reinício se o jogador acertar.

## 3.4 gerarNumeroAleatorio()
### Descrição:
- Gera um número aleatório dentro do intervalo de 1 a numeroLimite.
- Garante que o número gerado não seja repetido, reiniciando a lista se todos os números foram usados.

## 3.5 limparCampo()
### Descrição:
-Limpa o campo de input após cada tentativa.

## 3.6 reiniciarJogo()
### Descrição:
- Reinicia o jogo gerando um novo número secreto, limpando o campo e resetando o contador de tentativas.
- Exibe mensagens iniciais na tela.
- Desabilita o botão de reinício.

# 4. Execução Inicial
- Exibe mensagens iniciais na tela.
- Gera o número secreto aleatório.

# 5. Conclusão
Através da criação do arquivo app.js, tive a oportunidade de assimilar conceitos cruciais em JavaScript, proporcionando uma experiência prática e aplicada no desenvolvimento de jogos. Ao explorar variáveis, compreendi como armazenar dados essenciais, como o número secreto e o histórico de sorteios. A utilização de funções permitiu modularizar o código, tornando-o mais organizado e facilitando a execução de tarefas específicas, como exibir mensagens na tela e reiniciar o jogo.

A aplicação prática de **estruturas condicionais** foi reveladora ao verificar a precisão do chute do jogador, determinando se o número secreto era maior ou menor. A adoção de **recursividade** na geração aleatória de números evitou repetições, proporcionando uma abordagem eficaz. A **manipulação do DOM** para interação com elementos HTML revelou-se essencial para criar uma interface dinâmica e interativa. Além disso, a **integração com bibliotecas externas**, como **responsiveVoice**, ampliou as possibilidades, introduzindo a síntese de voz ao projeto. Em suma, esta aplicação não apenas solidificou meu entendimento de JavaScript, mas também me equipou com habilidades práticas para o desenvolvimento de experiências web envolventes.