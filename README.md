# Trabajo Fin de Grado - Ingenieria Informatica - Universidad de Cantabria
Resumen

Debido a las tareas de investigación del grupo de Arquitectura y Tecnología de Computadores de la UC, el simulador de redes de interconexión sobre el que trabajan sufre modificaciones continuas de código, lo que en ocasiones ha provocado tener que invertir un tiempo excesivo en localizar y solventar ciertos errores generados a consecuencia de dichos cambios.

Con el objetivo de solucionar, o al menos minimizar el proceso de detección y localización de estos errores, se ha elaborado un framework de verificación compuesto por un conjunto de pruebas software para comprobar el correcto funcionamiento del simulador después de haber sido modificado. En concreto, utilizando la librería Google Test, se han realizado pruebas unitarias que verifican módulos aislados del simulador y tests de integración para comprobar el comportamiento en conjunto de un grupo de componentes interconectados. También se ha elaborado una prueba de sistema mediante un script en Python que verifica el software completo.

Además, se ha englobado el framework en una estrategia de integración continua con la herramienta Jenkins de modo que las pruebas se ejecuten tras aplicar cambios en el simulador o periódicamente, de manera automática y transparente al programador.

Esta buena práctica supone ventajas al proceso de desarrollo del software, ya que ayudará a los programadores a detectar la localización de los errores tras haber aplicado cambios en el código del simulador.

Abstract

Due to the research tasks of the Arquitectura y Tecnolog´ıa de Computadores group of the UC, the
simulator of interconnection networks on which they work undergoes continuous code modifications,
which has sometimes caused them to spend an excessive time in locating and solving certain errors
generated by the changes.
In order to solve, or at least minimize this process, a verification framework has been developed,
consisting of a set of software tests to verify the correct operation of the simulator after having been
modified. In particular, using the Google Test library, unit tests have been performed to verify isolated
modules of the simulator, integration tests to check the joint behavior of a group of interconnected
components. A system test has also been developed using a Python script that verifies the complete
software behaviour.
In addition, the framework has been embedded in a continuous integration strategy with the Jenkins tool so that the tests are executed after applying changes in the simulator or periodically, in an
automatic and transparent manner for the programmer.
This good practice gives advantages to the software development process, as it will help programmers detect the location of errors after applying changes to the simulator code.
