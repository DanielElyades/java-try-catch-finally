# Estrutura try-catch-finally

### Bloco try
* Contém o código que repreenta a execução normal do trecho de código que pode acarretar em uma excceção.

### Bloco catch
* Contém o código a ser executado caso uma execeção ocorra.
* Deve ser especificado o tipo da exceção a ser tratada(upcasting é permitido)

#### Classe Program
>Neste exemplo é possivel acessar a posição da String que procura.
>Caso contrário ocorrerá uma exceção.

### Pilha de chamada de métodos
#### Classe Program2
>Foi adicionado um método a classe **Program** .
>Marcadores mostram quando iniciam e finalizam os métodos. Ao **method2** foi adicionado **printStrackTrace();** para rastrear a exceção.

### Bloco finally
#### Classe Program3
É um bloco que contém código a ser executado independentemente de ter ocorrido ou não uma execeção.
>**Exemplo:** fechar um arquivo, conexão de banco de dados, ou outro recurso específico ao final do processamento.
