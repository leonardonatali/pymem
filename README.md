## Jogo da memória em python:

- 1 Menu principal do jogo
  - Apresentar as seguintes opções:
  ```bash
    Pressione (1) para iniciar um novo jogo
  ```

- 2 Inicialização do jogo
  
  - 1.1 Criar uma matriz 4x4 com valores aleatórios (ver a biblioteca [randint](https://docs.python.org/3/library/random.html#random.randint));
  - Imprimir a matriz na tela;
  - Apresentar as seguintes opções:
  ```bash
    Pressione (1) para começar a jogar
  ```
  - Limpar **TODA** a tela caso a opção 1 seja informada;

- 3 Jogando o jogo

    - Imprimir a matriz na tela com `*`;
    - Pedir para o usuário informar a linha;
    - Validar se a linha existe na matriz;
    - Pedir para o usuário informar a coluna;
    - Validar se a coluna existe na matriz;
    - Pedir para o usuário informar o valor da célula (`matriz[linha][coluna]`);
    - Validar se o valor informado é o mesmo da célula. Se sim, imprimir uma resposta positiva pro usuário, se não, imprimir alguma mensagem pra tentar novamente;
    - [OPCIONAL] A cada resposta correta do usuário, vc pode guardar em uma variável a linha, coluna e valor acertado, e usar essa variável para mostrar a matriz sem o `*` nesse local, indicando para o usuário que ele já acertou aquela posição, e no fim, quando todos os valores da matriz forem preenchidos, pode mandar uma mensagem dizendo ao usuário que ele finalizou o jogo;
