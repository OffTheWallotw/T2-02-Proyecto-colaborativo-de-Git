# T2-02 Proyecto colaborativo de Git
# CALCULADORA
### Juan Carlos Aguilar Lopez  18460309
### Luis Fabián Vázquez Rodríguez 20460323
### Kevin Alexandro Ocon Zaragoza 19460812

# Explicacion Breve
Por este medio se llevara acabo la instalacion y como usar  la aplicación de calculadora desde una terminal por medio de línea de comandos utilizando contenedores de Docker.

## Requisitos de instalación
Asegúrate de tener instalado y configurado Docker antes de comenzar.
- [Docker](https://www.docker.com)


## Instrucciones para la instalación

1. Primero descargar docker, al instalarlo se tiene que dejar abierto, en dado caso de ya estar instalado, simplemente abrelo

2. Entrar a la carpeta raiz del proyecto y al estar dentro del proyecto abres una terminal desde la carpeta del proyecto 

3. una vez dentro de la terminal se ejecutara el siguiente comando para crear los contenedores:

    ```sh
    docker build -t calculadora .
    ```

    > **IMPORTANTE**
    >
    > Debe estar iniciado el Docker engine para ejecutar el comando anterior,
    > si no lo está, se devolverá un mensaje de error

4. Para ejecutar el contenedor creado
      ```sh
    docker run -it calculadora
    ```
    
# Ejemplo de uso
  ```sh
   Seleccione una operación:
1.Suma
2.Resta
3.Multiplicación
4.División
Opción: 1
Ingrese el primer número: 15
Ingrese el segundo número: 15
El resultado es: 30
```

## Documentación detallada
Este código de la calculadora implementa las operaciones básicas de suma, resta, multiplicación y división. 

Para ejecutarlo, primero debemos construir el contenedor Docker usando el comando:

>docker build. 

Luego, podemos ejecutar el contenedor usando el comando 

>docker run.

El contenedor Docker incluye el código de la calculadora y todas las dependencias necesarias para ejecutarlo. Esto facilita la distribución y el despliegue de la calculadora en diferentes entornos.