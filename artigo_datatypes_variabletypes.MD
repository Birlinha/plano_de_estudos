# O que são variáveis?


Na maioria das linguagens de programação, as variáveis são armazenadas em memória em formato binário, juntamente do código que você construiu. Mas, nós informamos ao computador algo que é legível para nós, como uma palavra - e o computador fica responsável por essa compilação.

Por isso, precisamos informar ao computador qual o formato de nossa variável - também chamado de tipo de dado. Se ela é um texto, um número, uma data, ou outros tipos de dado. Assim ele consegue consultar a "tabuada de tradução" correta, para cada variável.

# Como é a estrutura de um código Java

Quando criamos um arquivo Java por meio de uma IDE, começamos com uma classe de exemplo, e ela parece mais ou menos assim

"""

    package javamundo;
    
    public class exemplo {
      // Seu código vai aqui
    }
    
"""

Agora, vamos ver alguns exemplos de variáveis.

Nós podemos mudar o nome do nosso pacote, criando um novo arquivo.

"""

    package dio.ifood.potenciatech;
    
    public class Aluno { // vou chamar ess classe de 'aluno', como se fosse o site da Dio
        
        // Atributos da classe Aluno
        String nome;
        int idade;
        String linkDoGithub;
        int level;
      }
      
"""

Nós vimos 4 variáveis, e elas armazenam 2 tipos de dados.

Tipos de dados: String - Texto, e Int - Nº Inteiro.
Variáveis: nome, idade, linkDoGithub, level

# Afinal, quais são os tipos de dados e tipos de variáveis?

## Tipos de variáveis:
 - variável global
 - variável estática
 - variável local

## Tipos de dados:
 - Booleana
 - char (caracter)
 - byte
 - short
 - int
 - long
 - float
 - double
 - String
 - Array
 - outros

### Os tipos de dados são separados em 2 categorias principais:

 - Tipo de dados primitivos: como boolean, char, int, short, byte, long, float e double
 - Tipo de dados não primitivos ou tipo de dados de objeto: como String, Array, outros

Para mais detalhes em como utilizar cada tipo de dado, e cada variável, consulte as fontes abaixo! :D

Obrigada pela sua atenção

Fonte:
 - [Tipos de Variáveis em Java, por Javatpoint](https://www.javatpoint.com/pt/vari%C3%A1veis-java#:~:text=Existem%20tr%C3%AAs%20tipos%20de%20vari%C3%A1veis%20em%20java%3A%20local%2C,de%20data%20em%20java%3A%20primitiva%20e%20n%C3%A3o%20primitiva.)
 - [Tipos de dados em Java, por acervolima](https://acervolima.com/tipos-de-dados-em-java/)
 - [Sintaxe Java, por Gleyson Sampaio em potencia tech ifood](https://web.dio.me/course/aprendendo-a-sintaxe-java/learning/f7af647f-d6ef-4663-8a3c-1f63129ee55f?back=/track/potencia-tech-powered-ifood-java-beginners&tab=undefined&moduleId=undefined)
 - [Créditos do banner do artigo](https://pixabay.com/pt/vectors/caf%c3%a9-java-logotipo-programa%c3%a7%c3%a3o-151346/)
