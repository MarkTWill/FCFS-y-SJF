Rsumen de las funciones y su funcionalidad principal:

Clase Proceso:

Define la estructura de un proceso con propiedades como ID, nombre, tiempo de llegada (TLL), y tiempo de ejecución (T).
Se utiliza para crear instancias de procesos con los valores proporcionados.
Funciones llenar y agregar:

llenar: Lee los datos ingresados en un formulario HTML y crea instancias de la clase Proceso, almacenándolas en un arreglo llamado procesos.
agregar: Agrega nuevos elementos al formulario HTML para ingresar datos de procesos adicionales.
Funciones de Planificación de Procesos (FCFS y SJF):

FCFS (First-Come, First-Served): Implementa el algoritmo de planificación FCFS para la ejecución de procesos en función de su tiempo de llegada.
SJF (Shortest Job First): Implementa el algoritmo SJF para planificar procesos basados en su tiempo de ejecución más corto.
Funciones de ayuda y cálculos:

ordenarProcesos: Utilizada por el algoritmo SJF para ordenar los procesos según su tiempo de ejecución.
llenarTabla y llenarTablaR: Funciones para calcular y mostrar los tiempos de retorno (TR) y espera (TE) de los procesos.
Manipulación del DOM y visualización:

