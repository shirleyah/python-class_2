# [Nombre del proyecto]

Fecha: dd/mm/202X  

**Participantes**:

- [Nombre] <email:username@ccg/lcg.unam.mx>  

## Descripción del Problema


[Especificar la problemática que se presenta y la sollución que se espera obtener.]  


## Especificación de Requisitos

Requisitos funcionales

- Requisito 1: [descripción]  
- Requisito 2: [descripción]  
- Requisito 3: [descripción]  
- Requisito 4: [descripción]  
- Requisito 5: [descripción]  

Requisitos no funcionales

- Requisito no funcional 1: [descripción]  
- Requisito no funcional 2: [descripción]  
- Requisito no funcional 3: [descripción]  



## Análisis y Diseño

[Especificar cómo se llegará a la solución del problema. Se pueden incluir diagramas de casos de uso, pseudocódigos, y cualquien otro gráfico que describa la solución. Si se reciben datos de entrada se debe especificar el formato en el que se requieren , el tipo de archivo esperado, formato de resultados  ]  


```
Función principal (Suma_Numero):
    Intentar:
        datos_archivo = Obtener_Datos_Archivo(ruta_archivo)
        numeros = Validar_Datos(datos_archivo)
        resultado = Calcular_Suma(numeros)
        Imprimir_Resultado(numeros, resultado)
    Atrapar cualquier excepción como error:
        Imprimir el error

Función Obtener_Datos_Archivo(ruta_archivo):
    Si la ruta del archivo no existe:
        Levantar un error de "archivo no encontrado"
    Leer y retornar las líneas del archivo

Función Validar_Datos(data):
    Intentar:
        Convertir todos los datos a formato flotante y retornar como una lista
    Atrapar ValorError:
        Levanta un error de "¡Introducir solamente números de base 10!"

Función Calcular_Suma(numeros):
    Retornar la suma de los números

Función Imprimir_Resultado(numeros, resultado):
    Imprimir los números y su suma total en el formato especificado
```



#### Caso de uso: [Nombre del caso de uso]

```
         +---------------+
         |   [Actor]     |
         +-------+-------+
                 |
                 | 
                 v
         +-------+-------+
         |    [Caso      |
         |     de        |
         |     uso       |
         |   (actor)]    |
         +---------------+
```

- **Actor**: [Nombre del actor]
- **Descripción**: [Descripción del caso de uso]
- **Flujo principal**:

	1. [Paso 1]  
	2. [Paso 2]  
	3. [Paso 3]  
	4. [Paso X]  
	
- **Flujos alternativos**:
	- [Condicional 1]
	1. [Paso 1]  
	- [Condicional X]
	1. [Paso 1]  
                

