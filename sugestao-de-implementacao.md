# Sugestão de implementação

```
/**
 * Funções de inicialização
 */

função inicializarGame() {
  /* aqui você define todos as funções e eventos do game no momento da inicialização */
  desenharGame()
  configurarEventos()
}


função configurarEventos() {
  /* aqui você configura os eventos de usuário */
}


/**
 * Funções de desenho
 */

função desenharGame() {
  desenharCanvas();
  desenharParedes();
  desenharCobra();
  desenharComida();
}

função desenharCanvas() {
  /* aqui você desenha o quadro do jogo */
}

função desenharParedes() {
  /* aqui você desenha as paredes */
}

função desenharCobra() {
  /* aqui você desenha a cobra */
}

função desenharComida() {
  /* aqui você desenha a comida */
}


/**
 * Funções de interação
 */
função moverCobra() {
  /* aqui você move a cobra */
}

função atualizarPosicaoDaCobra() {
  /* aqui você desenha a posição da cobra */
}

função mudarDirecao() {
  /* aqui você implementa a mudança de direção */
}

função comerComida() {
  /* aqui você desenha a posição da cobra */
}

função gerarComida() {
  /* aqui você implementa a geração de uma nova comida */
}


/**
 * Funções auxiliares
 */

função estaColidindoComParede() {
  /* aqui você checa se a cobra está colidindo com a parede */
}

função estaColidindoComCobra() {
  /* aqui você checa se a cobra está colidindo com a cobra */
}

função estaColidindoComComida() {
  /* aqui você checa se a cobra está colidindo com a comida */
}

função gerarPosicaoAleatoriaDentroDoCanva() {
  /* aqui você checa gera uma posição aleatória */
}


/**
 * Main
 */
função principal() {
  inicializarGame();
}

principal(); // executa a função principal, responsavel por inicializar o jogo
```
