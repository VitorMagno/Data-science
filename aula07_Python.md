# curso de cientista de dados 

## introdução a python

### aula 7, parte 1, funções

* Funções são blocos de códigos criadas pelo desenvolvedor ou previamente definidas
    * exemplo: 
    ```python 
                def imprime ():
                    print ("função 01")

                imprime ()
    ``` 
    ```python 
                def imprime (n):
                    print (n)

                imprime ()
    ```
    ```python 
                def potencia (n):
                    return n * n 

                x = potencia (y)
    ```
    ```python 
                def intervalo (inic = 1, fim = 10) :
                    for inic in range (1, fim +1) :
                        print (inic)

                intervalo (1,10) #as variáveis (inic e fim) assumiriam esses valores
                #ou
                intervalo () #as variáveis assumiriam os valores padrão já estabelecidos
    ```