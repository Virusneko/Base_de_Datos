
## Práctica 4
### Data warehouse

Objetivo: Demostrar la identificación de los elementos que componen data warehouse y
su esquema

Ejercicio:

1. ¿Qué es un DataWarehouse?(valor 2) Donde se almacenan los datos

2. Realiza un diseño del modelo en estrella (valor 2) 
![image](https://user-images.githubusercontent.com/99296446/172029246-f68fbf65-e27e-466f-bb9d-3b578c0f3097.png)

3. Realiza un diseño del modelo copo de nieve (valor 2)
![image](https://user-images.githubusercontent.com/99296446/172029308-49805b48-0caf-4b13-b396-cdb5e749b48c.png)

## Práctica 7
### Funciones en SQL
Objetivo: Demostrar el uso y aplicación en una base de datos para mejorar la gestión

Ejercicio:

1. Calcula el número total de productos que hay en la tabla productos. (valor 4.5)

![image](https://user-images.githubusercontent.com/99296446/173208109-54c55f24-3753-4304-9892-fa8232b5fa70.png)

2. Muestra el número total de productos que tiene cada uno de los fabricantes. El listado
también debe incluir los fabricantes que no tienen ningún producto. El resultado
mostrará dos columnas, una con el nombre del fabricante y otra con el número de
productos que tiene. Ordene el resultado descendentemente por el número de
productos. (valor 4.5)

![image](https://user-images.githubusercontent.com/99296446/173208157-751f7d97-7bc5-4338-a5c1-9de8f8b861ae.png)

(la imagen de arriba muestra como debia ser el odigo pero db fiddle no acepta el comando)

![image](https://user-images.githubusercontent.com/99296446/173208164-37466c4d-c891-4605-99e2-f5d4f0770b42.png)

3. Muestra el precio máximo, precio mínimo y precio medio de los productos de cada
uno de los fabricantes. El resultado mostrará el nombre del fabricante junto con los
datos que se solicitan. (valor 4.5)

![image](https://user-images.githubusercontent.com/99296446/173208029-e9fc9d2f-27a6-43a5-ae41-11ed76c9d2aa.png)

4. Muestra el nombre de cada fabricante, junto con el precio máximo, precio mínimo,
precio medio y el número total de productos de los fabricantes que tienen un precio
medio superior a 200€. Es necesario mostrar el nombre del fabricante. (valor 4.5)

![image](https://user-images.githubusercontent.com/99296446/173208283-eee8dfd9-193d-4f68-9fee-486f06b5fcc8.png)


## Práctica 8.
### Disparadores (Triggers)

Objetivo: Demostrar las operaciones que se realizan en una base de datos.

Ejercicio: Crea una base de datos llamada test que contenga una tabla llamada
alumnos con las siguientes columnas. (valor 18)

Evaluación:

Creación de la base de datos : 9 puntos.

Creación de los Disparadores(Triggers): 9 puntos.

Tabla alumnos:

● id (entero sin signo)

● nombre (cadena de caracteres)

● apellido1 (cadena de caracteres)

● apellido2 (cadena de caracteres)

● nota (número real)

Una vez creada la tabla escriba dos triggers con las siguientes características:

● Trigger 1: trigger_check_nota_before_insert

  o Se ejecuta sobre la tabla alumnos.
  
  o Se ejecuta antes de una operación de inserción.
  
  o Si el nuevo valor de la nota que se quiere insertar es negativo, se guarda
  como 0.
  
  o Si el nuevo valor de la nota que se quiere insertar es mayor que 10, se
  guarda como 10.
  
  ![image](https://user-images.githubusercontent.com/99296446/173208410-ca3a111a-1a7d-446a-9a36-4c6f23fe4835.png)

● Trigger2 : trigger_check_nota_before_update
  o Se ejecuta sobre la tabla alumnos.
  
  o Se ejecuta antes de una operación de actualización.
  
  o Si el nuevo valor de la nota que se quiere actualizar es negativo, se guarda
  como 0.
  
  o Si el nuevo valor de la nota que se quiere actualizar es mayor que 10, se
  guarda como 10.
  
  ![image](https://user-images.githubusercontent.com/99296446/173208742-8ab050ca-5160-4d6c-b8ee-33c0984c3412.png)
  
Una vez creados los triggers escribe varias sentencias de inserción y actualización
sobre la tabla alumnos y verifica que los triggers se están ejecutando
correctamente.
