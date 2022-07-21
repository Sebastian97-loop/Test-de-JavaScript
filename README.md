# Test-de-JavaScript
Mi solución a el Test de JavaScript

# **Variables y operaciones**

## 1️. Responde las siguientes preguntas en la sección de comentarios:

### a. ¿Qué es una variable y para qué sirve?
- Una variable es un espacio en memoria utilizado para guardar algun valor. Podemos entender facilmente una variable representandola como una caja. porque le podemos ingresar los valores o "las cosas" y llevarlas a otra parte de nuestro código.
- 
### b. ¿Cuál es la diferencia entre declarar e inicializar una variable?

    // declarar una variable
    let variable;
    
    // inicializar una variable
    variable = 0;
    
    // para hacer este proceso en una sola linea
    let caja = 0;

### c. ¿Cuál es la diferencia entre sumar números y concatenar strings?


    // sumar numeros
    // vamos a declarar las variable a y b y despues en la variable c sumanos las variables a + b
    var a = 1;
    var b = 2;
    var c = a + b;
    console.log(c);
    
    // concatenar strings
    // utilizamos el mismo codigo, solo que en la linea de el console.log concatenamos a la variable c que tiene el valor de a y b.
    var a = 1;
    var b = 2;
    var c = a + b;
    console.log("El resultado de c es igual a: " + c);
    
### d. ¿Cuál operador me permite sumar o concatenar?
     // con el sigo +

## 2. Determina el nombre y tipo de dato para almacenar en variables la siguiente información:

- Nombre : **string**
- Apellido: **string**
- Nombre de usuario en Platzi: **string**
- Edad: **number**
- Correo electrónico: **string**
- Mayor de edad: **boolean**
- Dinero ahorrado: **number**
- Deudas: **number**

## 3. Traduce a código JavaScript las variables del ejemplo anterior y deja tu código en los comentarios.



    const nombre = "Sebastian";
    const apellido "Carrillo";
    const nombreDeUsuario = "chevyto97";
    let edad = 25;
    const correoElectronico = "sebastian1997lml@hotmail.com";
    let mayorDeEdad = true;
    let dineroAhorrado = 20.000;
    let deudas = 100.000;
    
   
# funciones
## 1.  Responde las siguientes preguntas en la sección de comentarios

- ¿Que es una funcion?
Es un bloque de codigo que nos permite realizar operaciones y pueden ser llamadas en cualquier momento de el codigo

a ¿Cuándo me sirve usar una función en mi código?
Cuando a la hora de programar queremos tener codigo empaquetado, el cual lo podemos mandar a llamar con una corta accion. Por ejemplo si queremos realizar una suma no tendremos que traer toda la logica que necesita la suma sino que llamamos la funcion que creamos con esa logica.
