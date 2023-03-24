# CC5301  Introducción a la Criptografía Moderna, Otoño 2023
_(Ver log de cambios al final)_

**Propósito:**

Aprender conceptos, técnicas y resultados del fascinante mundo de la Criptografía moderna :-)

**Profesor:** [Alejandro Hevia](http://www.dcc.uchile.cl/~ahevia/)
- Cátedras: Lunes y Miércoles 10:15am-11:30am
- **Horario Consultas profesor (via Discord o en persona): Martes 3:00pm-4:00pm.** 
- Clases auxiliares: Viernes 10:15am-11:45am 
	- Auxiliares: Bryan Ortiz
	- Ayudantes:  Valeria León y Vanessa Gaete
- Sitio web oficial del curso: este y [ucursos](https://www.u-cursos.cl/ingenieria/2023/1/CC5301/1/)
- [Programa del curso](https://www.u-cursos.cl/ingenieria/2023/1/CC5301/1/datos_curso/bajar_programa?id=5225&1227114904)

## Objetivo del curso 

Al finalizar el curso el alumno será capaz de:
* Razonar matemáticamente acerca de la seguridad algoritmos criptográficos tanto del tipo simétrico (clave privada) como del tipo asimétrico (clave pública).
* Modelar y analizar formalmente algoritmos criptográficos basados en cifradores de bloque, funciones de hash, y primitivas basadas en teoría de números, entre otros.
* Diseñar y evaluar soluciones criptográficas para problemas prácticos (confidencialidad, autentificación) presentes en redes de computadores.



## Metodología del Curso

El curso consiste en clases de cátedra más clases auxiliares ambas presenciales. Si la sala tiene la tecnología adecuada, algunas de ellas pudieran grabarse o transmitirse vía stream (vía zoom) pero no hay garantías. El material docente, el cual incluye presentaciones de clases (anotadas), pautas de auxiliares, guías, y libros de material de lectura del curso, será publicado en ucursos. Para consultas al equipo docente y discusión de la materia pueden usar el foro de ucursos, el servidor de discord del curso (ver abajo) o escribirle directamente por correo a lxs auxiliares y ayudantes.

El material para el curso será principalmente cubierto con las presentaciones de clases. 
Adicionalmente, habrá dos libros de referencias del curso:
- Jon Katz y Yehuda Lindell, _Introduction to Modern Cryptography, 
	Second Edition_. 
- Mihir Bellare y Phil Rogaway, _Introduction to Cryptography, Lecture Notes_. Apuntes de un curso en UCSD (el curso se basa fuertemente en el curso del prof. Bellare en UCSD).

(Ver links en referencias abajo). 
Se espera que cada estudiante lea y estudie en forma independiente el o los capítulos correspondientes
  a la materia vista en clases. Ellos serán indicados en el calendario más abajo.

El curso está fuertemente basado en trabajo personal (mal que mal, es un curso electivo ;-) ). Se espera que los estudiantes: 
- asistan a las clases de cátedra y auxiliares (y de ser posible pregunten!),
- lean los capítulos sugeridos de los libros clase a clase,
- interactúen (hagan preguntas) en el foro de estudiantes y chats (discord),
- resuelvan los problemas propuestos (dejados en clase), y
- resuelvan los problemas de las guías de problemas propuestos, y
- quiebren los últimos algoritmos criptográficos estandarizados (no, esto es broma, pero de hacerlo, contactar al profe directamente :-) ).

## Evaluaciones

El curso será completamente evaluado con
- 1 control y 1 examen
- 3 o 4 tareas obligatorias (el número exacto depende del tiempo disponible), y
- 1 proyecto del curso.

Las tareas deben resolverse en forma individualmente aunque se permite colaboración siempre que siga la política
 indicada (ver política de colaboración más abajo).
Para resolver cada tarea tendrán 2-3 semanas, y su solución debe incluir una la solución escrita (un PDF en latex o escrita a mano siempre que tenga letra legible y ordenada).

Se espera que cada estudiante **entienda bien la solución de su tarea y sea capaz de explicarla en persona**. El equipo docente se reserva el derecho a *citar a entrevista personal (vía zoom o presencial)* a algunos estudiantes para que expliquen su solución de la tarea. Cuáles estudiantes serán citados será decidido arbitrariamente por el profesor o incluso escogidos al azar. Note que, el que Ud. sea llamadx _no significa que esté acusado de copia o nada_, simplemente es una manera de confirmar que cada estudiante entiende su solución. Si es llamado a entrevista, la nota final de la solución dependerá tanto de la explicación escrita como de la entrevista.

Habrá un control y un examen al final del curso, ambos presenciales (a menos que la pandemia diga algo distinto). El examen en principio cubrirá toda la materia del semestre pero pudiera evaluar en un porcentaje mayor la materia no cubierta por el control 1. Dado que el control 1 no cubre toda la materia del curso, no habrá eximición en el examen.

Es posible que, a fin de semestre, tengamos una tarea extra opcional para reemplazar la nota de una tarea pero no está garantizado y depende de los tiempos del curso. 

Habrá un proyecto de curso el cual puede ser grupal (hasta 3 personas), y puede ser de dos tipos: implementación o teórico. El primero es una implementación de un sistema que utilice esquemas o herramientas criptográficas. Su nota dependerá de la creatividad y novedad del proyecto, de la contribución comparada con sistemas existentes y de la presentación del proyecto. Se dará una lista de posibles temas pero cada grupo puede escoger su propio tema. Si el proyecto es teórico, debe consistir en presentar un tema, vía leer y explicar al menos 1 artículo de investigación. La nota del proyecto dependerá en este caso de la claridad de la presentación y del análisis/revisión del tema presentado. En ambos casos la presentación será de a lo más 15 min presentación más 5 min de preguntas.

### Calendario Evaluaciones

* **Tarea 1 (T1)**: 

  - Fecha publicación: 5 de Abril 2023
  - Fecha de entrega: 18 de Abril 2023, 23:59hrs.
  - Contenidos: Confidencialidad perfecta, cifradores de bloque, ataques de recuperación de claves.

* **Tarea 2 (T2)**: 

  - Fecha publicación: TBA
  - Fecha de entrega: TBA
  - Contenidos: Encriptación Simétrica, Funciones de Hash y Unidreccionales, MACs.

* **Tarea 3 (T3)**: 
  
  - Fecha publicación: TBA
  - Fecha de entrega: TBA
  - Contenidos: Teoría de Números computacional, Encriptación Asimétrica y RSA.

* **Tarea 4 (T4)**: 
  
  - Fecha publicación: TBA
  - Fecha de entrega: TBA
  - Contenidos: Firmas Digitales, Commitments, protocolos criptográficos, (algoritmos post-quánticos?)

* **Control 1 (C1)**:
  - Fecha: TBA 
  - Contenidos: Lo visto hasta la semana inmediatamente anterior.

* **Presentación Proyecto**:
  - Fecha: 2da semana de exámenes 
  - Formato: Presentación de proyectos en forma presencial o remota 

**Nota de Proyecto :** La nota de la proyecto NP se basará en una rúbrica (a publicar) evaluada por el profesor de cátedra y el profesor auxiliar.

**Cálculo de nota NC:** La nota de control NC, se calculará como el promedio entre C1, NP y el Examen. La nota de tareas NT se calcula como el promedio de las notas T1,T2,T3 (y T4, si es que hay T4).  
  
**Examen y eximición:** Como el control 1 no cubre toda la materia del curso, no habrá eximición.

**Aprobación**: NP debe ser mayor o igual a 4.0., NC debe ser mayor o igual a 4.0. y NT debe ser mayor o igual a 4.0.

### Atrasos en Evaluaciones

Las evaluaciones tendrán una fecha y horario de entrega (típicamente 23:59hrs) pero se aceptarán atrasos de hasta 5 días siguiendo las siguientes reglas:

- Cada estudiante tendrá hasta un máximo de 5 días de atraso que puede usar libremente en las tareas (T1, T2, T3 y T4),
- No puede usar más de 3 días para cualquier tarea individual (para no atrasar las notas),
- Días de fin de semana y semanas de receso no cuentan en los días de atraso, y
- Una vez que el estudiante haya utilizado la totalidad de sus días de atraso, cualquier entrega que haga posterior a la fecha de entrega será calificada con nota 1.0. 

## Politica de Colaboración

Para resolver las actividades evaluativas, pueden colaborar entre dos o más personas siempre que usen la política de _Whiteboard_ (o "pizarrón en blanco"), esto es
- Al juntarse, pueden compartir un pizarrón o editor donde ambxs escriban y discutan cómo resolver el problema, pero **nadie puede grabar ni tomar fotografías**.  
- Al terminar, se "borra" (se cierra), y luego de 30min, cada unx escribe/redacta su solución en forma individual.

Se prohibe buscar soluciones por Internet, o usar las soluciones de otra persona.
(En serio, no use soluciones encontradas en Internet, no sólo por un tema ético sino porque hay muchas equivocadas o que usan ideas o conceptos que vemos distinto en este curso).

Para más detalles o en caso de duda, preguntar a los auxiliares o al profe.

## Donde colaborar y preguntar

Existe un servidor de [Discord](https://discord.gg/F6CqNUTm) para el curso (si el link expiró, preguntar en ucursos). Está disponible para contactar a los auxiliares, ayudantes y el profesor; además puede usarlo para colaborar si lo desea. Si no sabe usarlo, preguntar en el foro.

## Calendario

__(Actualizado 2023-03-17)__

IMPORTANTE: ** Intercambio clase cátedra con la auxiliar **: 
Los siguientes días, las cátedras se moverán de los miércoles a los viernes.
Las salas no sufrirán cambio, esto es, independientemente si hay cátedra o auxiliar, se mantiene la sala asociada a cada horario.

- Miércoles 29 de Marzo: Se hará auxiliar en horario de cátedra.
- Viernes 31 de Marzo: Se hará cátedra en horario de auxiliar.
- Miércoles 26 de Abril: Se hará auxiliar en horario de cátedra.
- Viernes 28 de Abril: Se hará cátedra en horario de auxiliar.
- Miércoles 31 de Mayo: Se hará auxiliar en horario de cátedra.
- Viernes 2 de Junio: Se hará cátedra en horario de auxiliar.
- Miércoles 28 de Junio: Se hará auxiliar en horario de cátedra.
- Viernes 30 de Junio: Se hará cátedra en horario de auxiliar.

Semana | Clase  | Tema                 | Contenidos        | Lecturas                       | Comentarios    
:----  | :----: | :--------------:     | :--------------   | :--------------                |  :---------
1      | 1      | Introducción         | Motivación        |  KL cap 1.1, 1.2, BR. Cap. 1 |  
1      | 2      | Cifradores clásicos  | Cifradores históricos, ataques | KL cap 1.3, , BR Cap. 2|   
2      | 3      | Confidencialidad Perfecta  | Definición, One-Time Pad, Resultados   | KL Cap. 2,  , PT. Cap. 5 y mini-guía|  
2      | 4    |                      | Limitaciones | KL, Teo. 2.10 y Cap. 2.4 |
3      | 5      | Encriptación Simétrica | Cifradores de Bloque          | KL Cap. 6.2, BR Cap 3.1-3.3 | 
3      | 6      | Encriptación Simétrica | DES, AES, Key Recovery Attacks| BR Cap 3, KL Cap. 6.2.3-6.2.5, Opcional 6.2.6; V Cap. 2.1 y 2.7, Smart Cap. 13.2,13.3  | 
4      | 7      | Funciones Pseudo-Aleatorias |  Definición, Ejemplos, Significado | BR Cap 4.1-4.3 | 
<!-- 
4      | 8      | Funciones Pseudo-Aleatorias |   |  |
11     | 19     | Criptografía Asimétrica | Encriptación Asimétrica (o de clave pública), conceptos, DHIES, Seguridad (IND-CPA), Introducción a RSA |  | 
11     | 20     |                      | Continuación RSA, Seguridad RSA, Variantes (SRSA) |  | 
-->

## Bibliografia
- **[KL]** J. Katz, Y. Lindell, **[Introduction to Modern Cryptography](http://www.cs.umd.edu/~jkatz/imc.html)**, 
	Second Edition, Chapman & Hall/CRC Press, 2007. 
	(En biblioteca y ucursos.). Ver la [errata](http://www.cs.umd.edu/~jkatz/imc/errata.pdf) y la sec. 4.6.3 [revisada](http://www.cs.umd.edu/~jkatz/imc/hash-erratum.pdf). 
- **[BR]** M. Bellare, P. Rogaway, **Introduction to Cryptography, Lecture Notes**, University of California San Diego, 2005.  
  	(En ucursos, disponible transparencias de versiones del curso para pregrado, y de postgrado). 
- **[SB]** V. Shoup and D. Boneh, **A Graduate Course in Cryptography**, 2017. [Disponible online gratis](https://toc.cryptobook.us/).
- **[Smart]**, N. Smart, **Cryptography, An Introduction**, 2013. [Disponible online gratis](https://homes.esat.kuleuven.be/~nsmart/Crypto_Book/).
- **[Shoup]**, V. Shoup, **A Computational Introduction to Number Theory and Algebra**, 2008. [Disponible online gratis](https://shoup.net/ntb/).
- **[Katz]**, J. Katz, **Digital Signatures**, Springer, 2010, disponible desde la red de la FCFM o usando la VPN del CEC (googlear título y springerlink).
- **[Stinson]**, D. Stinson, **Cryptography, Theory and Practice**, Second edition, Editorial Cgapman and Hall/CRC, 2002. En biblioteca hay copias físicas :-(.
- **[MvOV]**, A. J. Menezes, P.C. van Oorschot, S. A. Vanstone, **Handbook of Applied Cryptography**, CRC press, 1997. [Disponible online](http://cacr.uwaterloo.ca/hac/).
- **[PT]**, R. Pass, W. Tseng, **A Course in Discrete Structures**, lecture notes. 2011. [Disponible online](http://www.cs.cornell.edu/~rafael/discmath.pdf).
- **[V]**, S. Vadenaux, **A Classical Introduction to Cryptography, Applications for Communication Security**, (En biblioteca y ucursos.)

## Log de Cambios

- 2023-03-17: Reglas del curso publicadas
