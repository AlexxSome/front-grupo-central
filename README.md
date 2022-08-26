
## Requirements
- Node 16+
- Npm 8.1+
## Installation

In the project directory, you can run:
### `npm install`
### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

##Test
### `npm test`

__________________________________________________


# **Grupo central technical test**

Se requiere generar una visor para la información sobre de las causas de muerte en EEUU, a continuación se encuentra un modelo para orientar el desarrollo y los datos.

Los datos que puedes utilizar podrás encontrarlos en:  
https://catalog.data.gov/es_AR/dataset?tags=diabetes

En ese sitio tienes que acceder al dataset “Monthly Counts of Deaths by Select Causes, 2014-2019”

Explicando el funcionamiento:

- El usuario selecciona una enfermedad
    - Puede buscar una a través de una barra
    - También tiene la opción de agregarla como favorita. Al cambiar a esa pestaña, debe ver todos sus favoritos. No es necesario que se guarde este estado en la base de datos.
- Al seleccionar la enfermedad debe mostrar el nombre, si es favorito, poder seleccionar un año y mostrar un gráfico con la cantidad de fallecidos por mes para la información que exista.
- Bajo el gráfico debe mostrar una tabla con los meses y la cantidad de casos correspondientes



Algunos detalles que debes seguir:

- Tienes que crear una interfaz web (frontend) con React
- Debes crear una aplicación de servidor (backend) en Python, NodeJS u otro similar
- Tus aplicaciones deben estar publicadas en algún repositorio público (por ejemplo en GitHub o Bitbucket)

- Hay espacio para que puedas ser creativo, en caso de dudas no hay problema en que lo preguntes.

- Será evaluada la calidad del código y las prácticas que utilices. Te recomendamos no generar un gran commit con toda la solución, sino que lo vayas trabajando como si fuera un proyecto real. La idea es ver como solucionas un problema y el proceso de desarrollo.


