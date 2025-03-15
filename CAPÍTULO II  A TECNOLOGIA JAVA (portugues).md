CAPÍTULO II

A TECNOLOGIA JAVA

Sumário. A plataforma Java e a linguagem de programação Java. A biblioteca de software padrão do Java. Os pacotes, classes e métodos do Java. Diagrama de uma API do Java da Sun Microsystems (segundo a Suprema Corte dos EUA em sua decisão de 5 de abril de 2021).

A PLATAFORMA JAVA E A LINGUAGEM DE PROGRAMAÇÃO JAVA
Java, por um lado, constitui uma plataforma de software que permite a execução de programas de software escritos na linguagem de programação Java.

Por outro lado, Java é a linguagem de programação por meio da qual um programador escreve código-fonte em linguagem Java.

A plataforma Java possui vários componentes, que são os seguintes:

(i) ferramentas para auxiliar no desenvolvimento de código-fonte escrito na linguagem de programação Java (em inglês, Java Development Kit ou JDK);
(ii) o compilador Java (em inglês, javac compiler), que converte declarações na linguagem de programação Java em declarações de código bytecode do Java;
(iii) o ambiente de execução do Java (em inglês, runtime environment), que consiste em:
(a) a máquina virtual do Java (em inglês, Java Virtual Machine ou JVM), projetada para operar em diferentes tipos de computadores e sistemas operacionais; e
(b) a biblioteca de software padrão do Java ou biblioteca de classes do Java (em inglês, Java Standard Library ou Class Library, também denominada Java Packages ou API Packages nos documentos das partes e nas decisões judiciais); e, por fim,
(iv) a documentação para cada uma das edições da plataforma Java.

O PRINCÍPIO “WRITE ONCE, RUN ANYWHERE” (WORA)
A Sun Microsystems, Inc. desenvolveu a plataforma Java Standard Edition (Java SE) juntamente com outras edições da plataforma Java.

Sua primeira edição foi publicada no ano de 1996.

O objetivo da Sun Microsystems era que Java fosse independente da tecnologia sobre a qual o programa de computador escrito em Java fosse executado, de modo que os programadores não precisassem escrever diferentes versões de programas para diferentes sistemas operacionais ou hardware.

A máquina virtual do Java tem um papel essencial na plataforma Java.

Conforme mencionado anteriormente, a linguagem de programação Java – composta por palavras, símbolos e certas regras sintáticas e semânticas que devem ser seguidas para criar instruções – é a linguagem por meio da qual os programadores escrevem código-fonte, ou seja, a versão de um programa de computador compreensível para seres humanos.

No entanto, para que essas instruções criadas possam ser executadas, elas devem ser convertidas (ou compiladas) em código-objeto, que consiste em 0s e 1s compreensíveis por um computador específico.

No Java, conforme suas regras, o código-fonte é primeiro convertido em bytecode, um estágio intermediário antes de ser convertido em código-objeto pela máquina virtual do Java.

Dessa forma, a plataforma Java, por meio da utilização da máquina virtual do Java, permite que os desenvolvedores escrevam programas capazes de ser executados em diferentes computadores ou hardware sem precisar reescrevê-los para cada tipo específico de computador.

Isso ficou conhecido como “Write Once, Run Anywhere” (WORA).

Em resumo, um programa escrito em Java pode ser executado em qualquer sistema operacional ou hardware, desde que a máquina virtual do Java esteja instalada.

A BIBLIOTECA DE SOFTWARE PADRÃO DO JAVA. OS PACOTES, CLASSES E MÉTODOS DO JAVA
A biblioteca de software padrão do Java contém programas de computador pré-escritos (em inglês, built-in packages), que podem ou não ser utilizados pelos programadores para desenvolver seus próprios programas de computador.

Além disso, a biblioteca de software padrão do Java possui uma estrutura organizacional composta por:

(i) pacotes (em inglês, packages);
(ii) classes (em inglês, classes); e
(iii) métodos (em inglês, methods).

Assim, os pacotes são compostos por classes, e as classes são compostas por métodos.

Em outras palavras, os pacotes agrupam classes, e as classes agrupam métodos.

Esse conjunto organizado de programas de computador pré-escritos (pre-written programs), uma designação comum para programas ou sub-rotinas que compõem bibliotecas de software em geral, foi denominado no processo, individualmente, como interface de programação de aplicativos (API) ou, coletivamente, como pacotes de API do Java.

No entanto, durante o litígio, a definição do termo API não foi precisa, algo reconhecido pelo juiz do Tribunal Distrital.

Uma das partes (Oracle) afirmou que o termo API é um “camaleão”, pois pode significar várias coisas, algumas simples e outras muito complexas.

Independentemente disso, no processo, as partes litigantes, os amicus curiae e os magistrados envolvidos em diferentes instâncias referiram-se a API como:

(i) o conjunto dos 37 pacotes do Java;
(ii) um pacote específico do Java;
(iii) as declarações das APIs do Java, pois as APIs seriam compostas apenas pelas declarações de código (e não pelo código implementado); e
(iv) interfaces de software (segundo a Google e seus amicus curiae).

Para a Google e diversos amicus curiae que apresentaram opiniões favoráveis à empresa no processo, as APIs consistem apenas no código-fonte declarado (em inglês, method headers). Assim, segundo essa visão, seria redundante afirmar API e código declarado ou declarações das APIs do Java, pois ambos seriam equivalentes.

Exemplo de código-fonte declarado e implementado
Esquema 1: Código-fonte declarado e implementado de um método Java
java
Copy
Edit
package java.lang;                     // declaração do pacote java.lang   
public class Math {                     // declaração da classe Math
    public static int max(int x, int y) {  // declaração do método max
        if (x > y) return x;               // implementação, retorna x
        else return y;                      // implementação, retorna y
    }                                      // fecha o método
}                                          // fecha a classe
No código acima, destacam-se:

public: indica que outros programas ou métodos do Java, fora da classe, podem chamar esse método. Se fosse private, ele estaria disponível apenas para métodos dentro da mesma classe.
static: permite chamar o método sem precisar criar uma instância da classe.
int: define que o método retorna um número inteiro.
max: é o nome do método.
(int x, int y): define os argumentos do método, ambos do tipo inteiro.
Esquema 2: Chamada ou invocação do método Java no formato de comando determinado
java
Copy
Edit
int a = java.lang.Math.max(2,3);
Para reutilizar o método max do Java, o programador deve invocá-lo com o formato correto:
java.lang.Math.max(), seguindo a ordem pacote → classe → método.

Esse formato de comando é essencial para chamar o código-fonte declarado do método max, que, por sua vez, invoca o código-fonte implementado do método.

Sem o código-fonte declarado, a chamada ao método max através do formato de comando não produziria a invocação do código-fonte implementado e, portanto, nenhuma ação poderia ser executada.

DIAGRAMA DE UMA API DO JAVA DA SUN MICROSYSTEMS (SEGUNDO A SUPREMA CORTE DOS EUA, EM 5 DE ABRIL DE 2021)

Agora, analisaremos os argumentos apresentados por cada uma das partes, começando pela parte demandante, Oracle America, Inc., seguida da parte demandada, Google LLC.
