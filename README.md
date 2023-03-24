#### (Questão 1) Explique qual a função da Máquina Virtual Java (JVM).

O JVM permite a portabilidade de qualquer código Java, pois códigos em Java são compilados para o formato bytecode que permite que a JVM interprete aquele código em qualquer sistema operacional. 
    
#### (Questão 2) Qual a diferença entre JRE e JDK?

O JRE é o pacote básico para que um usuário possa utilizar qualquer aplicação Java, já o JDK é o conjunto do JRE e de ferramentas utilizadas para o desenvolvimento em Java.

#### (Questão 3) Crie um programa Java que imprima o seguinte texto “Terminei a primeira aula com um programa Java!”.

#### (Questão 4) Compile o programa desenvolvido no exercício anterior. A seguir apague o arquivo .class gerado e tente executar o programa. O que aconteceu?

    Houve um erro e o programa não pode ser executado. 
    "Error: Could not find or load main class MeuPrograma"

#### (Questão 5) Mude o nome do método “main” para “start”, compile e execute. O que aconteceu?

    Houve um erro e o programa não pode ser executado.
    "Error: Main method not found in class MeuPrograma, plead define the main method [...]"

#### (Questão 6) Crie um programa Java para imprimir duas linhas de texto usando duas linhas de código “System.out”, onde aparecerá o seu nome na primeira linha e na segunda linha aparecerá o time para o qual você torce.

#### (Questão 7) Experimente escrever todo o programa anterior em maiúsculo, compile e execute. O que aconteceu?

    Houve um erro e o programa não pode ser compilado.
    "[...] error: class, interface, enum, or record expected [...]"

#### (Questão 8) Experimente salvar o arquivo com um nome diferente do nome da classe, compile e execute. O que aconteceu?

    Houve um erro e o programa não pode ser compilado.
    "[...] error: class Programa is public, should be declared in a file named Programa.java [...]"

