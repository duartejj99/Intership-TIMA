# Borrador del informe de mi stage -- Español


#### Introduction



## Contexte général du travail


En la evolución y desarrollo tecnológico de los microprocesadores desde la concepción del intel 4004,
se han venido doblando, expandiendo, ramificando y potenciando las aplicaciones que hoy son posibles gracias 
al uso de una herramienta tan importante como lo ha sido la computadora, en este caso deconstruida a un microprocesador.


IDEA: describir como con el paso de cada generación en el arbol genealogico de microprocesadores se  ha ido
empujando los limites de lo posible dentro de lo que permiten las nuevas tecnologías

IDEA2: Hacer un parentesis en como aún esos microprocesadores que no estan a la vanguardia han servido para 
el desarrollo de sistemas embarcados (ASCO)
 
IDEA: Cómo el area de investigación siempre ha llevado a los limites de tecnologías que posteriormente 
quedan en las manos de cualquier individuo en su eventual comercializacion, y en el que se comienza o se renueva 
la proliferación de nuevas ideas, que ahora son posibles gracias al expandir el alcance de lo que es posible 
con el nuevo salto generacional en las tecnologías



Detrás de la motivacion de los investigadores, está una necesidad. Esta no es la excepcion al caso.
A medida que se desarrollan proyectos con creciente complejidad, asi mismo se ha impulsado el 
desarrollo del hardware necesario para superar los limites actuales existentes.

## Contexte restreint

En esta misma dirección es donde hay lugar para la investigación de *la investigacion para una implementacion de una cadena de herramientas XD (toolchain) para una maquina de 128 bits con arquitectura RISC-V* en el seno del laboratorio TIMA con una dirección a cargo del ingeniero en jefe Frederic Petrot que tiene la batuta del proyecto desde *INSERTE AÑO* 
dentro del equipo SLS.

Antes de entrar en los objetivos y motivación del proyecto, seria bueno dejar claro la pertinencia de este proyecto dentro del equipo del laboratorio TIMA y el equipo SLS. En este orden de ideas, 
hace falta dar una pequeña introduccion al laboratorio y al equipo SLS.

SuperLatinSalsa



## Laboratoire TIMA

Ni idea

## TEAM SLS

Ni idea


## Contexto del desarrollo del proyecto


Por que se llevó a cabo este proyecto?
En que contexto tiene lugar?



## Problématique

No hay una  cadena de compilacion existente para emular y medir el rendimiento de software ejecutado en una maquina de 128 bits.
No existe al dia de hoy un punto inicial en el que podamos comenzar a hacernos una idea de las ventajas y posibilidades que podría traer una maquina de estas caracteristicas.

## Objectif/motivation


Qué hay que resolver/desarrollar

*Brindar soporte e implementar satisfactoriamente una toolchain para una RISCV 128 bit* para *poder evaluar, medir y comparar los beneficios que puede traer este tipo de arquitectura y esta nueva generacion
en cuanto a la ejecución de codigo con respecto a las contrapartes ya coexistentes en generaciones de 64 bits y 32 bits.

En pocas palabras, qué impacto y qué beneficios trae el advenimiento de la famila de 128 bit con respecto a 64 bits, en mejora de ejecución de software.

We can study 128-bit micro-archi and evaluate its performance via software execution, to measure its efficienty and impact compared with its 64 and 32 bit contraparts.

Therefore we need software to measure performance on 128 bit software, to see the impact it could bring in performance

1

## Plan du rapport


Esta es una proposicion de via/ruta de acción? (Realmente se me ha hecho dificil comprender esta seccion)

¿Como introduzco la modificacion de una toolchain adaptada para codigo de 128 bits?

1) Introduccion al concepto de toolchain

1.1) gcc (compilador)
1.2) gas (ensamblador)
1.3) linker 
1.3.1) Relocaciones

2) Introduccion a los archivos tipo objeto
2.1) ELF -128

3) QEMU
4) Testing

5) Personal remarks
6) Conclusión
## ----------------------------------------------------------------------------------------------------------------------------------------------------------------
2da Propuesta

¿Cual fue la ruta que Sylvain y yo seguimos para el desarrollo de este proyecto?

A grandes rasgos:

1)Saber en qué nos estabamos metiendo
1.1)Demandar bastante ayuda al profesor con los recursos y conceptos necesarios para entender en qué nos estabamos metiendo exactamente

*comentario para bilan personnel puede ser*
PD: aqui como persona ajena al primer año de ensimag, tuve la oportunidad de familiarizarme con una cantidad abrumadora de cosas de las que antes no tenía conocimiento
No vengo con una formación de primer año de informatica, y esto no lo digo en tono de excusa sino para entender cómo este proyecto me ha permitido
llenar esos "vacíos" de conocimiento que sentia tener con respecto a mis pares de Ensimag. Conocimientos que llegan a ser tomados como garantía
eran ajenos a mi y presentaban a veces una ventaja grande con respecto a alguien que no tiene la facilidad que ellos.



2) Una vez ya familiarizados con los conocimientos ligados al proyecto en el que entrabamos

Comenzamos a descomponer el trabajo en secciones mas pequeñas, manteniendo la vision global de lo que estabamos haciendo.

Es asi como pasamos al siguiente planteamiento *INSERTAR IMAGEN DE LA DIAPOSITIVA- toolchain*

3) Una vez descompuesto los distintos bloques funcionales que debíamos modificar, se pudo hacer la bifurcación del trabajo entre Sylvain y yo.

4)


## Cuestiones profundas

¿Por que RISC-V como arquitectura objetivo?

open source y habia un esbozo de como seria una arquitectura de 128 bit 

Que beneficios tenia modificar gcc y no llvm por ejemplo?

El hecho de que era mas facil modificar gcc, habia una documentación clara de como generar una nueva entrada en el back end lo que hacía mas facil desarroollar y obtener lo que teniamos.

QEMU? QUE ES?

gcc et llvm?


#### Desarrollo del informe

Realmente pasé la mayor parte del trabajo aprendiendo sobre RISC-V para poder entender lo que tenia que modificar y arreglar en los problemas que había en binutils con respecto a la adicion de la extension de 128 bits presente y que fue introducida por Ms Frederic Petrot

*aqui debo hacer una lista de cosas las cuales me tocó trabajar (Ver bitacora de stage- no olvidar recoger los papeles)*


## ENTORNO DE DESARROLLO

## RISC-V 

# RISC-V COMPOSICION

# RISC-V 128 bit Ext

basado en --> 
## QEMU

## ELF 128

## BFD LIBRARY

## GAS (G ASSEMBLER)

## GCC

## TESTS

## Anexos

# Repos
128 test bit
Qemu
Binutils
Gcc
(Y) 