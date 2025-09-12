
# # Base de datos

Este repositoria es sobre las distintas clases de base de datos 2025

## Datos para trabajar en linea

A través del espacio de trabajo destinado por el módulo en marcha a través de APEX se llevará a cabo todo el trabajo asociado con el motor de base de datos ORACLE en la nube.

Para acceder a este y realizar actividades prácticas. 

Debe ingresar al siguiente LINK: https://apex.oracle.com/es/

Espacio de Trabajo: ICI_BD_S1


## Modelo 

![Modelo](https://github.com/iDvmian/Base-de-datos/blob/main/Screenshots/modeloHR.png)

## Unidad 1

### lesión 1

Sentencia SELECT Básica

SELECT identifica las columnas que se van a mostrar.
FROM identifica la tabla que contiene estas columnas.


Expresiones Aritméticas

Crear expresiones con datos de fecha y números mediante operadores aritméticos.
   
| Operador | Descripcion |
|-----------|-----------|
| +   | Sumar |
| -   | Restar   |
| *   | Multiplicar  |
| /   | Dividir  |

Ejemplos 
```
SELECT last_name, salary, salary + 300
FROM   employees;
```

al igual que en matemtaicas hay prioridad de de operadores

no e lo mismo, no poner parentecis
```

SELECT last_name, salary, 12*salary+100
FROM   employees;

```
que poerlos y hace bien pa operacion por prioridad de parentecis 

```
SELECT last_name, salary, 12*(salary+100)
FROM   employees;

```


Defincion de alias en las comunas 

Cambia el nombre de una cabecera de columna
Es útil para realizar cálculos
Sigue inmediatamente al nombre de columna (también puede ser la palabra clave opcional AS entre el nombre de columna y el alias)
Necesita comillas dobles si contiene espacios o caracteres especiales o si es sensible a mayúsculas/minúsculas








