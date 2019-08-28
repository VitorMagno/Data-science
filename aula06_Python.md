# curso de cientista de dados 

## introdução a python

### aula 6, parte 1, _módulos_ e _pacotes_

* _Módulos_  são conjuntos de funcionalidades organizadas em arquivos 
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
    * também posso fazer o uso sem a declaração do _módulo_ 
        * ex:
        ```python 
        from statistics import mean, median
        mean ()
        median ()
        
        #ou
        
        from statistics import *
        ```
    * além dos _módulos_ o python tem _pacotes_, que é um conjunto de _módulos_ 
        * ex:
        ```python 
        import cienciadedados.estatistica, cienciadedados.machinelearning
        ```
        * esses _pacotes_ organizam os _módulos_ usando notação de pontos. 
        * existem várias funções padrão, [aqui](https://docs.python.org/3/library/) está uma lista.
        * _Módulos_ e _pacotes_ adicionais [aqui](https://pypi.org/). Pip é um programa para instalar _módulos_ e _pacotes_. A instalação do pip é feita pelo prompt de comando utilizando 
            ```python 

            python -m ensurepip --default-pip
            
            ```
            * para instalar um pacote :
            ```python 
            
            python -m pip install numpy
            
            ```