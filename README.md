[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Px-uYaj2)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=23105242&assignment_repo_type=AssignmentRepo)
# Lab02 - Sumador/Restador de 4 bits

# Integrantes
[Wilmar Andrey Gil Cupacan](https://github.com/wilmarandreygc10-maker)
[Tomas Camilo Leon Torres](https://github.com/tomascleont-commits)
# Informe

Indice:

1. [Documentación](#documentación-de-los-circuitos-implementados-implementado)
2. [Simulaciones](#simulaciones)
3. [Evidencias de implementación](#evidencias-de-implementación)
4. [Preguntas](#preguntas)
5. [Conclusiones](#conclusiones)
6. [Referencias](#referencias)

## Documentación del diseño implementado

### 1. Sumador/Restador

#### 1.1 DescripciónEn el presente laboratorio se diseñó e implementó un circuito sumador/restador de 4 bits empleando el método del complemento a 2.

El diseño se fundamenta en la reutilización de un sumador binario previamente desarrollado, al cual se le añadieron compuertas lógicas, permitiendo seleccionar entre operaciones de suma y resta.

Cuando la señal Sel = 0, el circuito realiza la operación:

𝐴
+
𝐵
A+B

Debido a que las compuertas XOR permiten el paso directo de la señal 
𝐵
B.

Cuando la señal Sel = 1, el circuito ejecuta la operación:

𝐴
−
𝐵
A−B

Esto ocurre porque:

Las compuertas invierten los bits de 
𝐵
B, generando el complemento a 1.

La misma señal Sel se conecta al acarreo inicial del primer sumador, añadiendo el +1 necesario para obtener el complemento a 2.

De esta manera, la resta se transforma en una suma binaria, simplificando el diseño del hardware.

El sistema está compuesto por:

Cuatro sumadores completos de 1 bit conectados en cascada.

Cuatro compuertas XOR para el control del sustraendo.

Una señal de control de operación.

Propagación de acarreo tipo Ripple Carry.

El bit de acarreo final permite interpretar si el resultado es positivo o negativo.

#### 1.2 Diagramas


## Simulaciones 

### 1. Simulación del sumador/restador

#### 1.1 Descripción

#### 1.2 Diagrama


## Evidencias de implementación


## Conclusiones


## Referencias
