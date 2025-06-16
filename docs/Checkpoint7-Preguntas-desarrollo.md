# DIFERENCIAS JAVASCRIPT Y OTROS LENGUAJES DE PROGRAMACIÓN  

<img src= "https://github.com/user-attachments/assets/6ba011f5-a836-4f17-9de0-74b42cf6774f" alt = "Ejemplo Captura de pantalla" width= "600">

***

  

* JavaScript es el ***único*** lenguaje de programación que un navegador web puede entender. Todos los demás necesitan un servidor para que construya todos los procesos y muestre el código de una manera que el navegador pueda interpretar.  

Fue creado con este fin. Una herramienta que cualquier navegador pueda entender. Cuando escribes código JavaScript simplemente lo pones en el navegador, este lo analiza, lo interpreta y lo ejecuta.  

* Las aplicaciones más poderosas del mundo están integradas en JavaScript. Actualmente no hay manera de trabajar en el mundo del desarrollo sin este lenguaje de una forma u otra. **Gmail**, **Twitter**, o **Facebook** se han creado con JavaScript y lo usan de forma extensiva.  

  
  

<img src="https://github.com/user-attachments/assets/24c157a8-8b56-4e8a-9582-d5f71046adf2" alt="Ejemplo de Captura de Pantalla" width="600">


***


Un ejemplo claro es Google que ha creado su propio marco de JavaScript para su uso propio. Tomaron este lenguaje y construyeron sus propios sistemas.  

* Si quieres crear aplicaciones móviles no puedes hacerlo sino conoces JavaScript. Sus desarrolladores tomaron sus propias bibliotecas que les permiten construir sus propias aplicaciones utilizando sólo JavaScript que se traduce directamente a las APIs de los teléfonos inteligentes.  

Para construir algo para Apple o Android necesitas JavaScript.  

 

 
<img src="https://github.com/user-attachments/assets/9b430324-fe08-45a1-809c-0e6fbc878303" alt="Ejemplo de Captura de Pantalla" width="600">


***


Para crear una aplicación que pueda usar la cámara de un teléfono, verificar la ubicación usar el pulsómetro... antes tenías que aprender un lenguaje o idioma para cada cosa. Ahora JavaScript hace posible todo esto.  

* Este lenguaje de programación es uno de los recursos más poderosos para automatizar el flujo de trabajo.  

Un ejemplo de esto es si en una aplicación necesitas actualizar y seguir a un grupo grande de personas. En lugar de ir una por una manualmente dando click y escribir algo. Con JavaScript puedes crear un simple script que se ejecuta y automatiza el trabajo. En un segundo tienes el trabajo echo porque JavaScript lo hace con un poco de código.  

* La principal diferencia de JavaScript radica en su flexibilidad, su papel fundamental en el desarrollo web interactivo y su capacidad de ser utilizado tanto en el front-end como en el back-end , lo que lo convierte en un lenguaje muy potente y versátil en el panorama actual de la programación.  

# TIPOS DE DATOS EN JAVASCRIPT  

Los tipos de datos es la forma en que JavaScript ve las cosas. Si tenemos variables, que es lo más común, es como JavaScript ve este tipo de variables. Por ejemplo si ve un enunciado con palabras o ve un número.   

Son los tipos de datos más básicos y fundamentales en JavaScript. Son inmutables, lo que significa que una vez que se crea un valor, no se puede modificar.  

1. __Booleanos__. Es un tipo de datos que sólo acepta si es verdadero o falso. Representa un valor lógico.
Se usa comúnmente para condicionales.
Ejemplo:  true (verdadero) o false (falso).  

~~~
if (usuarioConectado) { 
  console.log("¡Estás conectado!");
} else {
  console.log("La sesión ha terminado.");
~~~

2. **Null**. Es la ausencia de cualquier valor. Null significa vacío. Es un valor que se asigna explícitamente para indicar "nada" o "vacío".  

Ejemplo:

~~~
100 + null;
~~~  

JavaScript ve el nulo y en vez de dar error, convierte nulo en nulo.

3. **Underfined**. Indefinido. Cuando tenemos algo en el código que simplemente es declarado y no se le da ningún valor. Te has podido olvidar o has omitido poner un valor. Por defecto cuando declaras una variable JavaScript va a establecer que es igual a underfined.  

Ejemplo: 

~~~
var name= "Alba";
   undefined ( Nos indica que el nombre Alba ha sido almacenado en la variable name.)
~~~  

No le hemos asignado ningún valor, sólo lo declaramos.


  

Null significa que unos datos están definidos. Tenemos acceso a la variable pero está vacía. Underfined significa que el valor no ha sido aún asignado, no está vacío, literalmente no hay valor que esté aún ahí.(Lo normal es que sea asignado más tarde). 

4. **Number**. Son tipos de datos numéricos. Son inmutables, lo que significa que una vez que se crea un valor, no se puede modificar. Representa tanto números enteros como números de punto flotante (decimales). JavaScript no distingue entre ellos a nivel de tipo.  

Ejemplo: 

~~~
number =15;
number= 8,5;
number= -10;
~~~ 

5. **String**. Se usa para palabras y enunciados. Son tipos de datos en cadena de caracteres.  Se encierran entre comillas simples (') o dobles (").
Son inmutables: cualquier operación que parezca modificar una cadena en realidad crea una nueva cadena.
Ejemplo:

~~~ 
var greeting ="Hi there";
~~~  



6. **Symbol**. Los símbolos son como las cadenas pero más específicos. No pueden ser cambiados, sólo puede haber uno de ellos. Es un tipo de datos inmutable. Vale para trabajar con objetos.  

Ejemplo: 

~~~
Symbol ("id");
~~~   


#  FUNCIONES DE STRING EN JAVASCRIPT  


<img src = "https://github.com/user-attachments/assets/0b34ee12-246b-4587-a58f-2fb037f79234" alt = "Ejemplo Captura de pantalla" width= "600">


***


Una función te permite poner comportamiento en el código. No podemos crear las funciones, están creadas en la librería básica de JavaScript. Así que simplemente tenemos que llamarlas. (Aunque también se pueden crear funciones propias).  

Las funciones nos permite realizar una tarea una y otra vez, sin tener que repetir el código todo el rato.  

Con la forma en que funcionan las variables en JavaScript, cuando se pasan a funciones simplemente pasan un valor porque es difícil que cuando tienes una variable original quieras cambiarla. Sólo cambiaría si añadimos (lo que nos da con las funciones) a una nueva variable o podríamos conectarlo a otra función. 
  

Hay muchas funciones de cadena en JavaScript y muchos métodos para manipular estas cadenas. La utilidad de cada método nos sirve dependiendo de lo que necesites hacer en cada momento.  

Aunque ya hemos dicho que hay muchas funciones hay algunas muy comunes y muy útiles.  


Lo primero no es crear una función, sino llamar a un atributo y luego incluiremos nuestras funciones.  

   

~~~
var str = "Estamos aprendiendo JavaScript"; 
~~~  

 **1** Funciones que buscan valores o encuentran un índice de un carácter. Son funciones de ** _búsqueda_ o _verificación_ **. Estos métodos ayudan a encontrar información dentro de una cadena, encontrar la posición de un carácter o a verificar ciertas condiciones.( Si una cadena contiene otra..)



> **charAT**. Esta función trabaja con el índex de la cadena. Al llamar a charAt y pasar un argumento queremos cualquier letra que esté en ese índex.  

~~~
var str = "Estamos aprendiendo JavaScript";
str.charAt (2); 
console.log(str.charAt (2)); // nos devuelve "t" que es la letra que está en el índice 2.
~~~  

Siempre tendremos en cuenta que en programación todos los índices empiezan en cero. El primer elemento siempre es cero.  

~~~
var str = "Estamos aprendiendo JavaScript";
str.charAt(350);
console.log(str.charAt (350)); // No devuelve nada.
""
~~~

Si llamas a un índice que no existe en nuestra cadena(350) nos devuelve una cadena vacía. Esto es bueno pero también puede confundir. A veces es mejor que te den error. Pero lo que nos dice es que no encontró nada en ese índice.

 

> **Includes**. Sirve para ver si algún valor está incluido en la cadena (string). Es una función muy sencilla, puedes pasar cualquier cosa y si está en la cadena original nos dará "true" y si no lo encuentra dará "false".  

~~~
var str = "Estamos aprendiendo JavaScript";
str.includes ("JavaScript");
console.log(str.includes ("JavaScript")); // Nos devolverá true.
str.includes("hola"); // Nos dará false.
~~~  

> **startsWith** En vez de buscar por toda la cadena sólo va al principio. Si lo encuentra "true" si no "false".  

~~~
var str = "Estamos aprendiendo JavaScript";
str.startsWith("aprendiendo");  
console.log(str.startsWith("aprendiendo")); // Nos devuelve false.
~~~  


> **endsWith** Busca la última palabra de la cadena, o cualquier elemento. No sólo revisa palabras, también carácter por carácter o si quieres saber si algo termina en ; .  

~~~
var str = "Estamos aprendiendo JavaScript";
str.endsWith("t");
console.log(str.endsWith("t")); // Nos devuelve true.
str.endsWith ("JavaScript"); 
console.log(str.endsWith("JavaScript")); // También es true.
~~~  

> **search**. Búsqueda. Lo que hace es mirar, buscar y cuando encuentra un patrón que coincide nos devuelve el índice en el que esté.  

~~~
var nuevaCadena = "El mar está precioso pero el mar es peligroso";
str.search("p");
console.log(str.search("p")); // Esto nos devuelve 9. Donde encuentra "p".
~~~  

Hay algunas funciones que lo que buscan es un índice determinado. Donde podemos encontrar determinada palabra o caracter.  


> **indexOf**. Le tienes que dar un argumento para que lo busque, busca en toda la cadena y una vez que encuentra lo que estamos buscando nos da su índice, si hay dos palabras o letras o atributos iguales siempre nos va a dar el índice del primero que encuentre.  

~~~
var nuevaCadena = "El mar está precioso pero el mar es peligroso";
str.indexOf("mar");
console.log(str.indexOf("mar")); // Nos devuelve 3 que es el índice donde se encuentra la palabra mar.
~~~ 


> **lastIndexOf**. También tienes que darle un dato. Pasa por toda la cadena y devuelve lo último que encuentra (si hay tres palabras iguales, nos dará el índice de la última)  

~~~
var nuevaCadena = "El mar está precioso pero el mar es peligroso";
str.lastIndexOf("mar");
console.log(str.lastIndexOf("mar")); // Nos devuelve 29 que es el índice del último mar que encuentra.
~~~ 

  

   
**2** **_Manipulación de contenido_**. Funciones que sirven para cambiar, extraer partes de la cadena o añadir.  

> **slice**. Es una función de división. Le tienes que dar un elemento y cuando lo encuentra nos dará el resto de la cadena a la derecha del índice que le hemos dado. También puede usar negativos para encontrar por ejemplo los últimos dígitos de algo. También sirve para agarrar un trozo de la cadena (pasas dos argumentos o dos índices para coger exactamente lo que quieres de la cadena.) 

~~~
var str = "Estamos aprendiendo JavaScript";
str.slice(9); // Nos daría "aprendiendo JavaScript".
str.slice(-11); // Nos daría "JavaScript".
str.slice(10,20); // Nos devuelve "aprendiendo".(Del índice 10 al 20 lo que esté en la cadena).  
~~~   


 

> **str.match** . Es una función de coincidencia. Tomará una expresión regular y nos dirá si es una coincidencia. La capacidad de usar esto es para ver si algo contra lo que quieres verificar es una coincidencia o no. Se usa por ejemplo para validar formularios. Cuando tienen que poner un correo electrónico y tienes que asegurarte de que se escribe correctamente coincidiendo lo que ponen con un patrón de lo que es un correo electrónico. Si lo que escribe la gente sigue los patrones de un correo electrónico sería una coincidencia y el correo electrónico seguiría adelante. Sino tendfrías que poner un correo válido.  

> **replace**. Reemplaza algo para que no se repita. Tienes que darle dos argumentos, el primero es lo que está buscando y el segundo separado por una coma es lo que quiero reemplazar. Puedes pasar una expresión regular como primer argumento porque hay veces en las que no sabes lo que estas buscando.  

~~~
var str = "Estamos aprendiendo JavaScript";
str.replace("aprendiendo", "jugando");
console.log(str.replace("aprendiendo", "jugando")) // Nos daría "Estamos jugando JavaScript".
~~~  

  

> **concat** es una función que es una abreviatura de concatenar. No cambia la cadena , sólo cambia el valor. Sirve para conectar dos frases, palabras.  

~~~
var str = "Estamos aprendiendo JavaScript";
str.concat (" y vamos poco a poco");
console.log(str.concat(" y vamos poco a poco")); // Nos devuelve "Estamos aprendiendo JavaScript y vamos poco a poco"
~~~  

Combina lo que le hemos pasado como argumento a concat y lo pone al final de la primera cadena.  

**concat** no cambia la cadena original, simplemente cambiamos el valor. Para conectar las dos frases permanentemente tendríamos que crear una nueva cadena.   

> **repeat** . Como argumento puedo pasar las veces que quiera repetir una cadena. Lo repite las veces que le digas y lo incluye todo en una sola cadena. No altera la cadena original. Sólo devuelve un valor. Es difícil que quieras cambiar la variable original. Si quieres hacerlo deberías crear una nueva variable.  

~~~
var str = "Estamos aprendiendo JavaScript";
str.repeat(2);
console.log(str.repeat(")); // Nos devuelve dos veces la misma cadena. "Estamos aprendiendo JavaScriptEstamos aprendiendo JavaScript".
~~~
   
 

**3** _**Transformación**_. Cambian las letras o eliminan espacios en blanco. Cambian el caso de una cadena, ya sea a mayúsculas o a minúsculas.  



> **Trim**. Es una función muy útil y beneficiosa para limpiar datos, elementos, espacios en blanco.. Se puede encadenar con otras funciones.  

  
~~~
var cadenaNueva= "    Hola   ";
cadenaNueva.trim();
console.log(cadenaNueva.trim()); // Nos devuelve Hola (sin ningún espacio al principio ni al final de la palabra).
~~~



> **toUpperCase**. Convierte todos los valores de la cadena en mayúsculas.  

~~~
var str = "Estamos aprendiendo JavaScript";
str.toUpperCase();
console.log(str.toUpperCase("Estamos aprendiendo JavaScript));  // Nos devuelve ESTAMOS APRENDIENDO JAVASCRIPT
~~~ 

   

 

> **toLoweCase**. Convierte todos los valores de la cadena en minúsculas.  

~~~
var str = "Estamos aprendiendo JavaScript";
str.toLowerCase();
console.log(str.toLowerCase("Estamos aprendiendo JavaScript")); // Nos devuelve estamos aprendiendo javascript.
~~~  



# CONDICIONAL EN JAVASCRIPT  



 

<img src="https://github.com/user-attachments/assets/bc10066c-25c2-4b14-8428-592413e868f5" alt="Ejemplo de Captura de Pantalla" width="600">  


***


Los condicionales son imprescindibles en cualquier lenguaje de programación. Permiten un comportamiento dinámico en las aplicaciones.
Nos dan la capacidad de observar un par de valores o múltiples y como se relacionan entre sí para ver si son iguales entre sí o no.
También puedes comprobar si los valores son del mismo tipo o no.
En la vida real los condicionales están por todas partes. ( Si llueve, cojo paraguas. Si el semáforo está en verde, cruzo..)
Las sentencias condicionales permiten ejecutar código específico sólo si se cumple una determinada condición. Sirven para ir tomando decisiones a lo largo de un programa.  

 _If_,_else_ y _else if_ son las principales formas condicionales. Un poco distinto a estas sentencias tenemos el operador _ternario_.  

1. ## SENTENCIA IF  

Es el condicional básico, ejecuta lo que le decimos si una sentencia es verdadera.
La sintaxis para utilizar _if_ es poner entre paréntesis la condición. Y en ella tenemos diferentes opciones, la **igualdad**i que escribiríamos == y la **igualdad estricta** ===. O la **desigualdad** != y la **desigualdad estricta** !==. También es normal utilizar código como **menor que**(<), **mayor que** (>), **menor o igual** (<=) o **mayor o igual** (>=).

~~~ 
var number = 18;
var numberTwo = "18";
if (number == numberTwo){
    console.log ("Son iguales"); 
}
~~~  

Esto nos dará "Son iguales" .
Cuando en un condicional utilizamos la igualdad (normal) sólo nos centramos en el valor de algo.
En este caso las dos variables tienen un valor de 18 aunque numberTwo actúe como una cadena y number como un dato numérico. Esto quiere decir el tipo de datos no es igual.  

Lo ideal es utilizar la igualdad estricta (===), es decir, el condicional busca si las dos variables son iguales en cuanto a valor y a tipo de dato. Asi nos evitamos posibles errores.

Igual que la igualdad, utilizamos la desigualdad. Y aquí también lo mejor es usar la desigualdad estricta (! ==).  

~~~
if (number !== numberTwo) {
    console.log ("No son iguales");
}
~~~  

~~~
if (number>= 16)}
    console.log("Puedes ver película en el cine");

~~~  

2. ## ELSE  

La sentencia _if_ no es muy útil sin tener la capacidad de dar otra opción. _If_ la mayoría de las veces necesitará de _else_ para tener sentido.  
Si el primer condiconal es falso quiero que se ejecute otra cosa. Esta sentencia te permite ejecutar un bloque de código si la condición es verdadera, y un bloque de código diferente si la condición es falsa.
La sintaxis de _else_ es distinta. Cuando colocamos la sentencia if tenemos que cerrarla con paréntesis rizados {}. Cuando cerramos el código colocamos la sentencia else. Y volvemos a abrir paréntesis rizados para colocar el resto del condicional dentro.  

~~~
if (age>=18){
   console.log ("Puedes conducir");
}else {
   console.log("No puedes conducir");
}
~~~  

Si nuestra variable de edad es 16, nos devolverá "No puedes conducir" se ignora la primera condición porque no se cumple y como no es cierta se ejecuta la segunda opción. Si la variable es 20 nos dirá que "Puedes conducir", en este caso la primera opción es verdadera por lo tanto se ignora el resto del código.  

3. ## ELSE IF  

Sirve para manejar múltiples condiciones, puedes encadenar varias sentencias if utilizando else if. JavaScript evaluará las condiciones en orden, y ejecutará el bloque de código de la primera condición que sea verdadera.
En este condicional tenemos que dar dos argumentos La sintaxis es parecida a _else_ aunque dentro de este condicional tenemos que poner más código.  

~~~
var age = 8;
if (age <= 10) {
   console.log ("Puedes comer menu infantil");
   console.log ("Puedes conducir");
   console.log ("No eres mayor para alquilar un coche");
}else if (age >16 && age <25){
} 
~~~  

Si la variable es 8, nos dará como reslutado "Puedes comer menu infantil".

_Else if_ revisa el condicional de izquierda a derecha y toma en cuenta los dos argumentos, en este caso, mayor que 16 y menos que 25. Si se cumple el primer condicional(mayor que 16) mira el segundo y si ambos son ciertos, todo lo que esté dentro de las llaves {} va a continuar. Pero si el primero es verdadero (mayor que 16) pero el segundo no (menor que 25) entonces todo el enunciado va a ser falso y pasará al siguiente condicional si lo hay.
Poe ejemplo age= 30 no nos devuelve nada porque no cumple ninguno de los condicionales. En este caso estaría bien poner otro _else if_ para ser más explícito. Siempre hay que intentar asegurarte de que lo que estés buscando sea lo que vas a encontrar. 

4. ##  OPERADOR TERNARIO  

Dentro de los condicionales también encontramos el operador ternario.  

# OPERADOR TERNARIO  


 

<img src = "https://github.com/user-attachments/assets/879940bc-cb34-4b5d-925c-19ebfa922c97" alt =" Ejemplo Captura pantalla" width= "600">

***


El operador ternario es una forma abreviada de escribir una sentencia _if..else_ simple en una sola línea. Es útil para asignaciones condicionales de valores o para expresiones cortas. Sólo se pueden poner dos sentencias. Si tenemos más condiciones es mejor usar los condicionales simples.  

~~~
var tieneDinero = true;
var mensaje = tieneDinero ? "Puedes comprarlo." : "Necesitas ahorrar.";

console.log(mensaje); 
~~~  

Este código nos dará como resultado la sentencia "Puedes comprarlo."  

Los condicionales son importantes en los programas porque utilizándolos creas una lógica y es dinámica. Permites que el código reaccione de una forma determinada dependiendo de las circunstancias.  




<img src = "https://github.com/user-attachments/assets/4ab1e9f5-892b-4552-8564-91f07082af22" alt = "Ejemplo Captura pantalla" width= "600">  


***



~~~
function ageKarate(age) {
    if (age >18){
        console.log("clase Adultos");
        
    }else{
        console.log("Karate infantil")
    }
}
ageKarate (15);
~~~  
Esto es la estructura de un condicional básico. Vamos a utilizar el operador ternario para ver como podemos realizar este código en una sola frase dentro de una variable.  

~~~
let respuesta = age > 18 ? "clase Adulto" : "Karate infantil";

console.log(respuesta);
~~~  

Todo el código lo guardamos dentro de la variable y nos devuelve "karate infantil".  


<img src= "https://github.com/user-attachments/assets/9560d57e-a3db-4ea0-84cd-42b3df7d4ba2" alt = "Ejemplo Captura de pantalla" width = "400">  


***



 

 
  

# DECLARACIÓN DE FUNCIÓN O EXPRESIÓN DE FUNCIÓN 

 

<img src="https://github.com/user-attachments/assets/7d376d71-e051-4c46-83b7-55b37c8f5f4d" alt="Ejemplo Captura de pantalla" width="600">  



***

Las funciones en JavaScript reciben un tipo de valor y devuelven otro diferente. Este lenguaje de programación está basado en funciones y el hecho de como trabaja con ellas, las pasa de un lugar a otro, le hace diferente a otros lenguajes. Además la forma en la que trabaja con funciones hace que sea muy flexible.
Existen varias formas de usar las funciones en JavaScript. 
La **declaración de función** o la **expresión de función**.  

* Declaración de función  


Esta es la forma normal, standar de utilizar una función.  
La sintaxis es crear la función, ponerle un nombre y acabar con paréntesis () y luego siempre corchetes rizados {}. Dentro de ellos pondremos lo que quieres que nos devuelva esa función.  

~~~
function saludo(){
  return "Hola gente";
}
~~~  

* Expresión de función  

También llamadas funciones anónimas o funciones anónimas con nombres. El flujo de desarrollo es un poco diferente y hay diferencias entre las funciones de declaración y las funciones de expresión.
Una expresión de función es una función que se almacena dentro de una variable.  

~~~
var saludo2 = function () {
   return "Hola gente de nuevo";
};
~~~  

Dentro de la función entre paréntesis no nombramos nada. Aquí es donde aparece la parte anónima. Al final de todo el código siempre hay que poner ;.  

Tenemos las dos salidas a las dos funciones:  

~~~
console.log(saludo());
console.log(saludo2());
~~~  

Esto nos devuelve de la misma forma.
~~~
"Hola gente"
"Hola gente de nuevo" 
~~~  


Esto puede ser raro porque para qué necesitamos dos formas para hacer lo mismo.  

Vamos a ver otro ejemplo.  

~~~
var edad = 6;
   if (edad < 10) {
   var Merendola = function (){
   return "chuches para merendola";
  };
console.log(Merendola());
}
~~~  

Esto nos devolverá "chuches para merendola". Que es lo que estamos buscando. 
~~~
var edad = 6;
   if (edad < 10) {
   function Merendola2() {
     return "Bocadillos para merendola";
   }
}
console.log(Merendola2());
~~~  

Esto nos va a devolver "Bocadillos para merendola".


Pero las declaraciones de funciones no deben colocarse en bloque, (no deben estar dentro de las llaves{} como en un bloque condicional). Y es lo que hemos hecho. Generamos una función sobre la marcha y eso no es lo que se pretende que hagan las declaraciones de funciones, eso es para lo que está destinada una expresión de función.  

~~~
var edad = 6;
function Merendola2() {
if(edad <10) {
   return "bocadillos para merendola";
   }
}
console.log(Merendola2());
~~~  



Las expresiones de funciones son más modulares. Si necesitas algo para poder moverte o una función que necesites poder crear en cualquier punto, esa es la función para lo que se utilizan las expresiones. Mientras que una declaración de función es sólo cuando lo tienes fuera del bloque. En este último ejemplo la función está fuera del bloque, fuera del condicional. Esta es la manera correcta.  

# "THIS" PALABRA CLAVE EN JAVASCRIPT

Es una palabra muy especial. Entender _this_ es crucial para dominar JavaScript, especialmente al trabajar con objetos y programación orientada a objetos. El valor de esta palabra cambia siempre según el contexto en el que aparezca. Por este motivo es tan sumamente difícil darle un significado específico. Donde más se usa es dentro de objetos. 

En una función _this_ va a comportarse dependiendo de como se llame a la función. Se puede referir a lo que está haciendo esa función.  

En una función normal (las más usadas) en las que se tenga la propiedad de un objeto, _"this"_ va a hacer referencia a ese objeto. Respondería a la pregunta ¿de dónde debería obtener algún valor o dato?. 
Si tienes muchas funciones, métodos en una aplicación, llamar a __this__ va a hacer que te dé exactamente el objeto que quieres. Va a buscar exactamente lo que le pides. Si después de __this__ pones punto y colocas el nombre de la función o método, así consigues saber la instancia exacta a la que se refiere.  

Sino pondríamos __this__ sólo la función genérica, buscará por toda el código y verificará si hay una función con determinado nombre y sino hay devolverá "undefined". y no funcionará. 



Ejemplo básico de uso de this en JavaScript.
~~~

var persona = {
    nombre: "Ibai",
    edad: 11,
    saludo() {
        console.log(`Hola, mi nombre es ${this.nombre} y tengo ${this.edad} años.`);
    },
};

persona.saludo(); 

~~~  

  

El resultado que nos daría es "Hola, mi nombre es Ibai y tengo 11 años".

Cuando escribimos _"this"_ sabe que hace referencia al objeto del método que estemos usando.  

Definimos al objeto persona. Tiene tres propiedades "nombre" que es una cadena "Ibai", "edad" que es un número con valor 11 y "saludo" que es la función que va a usar _"this"_. 

Uso de _this_ en el método saludo:
En saludo usamos _this_ para acceder a las propiedades del objeto.
_this.nombre_ nos lleva a la propiedad nombre del objeto (persona)
_this.edad_ nos lleva a la propiedad edad del objeto (persona).
Si llamamos al método saludo: persona.saludo(); el valor de _this_ dentro del método se refiere al objeto que lo invoca, en este caso, persona.  

El resultado como ya hemos dicho es "Hola, mi nombre es Ibai y tengo 11 años".

~~~
function alert() { 
  console.log(this.edad + ' años'); 
}

var Objeto = {
  edad: 22,
  alert: alert
}

Objeto.alert();
~~~  

Nos daría como salida : 22 años.


Sencillamente, cuando llamas a una función usando el punto (.),_ this_ está implícitamente vinculado al objeto desde el que se llama a la función.
En este ejemplo, dado que alert es llamada desde Objeto, la palabra clave this está vinculada a Objeto.  Cuando llamamos a alert con Objeto.alert(), this.edad es 22, siendo  edad una propiedad de Objeto.  

¿Quién llama a la función? Esa es la pregunta clave. El valor de _this_ casi siempre depende del "punto" (.) que precede a la función cuando es llamada.


~~~
function alert() { 
  console.log(this.edad + ' años'); 
}

const Objeto = {
  edad: 22,
  alert: alert,
  anidarObj: {
    edad: 40,
    alert: alert
  }
}

Objeto.alert();   En este caso _`this`_ está vinculada a "Objeto". Nos da como salida 22 años
Objeto.anidarObj.alert();  En este otro caso _`this`_ está vinculada a `anidarObj`. Nos da como salida 40 años
~~~  


***  



<img src="https://github.com/user-attachments/assets/cb12c0d8-0a0e-431f-8911-ecadaed1ba9a" alt="Ejemplo Captura de pantalla" width="700">  



***  

![Captura de pantalla 2025-06-12 011633](https://github.com/user-attachments/assets/ce806fd8-2ced-4bfe-899c-f03c96a79938)  


***
