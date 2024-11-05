# Paradigma de Programación Paralela

Este repositorio contiene las notas y ejemplos de código para apoyar la clase sobre el Paradigma de Programación Paralela. A continuación, se incluye teoría detallada, ventajas y desventajas, componentes clave, tipos de paralelismo, desafíos y ejemplos prácticos en código.

## Índice
- [Introducción](#introducción)
- [Teoría](#teoría)
  - [Concepto](#concepto)
  - [Importancia](#importancia)
  - [Ventajas y Desventajas](#ventajas-y-desventajas)
  - [Componentes Clave](#componentes-clave)
  - [Tipos de Paralelismo](#tipos-de-paralelismo)
  - [Desafíos](#desafíos)

---

## Introducción

La programación paralela permite dividir un problema grande en múltiples tareas más pequeñas que pueden ejecutarse simultáneamente, optimizando el tiempo de procesamiento. A diferencia de la programación secuencial, que ejecuta las tareas una tras otra, la programación paralela utiliza múltiples recursos (procesadores o núcleos) para resolver problemas de manera concurrente.

Este paradigma es fundamental en áreas de procesamiento intensivo, como la simulación científica, el aprendizaje automático y el análisis de grandes volúmenes de datos.

---

## Teoría

### Concepto

La programación paralela es una técnica que divide un problema complejo en múltiples subproblemas que se pueden resolver simultáneamente, acelerando así el proceso de cálculo. Su premisa principal, "divide y vencerás", permite que múltiples procesadores o núcleos trabajen coordinadamente en diferentes partes de un problema.

La computación paralela se opone a la computación secuencial, donde las operaciones ocurren una tras otra. Esto la hace especialmente relevante en aplicaciones científicas y de gráficos computacionales.

### Importancia

El paralelismo ha cambiado la forma de abordar problemas computacionales, abriendo posibilidades en campos como la inteligencia artificial, la ingeniería y la bioinformática. Ha impulsado el desarrollo de hardware especializado (como GPUs) y software para manejar tareas en paralelo, lo cual permite abordar problemas de gran escala que antes eran inabordables.

### Ventajas y Desventajas

**Ventajas**
- **Mayor velocidad de procesamiento**: Optimiza el tiempo de ejecución al dividir tareas entre múltiples recursos.
- **Escalabilidad y eficiencia**: Permite ejecutar problemas de gran magnitud en menos tiempo.
- **Optimización de recursos**: Mejora el rendimiento en aplicaciones que manejan grandes volúmenes de datos.

**Desventajas**
- **Consumo energético elevado**: Los sistemas paralelos suelen consumir más energía.
- **Complejidad de programación**: La sincronización y coordinación entre tareas puede ser difícil de lograr.
- **Posibles fallos**: A mayor número de componentes, mayor posibilidad de fallos.

### Componentes Clave

- **Tareas**: Partes en que se divide un problema para resolverlo más rápido. Dependiendo de su complejidad, pueden clasificarse en granularidad gruesa o fina.
- **Scheduling**: Proceso de asignar tareas a hilos o procesos, considerando dependencias y prioridades.
- **Hilos**: Unidades de ejecución que permiten que varias tareas se realicen al mismo tiempo.
- **Mapeo**: Asignación de hilos a núcleos de procesamiento.

### Tipos de Paralelismo

- **Paralelismo a nivel de bit**: Aumenta el tamaño de palabra del procesador para reducir la cantidad de instrucciones necesarias.
- **Paralelismo a nivel de instrucción**: Ejecuta grupos de instrucciones en paralelo, optimizando tareas.
- **Paralelismo a nivel de datos**: Cada procesador ejecuta la misma tarea en subconjuntos de datos diferentes.
- **Paralelismo a nivel de tareas**: Cada hilo realiza tareas distintas e independientes de los demás.

### Desafíos

- **Sincronización**: Coordinar procesos y hilos es crucial para una correcta ejecución.
- **Escalabilidad**: Lograr que el sistema funcione eficazmente con un número creciente de procesadores.
- **Comunicación**: Establecer canales eficientes para el intercambio de datos entre tareas.

---

