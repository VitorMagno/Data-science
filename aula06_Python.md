# curso de cientista de dados 

## introdução a python

### aula 6, parte 1, módulos e pacotes

* Módulos  são conjuntos de funcionalidades organizadas em arquivos 
    * ex: 
    ```python 
    import statistics 

    x = statistitcs.mean (z)
    y = statistics.median (z)
    ```
    ```python 
    import statistics as est #posso usar um apelido para chamar a função statistics para ficar mais ágil 
    x = est.mean (z)
    y = est.median (z)
    ```
    * também posso fazer o uso sem a declaração do módulo 
        * ex:
        ```python 
        from statistics import mean, median
        mean ()
        median ()
        
        #ou
        
        from statistics import *
        ```
    * além dos módulos o python tem pacotes, que é um conjunto de módulos 
        * ex:
        ```python 
        import cienciadedados.estatistica, cienciadedados.machinelearning
        ```
        * esses pacotes organizam os módulos usando notação de pontos. 
        * existem várias funções padrão, [aqui](https://docs.python.org/3/library/) está uma lista.
        * Módulos e pacotes adicionais [aqui](https://pypi.org/). Pip é um programa para instalar módulos e pacotes. A instalação do pip é feita pelo prompt de comando utilizando 
            ´´´python 
            python -m ensurepip --default-pip
            ´´´
            * para instalar um pacote :
            ´´´python 
            python -m pip install numpy
            ´´´