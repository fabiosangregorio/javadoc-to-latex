# javadoc-to-latex
Easily compile and format util.Javadoc entities to LaTeX.

# Usage

## Compilation
1. Move to src 
    ```bash
    cd src
    ```
1. Compile the jflex lexer to Java:
    ```bash
    jflex cup_scanner.flex
    ```
1. Compile the cup parser to Java:
    ```bash
    java -jar ../lib/java-cup-11b.jar parser.cup
    ```
1. Compile the generated Java classes with javac:
    ```bash
    javac -cp ../lib/java-cup-11b-runtime.jar *.java
    ```
1. Run main

# To do
* Gestire liste delle chiavi e dei tag inline
* trim spazi e tab all'inizio
* Implementazione Author (Lorenzo)
* Implementazione del resto
  
* trim spazi e tab all'inizio  

* Warning: keys non ordinate ~ mischiate
* Warning: missing descrizione
  
* Error: version
* Error: testo mancante in inline (es. {@code })
* Error: testo mancante dopo chiavi

* Commentare Javadoc.java e code.java con javadoc

* Problema con VERSION e Key_Version Text? (JDE da problemi perchè dopo version si può andare a capo e scrivere una nuova e ultima riga)


