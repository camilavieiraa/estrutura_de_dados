## Resumo dos Componentes
Estrutura Base:

  - Utiliza uma lista nativa do Python (fila = []) para armazenar os dados.

## Operações Disponíveis:

  - Enfileirar (enfileirar): Adiciona um novo elemento ao final da lista usando .append().
  - Desenfileirar (desenfileirar): Remove o primeiro elemento do início da lista com .pop(0). Valida se a fila está vazia antes de remover.
  - Consultar (consultar): Exibe o elemento que está na frente da fila (fila[0]) sem removê-lo.
  - Contar (contar): Informa a quantidade atual de elementos com len(fila).
  - Exibir tudo: Imprime o estado completo da lista no momento.

## Interface e Fluxo:
- A função menu() roda em um loop contínuo (while True), apresentando as opções no console e executando a ação correspondente até que o usuário digite a opção de saída (0).
