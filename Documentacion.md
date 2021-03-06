# 0. Introduccion al curso
## Capitulo 1: Elementos de entorno de algoritmos y programacion
Aprenderas los conceptos fundamentales de los elementos basicos del proceso de informacion en una computadora.
* Hardware
* Software
* Dato
* Informacion
* Algoritmo
* Programa
* Tipos de algoritmos
* Lenguaje de programacion 

## Capitulo 2: Entidades primitivas
Conocer los recursos principales y necesarios para la formulacion de una solucion.
* Tipos de datos
* Expresiones
* Operandos y Operadores
* Identificadores
* Constantes y variables
* Contadores
* Acumuladores
* Operacion de asignacion
* Entrada y salida de informacion

## Capitulo 3: Herramientas de programacion para formulacion de algoritmos
Descubre las tecnicas y metodologias para empezar a formular soluciones a traves de los algoritmos
* Diagrama de flujo
* Diagrama estructurado N-S (Nassi-Schneiderman)
* Pseudocodigo

## Capitulo 4: Estructuras algoritmicas
Comprendera las tecnicas de organizacion a traves de mecanismos capaces de agrupar las rutinas, que generan soluciones, mediante valores limites y condicionales en una variable.
* Estructuras secuenciales.
* Estructuras condicionales.
* Estructuras repetitivas.

## Capitulo 5: Arreglos
Concentra el almacenamiento estatico de los datos, interpretados como informacion
* Definicion
* Arreglos unidimensionales
* Arreglos biidimensionales
* Arreglos multidimensionales

## Capitulo 6: Modularidad - Procedimientos y funciones
Aprenderas a descomponer la solucion de un problema, encontrando mecanismos independientes, capaces de llevar valores de variables de manera local y global
* Funciones (realiza determinada accion y retorna un valor)
* Procedimientos (realiza determinada accion pero no retorna un valor)
* Recursividad

## Capitulo 7: Cadenas de caracteres
Enfocara casos especiales vinculados al tratamiento de la informacion generada por el conjunto de caracteres.
* Cadena de caracteres
* Operaciones con cadenas

## Capitulo 8: Archivos
Conocera la estructura interna de la generacion de un almacenamiento interno y externo de la informacion.
* Nocion de archivo
* Campos
* Registros
* Operaciones sobre archivos
* Archivos de texto

## Capitulo 9: Ordenacion y busqueda
Descubrira los diversos metodos para interpetar mediante rutinas de estructuras de codigos, formas de ordenar y buscar un dato dentro de un bloque de informacion.
* Ordenacion:
    * Metodo burbuja
    * Metodo de insercion
    * Metodo de seleccion
    * Metodo de Quick Short
* Busqueda:
    * Busqueda secuencial
    * Busqueda binaria

# 1. Informacion y procesamiento de la informacion
## Capitulo 1: Elementos de entorno de algoritmos y programacion
1. Informacion y procesamiento de la informacion
2. Algoritmo y programa
3. Lenguaje de programacion
4. Metodologias para la solucion de problemas por medio de computadora.
## Informacion y procesamiento de la informacion
Antes de comenzar veamos unos peque??os conceptos ...

* Una computadora es un procesador de datos y sistemas de procesamiento de la informacion.
* Un sistema es un conjunto de componentes conectados interactivos, que tienen un proposito y una unidad total.
* Sistema de procesamiento de informacion, es un sistema que transforma los datos brutos en informacion organizada, significativa y util. 

Para procesar la informacion necesitamos hardware y software

**Hardaware (parte fisica - tangible):** Es el conjunto de componentes fisicos de una computadora. El hardware de una computadora se compone de:  
- Unidad Central de Procesos (CPU): Conjunto de circuitos electronicos capaces de ejecutar calculos como operaciones logicas y matematicas.
- Memoria Central: La informacion procesada por CPU se almacena normalmente en la memoria central hasta que se terminan los calculos.
- Dispositivos de Almacenamiento secundario (Memoria auxiliar).
- Perisfericos o Dispositivos de Entrada/Salida (E/S).

**Software (parte l??gica - intangible):**
Es el conjunto de programas que controlan el funcionamiento del hardware de una computadora

**Dato:** 
- El dato es una representacion simbolica (numerica, alfabetica, algoritmica, etc.), un atributo o caracteristica de una entidad. Los datos describen hechos empiricos, sucesos y entidades reales. Un dato puede ser un simple caracter, tal como 'a', un numero, o un dibujo, etc.
- Un dato es la expresion general que describe los objetos con los cuales opera una computadora. Existen dos tipos de datos:

    - Simples (sin estructura):
        - Numericos (enteros, reales)
        - Logicos (Boolean)
        - Caracter (char, string)
    - Compuestos (estructurados):
        - Registros
        - Arreglos (Vectores, Matrices)
        - Archivos

**Informacion:**
- La informacion es un conjunto de datos acerca de algun suceso, hecho, fenomeno o situacion, que organizados en un contexto determinado tienen su significado, cuyo proposito puede ser el de reducir la incertidumbre o incrementar el conocimiento acerca de algo.

**Procesamiento de la informacion:**
- La informacion se puede introducir en la computadora como entrada(input) y a continuacion se procesan para producir una salida (output).

![mark down image](img/i1.png "Procesamiento de la informacion")


# 2. Algoritmo y Programa
Un algoritmo es un metodo para resolver un problema, es una secuencia ordenada de instrucciones que siempre se ejecutan en un tiempo finito, que describen el proceso que se debe seguir, para dar solucion a un problema.

En un algoritmo siempre debe haber un punto de inicio y un punto de terminacion, estos deben ser unicos y deben ser facilmente identificables.

## Caracteristicas de un algoritmo
Todo algoritmo debe cumplir con las siguientes caracteristicas:
- Tiene que ser preciso.
- Tiene que estar bien definido.
- Tiene que ser finito.
- Un algoritmo debe describir: Entrada, Proceso y Salida.

Por ejemplo: El algoritmo para llamar a un contacto personal, por mi celular.
- Entrada: marcar el numero celular de este contacto.
- Proceso: Enlace intercelular.
- Salida: Contacto establecido - Llamda aceptada o rechazada.

Ejemplo: Un alumno postula a Ingenieria Informatica. La oficina de control del proceso de Admision de la Universidad verifica el puntaje obtenido por el alumno, en el examen de admision, si el alumno alcanzo el puntaje indicado en este proceso de admision, entonces puede ser aceptado en dicha carrera profesional, en caso contrario tiene que volver a postular. Generar el algoritmo correspondiente:

Solucion:

1. Inicio.
2. Leer el puntaje obtenido.
3. Verificar el puntaje obtenido.
4. Si el puntaje es el propuesto en el proceso de admision aceptar al alumno, caso contrario el alumno tiene que volver a postular.
5. Fin.

## Tipos de algoritmos
### Algoritmos cualitativos: 
- Son aquellos en los que se describen los pasos utilizando palabras. Por ejemplo: Usar una guia telefonica, buscar una palabra en un diccionario,etc.

Ejemplo: Cual es el algoritmo para buscar informacion en Google.
1. Inicio.
2. Entrar en la pagina web de Google.
3. En el cuadro de entrada de datos, colocar el nombre del tema.
4. Hacer un clic en "Buscar" o presionar "Enter".
5. Se obtiene como resultado enlaces del tema buscado.
6. Seleccionar el enlace conveniente.
7. Fin

## Algoritmos cuantitativos
- Son aquellos en los que se utilizan calculos numericos para definir los pasos del proceso. Por ejmplo: resolver una ecuacion, sacar el area de un triangulo.

Ejemplo: Realizar un algoritmo que calcule la altura de un edificio.
1. Inicio.
2. Leer la cantidad de pisos "n".
3. Leer la altura de cada piso "h".
4. Multiplicar la cantidad de pisos por la altura de cada piso: H=n*h.
5. Imprimir H.
6. Fin

## Lenguajes Algoritmicos:
Es una serie de simbolos y reglas que se utilizan para describir de manera explicita un algoritmos.

## Tipos de lenguajes algoritmicos
- Graficos: Es la representacion grafica de las operaciones que realiza un algoritmo. Por ejemplo: diagramas de flujo, diagramas N-S.
- No Graficos: Representa en forma descritiva las operaciones que debe realizar un algoritmo. Por ejemplo: Pseudocodigo.

Ejemplo: Realizar un algoritmo para determinar si un numero es positivo o negativo


![mark down image](img/i2.png "Procesamiento de la informacion")

## Programa:
- Es el conjunto de instrucciones escritas en algun lenguaje de programacion y que ejecutadas secuencialmente resuelven un problema especifico.

# 3. Lenguaje de programacion
## ??Que es un lenguaje de programacion?
- Es un conjunto de simbolos y reglas sintacticas y semanticas que definen su estructura y el significado de sus elementos y expresiones, y es utilizado para controlar el comportamiento fisico y logico de una maquina.
- Los lenguajes de programacion tienen un conjunto de instrucciones que nos permiten realizar operaciones de entrada/salida, calculos, manipulacion de textos, logica/comparacion y almacenamiento/recuperacion.

## Tipos de lenguajes de programacion:
Los lenguajes de programacion se pueden clasificar atendiendo a varios criterios, los principales son:
- Segun el nivel de abstraccion.
- Segun la forma de ejecucion.
- Segun el paradigma de programacion.

### Segun el nivel de abstraccion:
1. Lenguaje maquina: Las instrucciones en el lenguaje maquina se expresan en terminos de la unidad de memoria mas peque??a: el bit (digito binario 0 o 1).
    - Ventaja: No necesita ser traucido, tiene una mayor adaptacion al equipo.
    - Inconveniente: La dificultad y lentitud en la codificacion.
2. Lenguaje de bajo nivel (ensamblador): Se utilizan palabras mnemotecnicas (abreviaturas). Por ejemplo, mnemotecnicos tipicos de operaciones aritmeticas son: ADD(sumar), SUB(restar), DIV(dividir), etc.

    - Ejemplo: ADD A,B C
- Ventaja: No es tan dificil como el lenguaje maquina.
- Incoveniente: Cada maquina tiene su propio lenguaje, necesitamos un proceso de traduccion.
3. Lenguaje de alto nivel: Son aquellos en los que las instrucciones o sentencias son escritas con palabras similares a los lenguajes humanos, lo que facilita la escritura y comprension del programa.
    - Ventaja: Son independientes de cada maquina, lo que los hace portable.
    - Inconveniente: El proceso de traduccion es muy largo y ocupa mas recursos.

# 4. Lenguaje de programacion (parte 2)
### Segun la forma de ejecucion
1. Lenguajes compilados:
    - Se compilan una vez y se utilizan cuantas veces se desee sin necesidad de volver a utilizar el compilador.
    - Los compiladores analizan todo el programa y no generan resultados si no es correcto todo el codigo.
2. Lenguajes interpretados: 
    - Son interpretados cada vez que se ejecutan y necesitan siempre del interprete.
    - Los interpretes analizan las instrucciones segun las necesitan y pueden iniciar la ejecucion de un programa con errores.

### Segun el paradigma de la programacion
Un paradigma de programacion representa un enfoque particular o filosofia para la construccion de un software

1.  Algoritmo, Imperativo o por procedimientos
    - El mas comun y esta representado,por ejemplo, por lenguajes de programacion como C o BASIC.
    - Describe la programacion en terminos del estado del programa y sentencias que cambian dicho estado. Los programas imperativos son un conjunto de instrucciones que le indican al computador como realizar una tarea.
2. Declarativo o predicativo
    - Basado en la utilizacion de predicados logicos o funciones matematicas, su objetivo es conseguir lenguajes expresivos en los que no sea necesario especificar como resolver el problema (programacion convencional imperativo).
3. Logico
    - Un ejemplo es PROLOG. El mecanismo de inferencia generico se basa en los procedimientos de deduccion de formulas validas en un sistema axiomatico.
4. Funcional
    - Representado por la familia de lenguajes LISP. El mecanismo de inferencia generico se basa en la reproduccion de una expresion funcional a otra equivalente simplificada.
5. Orientada a objetos
    - Cada vez mas utilizado, sobre todo en combinacion con el imperativo. De hecho los lenguajes orientados a objetos permiten la programacion imperativa. Algunos ejemplos de lenguajes orientados a objetos son C++,Delphi,Java,Python,etc. Usa objetos y sus interacciones para dise??ar aplicaciones y programas de computadora. Esta basado en varias tecnicas, incluyendo herencia, modularidad, polimorfismo y encapsulamiento.

# 5. Metodologias para la solucion de problemas
Desde el punto de vista educativo, la solucion de problemas mendiante la programacion posibilita la activacion de una amplia variedad de estilos de aprendizaje. Pueden encontrar diversas maneras de abordar problemas y plantear soluciones.

Es por ello que, debemos considerar cuatro fases, en esencia, para resolver problemas especificos mediante la programacion de computadores.
1. Analizar el problema.
2. Dise??ar un algoritmos.
3. Traducir el algoritmo a un lenguaje de programacion.
4. Depurar el programa.

## Definicion del problema:
Esta fase esta dada por el enunciado del problema, el cual requiere una definicion clara y precisa. Es importante que se conozca lo que se desea que realice la computadora; mientras esto no se conozca del todo no tiene mucho caso continuar con la siguiente etapa.
 ## Analisis del problema:
Una vez que se ha comprendido lo que se desea de la computadora, es necesario definir
- Los datos de entrada.
- Cual es la informacion que se desea producir (salida).
- Los metodos y formulas que se necesitan para procesar los datos.
## Dise??o del algoritmo
Las caracteristicas de un buen algoritmo son:
- Debe tener un punto particular de inicio.
- Debe ser preciso e indicar el orden de realizacion de cada paso.
- Debe ser definido, no debe permitir dobles interpretaciones.
- Debe ser general.
- Debe ser finito en tama??o y tiempo de ejecucion
## Codificacion
La codificacion es la operacion de escribir la solucion del programa (de acuerdo a la logica del diagrama de flujo o pseudocodigo), en una serie de instrucciones detalladas, en un codigo reconocible por la computadora, la serie de instrucciones detalladas se le conoce como codigo fuente, el cual se escribe en un lenguaje de programacion.
## Prueba y depuracion 
Los errores humanos dentro de la programacion de computadoras son muchos y aumentan considerablemente con la complejidad del problema. El proceso de identificar y eliminar errores, para dar paso a una solucion sin errores se le llama depuracion.

La depuracion o prueba resulta una tarea tan creativa como el mismo desarrollo de la solucion, por ello se debe considerar con el mismo interes y entusiasmo.
## Documentacion
Es la guia o cumunicacion escrita en sus variadas formas, ya sea en enunciados, procedimientos, dibujos o diagramas.

A menudo un programa escrito por una persona, es usado por otra. Por ello la documentacion sirve para ayudar a comprender o usar un programa o para facilitar futuras modificaciones (mantenimiento).

La documentacion se divide en tres partes:
- Documentacion interna: Es aquella que se crea en el mismo codigo, puede ser en forma de comentarios o de archivos de informacion dentro de la aplicacion.
- Documentacion externa: Es aquella que se escribe en cuadernos o libros, totalmente ajena a la aplicacion en si.
- Manual de usuario: Documento de comunicacion tecnica que busca brindar asistencia a los sujetos que usan un sistema.

## Mantenimiento
Se lleva a cabo despues de determinado el programa, cuando se detecta que es necesario hacer algun cambio, ajuste o complementacion al programa para que siga trabajando de manera correcta. Para poder realizar este trabajo se requiere que el programa este correctamente documentado.

# 6. Descargar e instalar PSeInt
## Entidades primitivas
1. Descargar PSeInt
2. Identificadores (Constantes y Variables)
3. Tipos de datos
4. Operacion de asignacion
5. Operadores y Operandos
6. Funciones internas
7. Entrada y salida de informacion
8. Ejercicios

## ??Que es PSeInt?
PSeInt es una herramienta para asistir a un estudiante en sus primeros pasos en programacion. Mediante un simple e intuitivo pseudolenguaje en espa??ol (complementado con un editor de diagramas de flujo), le permite centrar su atencion en los conceptos fundamentales de la algoritmia computacional, minimizando las dificultades propias de un lenguaje y proporcionando un entorno de trabajo con numerosas ayudas y recursos didacticos.
# 7. Identificadores (Constantes y Variables)
## Identificadores:
Los identificadores representan los datos de un programa (constantes o variables). Un identificador es una secuencia de caracteres que sirve para identificar una posicion en la memoria de la computadora, que nos permite accesar a su contenido

![mark down image](img/i3.png "Identificadores")

## Reglas para formar un Identificador
- Debe comenzar con una letra (A - Z, mayusculas o minusculas) y no deben contener espacios en blanco.
- Letras, digitos y caracteres, pueden estar unidos por un caracter subrayado como "_".
- El primer caracter no puede ser un numero.

![mark down image](img/i4.png "Ejemplo de identificadores")

## Tipos de Identificadores
### Constantes:
Una constante es un dato numerico o alfanumerico que no cambia durante la ejecucion del programa.

Ejemplo:    PI = 3,1416

### Variables:
Es un espacio en la memoria de la computadora que permite almacenar temporalmente un dato durante la ejecucion de un proceso, su contenido puede cambiar durante la ejecucion del programa.

Ejemplo:  area = (base*altura)/2

### Clasificacion de las variables
1. Por su contenido
    - Numericas.
    - Logicas.
    - Alfanumericas (String)
2. Por su uso
    - De trabajo
    - Contadores
    - Acumuladores

# 8. Tipos de datos
Los tipos de datos hacen referencia al tipo de informacion que se trabaja, todos los datos tienen un tipo asociado con ellos. El tipo de dato determina la naturaleza del conjunto de valores que puede tomar una variable.

Ejemplo:

entero numero1 =10;

real numero2=19.56;

caracter letra='a';

logico misterio=verdadero;

![mark down image](img/i5.png "Tipos de datos")

![mark down image](img/i6.PNG "Tipos de datos")

# 9. Operacion de asignacion
Consiste en atribuir un valor a una variable:

    Nombre de la variable <- expresion

En algunos lenguajes de programacion, el simbolo puede variar a: "=",":="

![mark down image](img/i7.PNG "Operacion de asignacion")

El proceso de asignacion se realiza en 2 fases:
- Se evalua la expresion de la parte derecha de la asignacion obteniendose un unico valor.
- Se asigna ese valor a la variable de la parte izquierda, sustituyendose el valor que tenia anteriormente.

        num=10;

??Que es lo que hay que tener en cuenta?
- En la parte izquierda solo puede haber una variable.
- La variable a la que se le asigna el valor pierde su valor anterior.
- El tipo de dato del valor que se obtiene al evaluar la parte derecha tiene que ser el mismo que el tipo de dato de la variable de la parte izquierda, es decir a una variable solo se le pueden dar valores de su mismo tipo de dato.

![mark down image](img/i8.PNG "Operacion de asignacion")