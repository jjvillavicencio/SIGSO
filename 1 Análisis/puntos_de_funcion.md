- [Prototipado](#prototipado)
    - [Gestión del grupo de patrulla de caminos](#gesti%C3%B3n-del-grupo-de-patrulla-de-caminos)
        - [Prototipos](#prototipos)
        - [Cálculo de los Puntos de función sin ajustar](#c%C3%A1lculo-de-los-puntos-de-funci%C3%B3n-sin-ajustar)
        - [Factores de ajustes de complejidad](#factores-de-ajustes-de-complejidad)
        - [Cálculo de los puntos de función](#c%C3%A1lculo-de-los-puntos-de-funci%C3%B3n)
        - [Cálculo del esfuerzo](#c%C3%A1lculo-del-esfuerzo)
        - [Cálculo de lineas de código](#c%C3%A1lculo-de-lineas-de-c%C3%B3digo)
        - [Cálculo esfuerzo de personas/mes](#c%C3%A1lculo-esfuerzo-de-personasmes)
        - [Calculo de la duración del proyecto](#calculo-de-la-duraci%C3%B3n-del-proyecto)
        - [Duración en meses](#duraci%C3%B3n-en-meses)
        - [Costo total del proyecto](#costo-total-del-proyecto)

# Prototipado

En esta sección se muestran los componentes que se han considerado para la estimación con puntos de función.

## Gestión del grupo de patrulla de caminos

Gestión de vehículos a motor
* Administración de datos maestros
* Acceso a información actualizada sobre el solicitante para informar y tomar decisiones

### Prototipos


|             | Interfaz principal |    |    |     |     |
|-------------|--------------------|----|----|-----|-----|
| Descripción | EI                 | EO | EQ | ILF | EIF |
| Navegación  | 6                  | 6  |    |     |     |
|             |                    |    |    |     |     |
| Total       | 6                  | 6  |    |     |     |




|                             | Formulario de solicitud |    |    |     |     |
|-----------------------------|-------------------------|----|----|-----|-----|
| Descripción                 | EI                      | EO | EQ | ILF | EIF |
| Descripción del vehículo    | 7                       | 2  | 1  | 3   | 2   |
| Descripción del propietario | 4                       | 2  | 2  | 1   | 1   |
| Descripción de la solicitud | 1                       | 2  |    | 1   |     |
| Solicitar                   | 1                       | 2  | 3  | 4   | 2   |
| Total                       | 13                      | 6  | 6  | 8   | 5   |


|                             | Formulario de quejas |    |    |     |     |
|-----------------------------|----------------------|----|----|-----|-----|
| Descripción                 | EI                   | EO | EQ | ILF | EIF |
| Descripción del vehículo    | 3                    | 2  | 1  | 1   |     |
| Descripción del propietario | 2                    | 2  | 1  | 1   | 1   |
| Cargar informe de quejas    | 2                    | 3  | 1  | 1   |     |
| Registrar                   | 1                    | 2  | 3  | 3   | 1   |
| Total                       | 8                    | 9  | 6  | 6   | 2   |


|                   | Informe de historial |    |    |     |     |
|-------------------|----------------------|----|----|-----|-----|
| Descripción       | EI                   | EO | EQ | ILF | EIF |
| Datos del informe | 3                    | 2  | 1  | 2   |     |
| Visualización     | 1                    | 1  |    |     |     |
| Generar           | 1                    | 2  | 2  | 2   |     |
| Total             | 5                    | 5  | 3  | 4   |     |




|                   | Informe de ingresos |    |    |     |     |
|-------------------|---------------------|----|----|-----|-----|
| Descripción       | EI                  | EO | EQ | ILF | EIF |
| Datos del informe | 5                   | 3  | 2  | 2   |     |
| Visualización     | 1                   | 1  |    |     |     |
| Generar           | 1                   | 2  | 2  | 2   |     |
| Total             | 7                   | 6  | 4  | 4   |     |



|                   | Informe de   vehículos en mal estado |    |    |     |     |
|-------------------|--------------------------------------|----|----|-----|-----|
| Descripción       | EI                                   | EO | EQ | ILF | EIF |
| Datos del informe | 3                                    | 2  | 1  | 2   |     |
| Visualización     | 1                                    | 1  |    |     |     |
| Generar           | 1                                    | 2  | 2  | 2   |     |
| Total             | 5                                    | 5  | 3  | 4   |     |

|                   | Informe de vehículos registrados |    |    |     |     |
|-------------------|----------------------------------|----|----|-----|-----|
| Descripción       | EI                               | EO | EQ | ILF | EIF |
| Datos del informe | 3                                | 2  | 1  | 2   |     |
| Visualización     | 1                                | 1  |    |     |     |
| Generar           | 1                                | 2  | 2  | 2   |     |
| Total             | 5                                | 5  | 3  | 4   |     |


|                             | Formulario   de registro de estado del vehículo |    |    |     |     |
|-----------------------------|-------------------------------------------------|----|----|-----|-----|
| Descripción                 | EI                                              | EO | EQ | ILF | EIF |
| Descripción del vehículo    | 3                                               | 2  | 1  | 2   |     |
| Descripción del propietario | 6                                               | 2  | 2  | 1   |     |
| Estado del vehículo         | 12                                              | 2  |    | 1   |     |
| Registrar                   | 1                                               | 2  | 3  | 4   |     |
| Total                       | 22                                              | 8  | 6  | 8   |     |

|                             | Formulario de   registro de vehículo |    |    |     |     |
|-----------------------------|--------------------------------------|----|----|-----|-----|
| Descripción                 | EI                                   | EO | EQ | ILF | EIF |
| Descripción del vehículo    | 11                                   | 2  | 1  | 1   | 2   |
| Descripción del propietario | 3                                    | 2  | 1  | 1   |     |
| Registrar                   | 1                                    | 2  | 2  | 2   | 2   |
| Total                       | 15                                   | 6  | 4  | 4   | 4   |

### Cálculo de los Puntos de función sin ajustar

| Puntos de   función sin ajustar |             |      |       |    |   |    |   |   |    |     |
|---------------------------------|-------------|------|-------|----|---|----|---|---|----|-----|
| Descripción                     | Complejidad |      |       |    |   |    |   |   |    |     |
| Baja                            | Media       | Alta | Total |    |   |    |   |   |    |     |
| Entradas (EI)                   | 6           | x    | 3     | 80 | x | 4  |   | x | 6  | 338 |
| Salidas (EO)                    | 6           | x    | 4     | 45 | x | 5  |   | x | 7  | 249 |
| Consultas (EQ)                  |             | x    | 3     | 35 | x | 4  |   | x | 6  | 140 |
| Archivos (ILF)                  |             | x    | 5     | 42 | x | 10 |   | x | 15 | 420 |
| Interfaz del programa (EIF)     |             | x    | 5     | 11 | x | 7  |   | x | 10 | 77  |
| PFSA                            | 1224        |      |       |    |   |    |   |   |    |     |

### Factores de ajustes de complejidad

|                             |                                         |       |
|-----------------------------|-----------------------------------------|-------|
| #                           | Factor de complejidad                   | Valor |
| 1                           | Comunicación de datos                   | 4     |
| 2                           | Proceso distribuido                     | 4     |
| 3                           | Rendimiento                             | 5     |
| 4                           | Configuración operacional   compartida  | 5     |
| 5                           | Ratio de transacciones                  | 5     |
| 6                           | Entrada de   datos en linea             | 5     |
| 7                           | Eficiencia   con el usuario final       | 5     |
| 8                           | Actualizaciones en linea                | 5     |
| 9                           | Complejidad del proceso interno         | 5     |
| 10                          | Reusabilidad del código                 | 5     |
| 11                          | Contempla   la conversión e instalación | 3     |
| 12                          | Facilidad de operación                  | 5     |
| 13                          | Instalaciones múltiples                 | 0     |
| 14                          | Facilidad de cambios                    | 5     |
| Factor de complejidad total | 61                                      |       |

### Cálculo de los puntos de función

```js
PF = PFSA * (0,65 + (0.01 * Ʃ(Fi))

PF = 1224 * (0,65 + (0,01 * 61))

PF = 1542,24

```
### Cálculo del esfuerzo

| Lenguaje   | QSM      |       |      |      |
|------------|----------|-------|------|------|
|            | Promedio | Medio | Bajo | Alto |
| JavaScript | 47       | 53    | 31   | 63   |

### Cálculo de lineas de código

```js
LOC = PF * LOCPF
LOC = 1542,24 * 47
LOC = 72485,28

```

### Cálculo esfuerzo de personas/mes

```js
PF/(1/8 personas/hora)
1542,24/0,125
12337,92 horas/persona

```

### Calculo de la duración del proyecto

```js
(Esfuerzo Hora/persona)/personas
12337,92/13
949,07

```

### Duración en meses

```js
949,07 horas / 100 horas/mes
9 meses y 9 días

```

### Costo total del proyecto

```js
Sueldo participante * 13 participantes * 9 meses + otros costos
1200 * 13 * 9
140400

```