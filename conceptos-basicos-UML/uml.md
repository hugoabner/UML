# DIAGRAMAS UML 

<!-- Titulo h1-->
# ¿Qué es el lenguaje de modelado unificado?

*Es un lenguaje estandarizado que consiste en un conjunto integrado de diagramas, que fue desarrollado con la intención de ayudar a los desarrolladores de sistemas y de software, asi como para modelado de negocios y otros sistemas no software. 
Ademas el UML representa una colección de mejores practicas de ingenieria que han demostrado ser exitosas en el modelado de sistemas grandes y complejos   * 

<!-- Titulo h1-->
# EL origen de UML
*
UML es una notación que surgio de OMT 
1. Object Modeling Technique OMT [James Rumbaugh 1991] - aquellas epocas era el mejor para el analisis y sistemas de información con uso intensivo de datos 

2. Booch [Grady Booch 1994] El metodo Booch fue excelente en diseño e implementación, Grady Booch habia trabajado extensamente con el lenguaje Ada
*







![alt text](/images/image.png)


![alt text](/images/uml-concept.png)


# Tipos de Actores en un diagrama de casos de uso UML 

*
La implementación de clasificacion de tipos de actores en un diagrama de casos de uso UML depende del contexto y de tu proposito
Ejemplo: 

1. SI ERES PRINCIPIANTE, bastara considerar 2 tipos de actores, actores primarios y actores secundarios ya que es la sencilla, practica y ampliamente aceptada.
2. SI TRABAJAS EN UN PROYECTO COMPLEJO, puede ser ideal adoptar una clasificación mas detallada y que incluya actores externos y de tiempo

Algunas metodologias extienden la clasificación básica para dar mas precisión al analisis de requisitos 

1. ACTOR EXTERNO, se refiere a cualquier sistema o dispositivo fuera del sistema principal 
2. ACTOR DE TIEMPO, representa un evento que se desencadena en un momento especifico
3. CLASIFICACIÓN POR ACTIVIDAD, hay autores que categorizan a los actores segun si son activos (inician el caso de uso) o pasivos (solo reciben información o asistencia)

Puntos importantes a considerar sobre los actores: 

1. Pueden ser personas, sistemas, o dispositivos, puede ser un usuario humano (un cajero, un administrador), un sistema externo (un servicio de pago) o un harware (un lector de tarjetas) 
2. Actores de tipo tiempo, aunque no son actores en el sentido tradicional, los eventos temporales tambien pueden representarse como actores en un diagrama de casos de uso si son los que inician una acción, ejemplo: Un temporizador que activa un proceso automatico en el sistema
3. Generalización de actores, es importante mostrar la generalización de actores para mostrar una relacion de herencia entre actores, por ejemplo 
un actor Empleado podria generalizar a los actores Cajero y Gerente, que tienen roles mas especificos.
4. Rol vs individuo. Un actor no representa a un individuo especifico (por ejemplo "Juan Perez"), sino un rol que puede ser desempeñado por diferentes individuos o entidades ("Cliente") 

*


# Relaciones en casos de uso

## Relacion << Extend >> 

![alt text](/images/relacion-extend.png)

## Relacion << Include >> 

![alt text](/images/relacion-extend.png)
