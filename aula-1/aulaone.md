* 1. O que é essa class?

Em Python, você pode simplesmente escrever:

print("Olá, mundo!")

e executar.

Java possui uma estrutura mais rígida.

Temos:

public class Aula01 {
    
}

Estamos declarando uma classe chamada Aula01.

Uma diferença importante:

public class Aula01

e o arquivo:

Aula01.java

normalmente precisam ter o mesmo nome.

Por exemplo:

Aula01.java

contém:

public class Aula01 {
}

Se você colocar:

public class Programa {
}

dentro de Aula01.java, terá problema de compilação porque uma classe public deve corresponder ao nome do arquivo.

* 2. O famoso main

Esta parte:

public static void main(String[] args) {
    
}

é extremamente importante.

Por enquanto, não precisamos decorar cada palavra.

Podemos pensar assim:

public static void main(String[] args)
              ↓
        ponto inicial
        do programa

Quando executamos uma aplicação Java, o Java procura esse método para começar a execução.

Em Python, seria parecido com:

def main():
    print("Olá")


main()

Embora Java e Python tenham mecanismos diferentes, essa comparação ajuda a entender a ideia.

* 3. System.out.println()

Em Python:

print("Olá")

Em Java:

System.out.println("Olá");

Por exemplo:

public class Aula01 {

    public static void main(String[] args) {

        // Imprime uma frase.
        System.out.println("Estou estudando Java.");

        // Imprime outra frase.
        System.out.println("Meu objetivo é desenvolver APIs.");

        // Podemos imprimir números também.
        System.out.println(10);

    }
}

Resultado:

Estou estudando Java.
Meu objetivo é desenvolver APIs.
10

* 4. O ; do Java

Essa é uma diferença que você perceberá imediatamente vindo do Python.

Em Java:

System.out.println("Olá");
System.out.println("Java");
System.out.println("Python");

Normalmente cada instrução termina com:

;

Em Python:

print("Olá")
print("Python")

não precisamos colocar ;.

Portanto, se você escrever:

System.out.println("Olá")

poderá receber erro de compilação.

O ; é uma das primeiras coisas que você precisará acostumar a colocar.

* 5. Comentários

Como você pediu, vou manter comentários nos códigos.

Em Java temos:

Comentário de uma linha
// Este comentário não será executado.
System.out.println("Olá");
Comentário de várias linhas
/*
    Este é um comentário
    de várias linhas.
*/

System.out.println("Olá");

Você verá bastante isso em projetos reais.

* 6. Strings

Agora vamos começar algo que você já conhece muito bem do Python.

Em Python:

nome = "João"

Em Java, inicialmente:

String nome = "João";

Observe a diferença.

Python:

nome = "João"

Java:

String nome = "João";

Java exige que você informe o tipo da variável.

Isso é uma das diferenças fundamentais entre as linguagens.