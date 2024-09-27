# ApplicationDemo2

## Proyecto REST de Ejemplo para Registro de Usuario Básico

Este proyecto es una aplicación que gestiona usuarios, permitiendo registrar un usuario a modo de demo utilizando Spring Boot, Spring JPA, y pruebas unitarias con JUnit.

## Descripción

La aplicación permite el registro de usuarios y está diseñada para demostrar el uso de tecnologías como Spring Boot y Spring JPA. Incluye pruebas unitarias para asegurar la calidad del código.

## Requisitos Previos

- JDK 17 o superior.
- Puerto 8086 disponible.
- IDE como IntelliJ IDEA, Eclipse o Spring Tool Suite.

## Instalación

1. **Clona el repositorio a una carpeta local**:
   ```bash
   git clone https://github.com/PatricioBerrios/DemoApplication2.git
   cd ApplicationDemo2

2. Importa el proyecto en tu IDE.
  Asegúrate de que el puerto 8086 esté libre antes de ejecutar la aplicación.

3.Ejecuta la aplicación:
  Usa la opción de "Run" en tu IDE para iniciar el proyecto.
  
4. Prueba la API:
  Con Postman o una herramienta similar, realiza una petición POST a la siguiente URL:
 
  http://localhost:8086/register

5. Utiliza el siguiente JSON como ejemplo para el registro de un usuario:

  {
    "name": "Juan Rodriguez",
    "email": "juaanrodriguez@org.com",
    "password": "Hello1",
    "phones": [
        {
            "number": "1234567",
            "citycode": "1",
            "contrycode": "57"
        },
        {
            "number": "1234568",
            "citycode": "13",
            "contrycode": "57"
        }
    ]
}

6. Pruebas

El proyecto incluye pruebas unitarias. Puedes ejecutarlas utilizando tu IDE o mediante la línea de comandos:

./gradlew test




