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

## Objectif/motivation


Qué hay que resolver/desarrollar

*Brindar soporte e implementar satisfactoriamente una toolchain para una RISCV 128 bit* para *poder evaluar, medir y comparar los beneficios que puede traer este tipo de arquitectura y esta nueva generacion
en cuanto a la ejecución de codigo con respecto a las contrapartes ya coexistentes en generaciones de 64 bits y 32 bits.

En pocas palabras, qué impacto y qué beneficios trae el advenimiento de la famila de 128 bit con respecto a 64 bits, en mejora de ejecución de software.

We can study 128-bit micro-archi and evaluate its performance via software execution, to measure its efficienty and impact compared with its 64 and 32 bit contraparts.

Therefore we need software to measure performance on 128 bit software, to see the impact it could bring in performance

1

## Plan du rapport

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
6) Conclus


maquinas, computadores, fuerza de computo, desarrollos que 
En este sentido, 





## Cuestiones profundas

¿Por que RISC-V como arquitectura objetivo?

open source y habia un esbozo de como seria una arquitectura de 128 bit 

Que beneficios tenia modificar gcc y no llvm por ejemplo?

El hecho de que era mas facil modificar gcc, habia una documentación clara de como generar una nueva entrada en el back end lo que hacía mas facil desarroollar y obtener lo que teniamos.

QEMU? QUE ES?

gcc et llvm?


#### Desarrollo del informe



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

##