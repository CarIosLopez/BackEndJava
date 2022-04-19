# Notes C1 - POO

*Este apartado son tips, consejos y notas que menciona* **Fernanda Ochoa** *durante sus clases, no estan escritas tal cual lo dice, he tratado de parafrasear y reodenar sus palabras para poder entenderlo, espero que les ayude.*

Viñetas = tips, consejos

Solo texto = Mi aporte


---


* Aquí lo voy a dejar public int, es bueno saber que tambien existe **private int que se puede usar detro del mismo paquete y protected se puede se puede usar para todo el paquete y public de mas paquetes,** pero lo vamos a dejar public porque manejare paquetes, ya que no es lo mismo lo que se ve en el paquete a nivel paquete a lo que se ve a nivel "hello" ya que unos estan empaquetados y los otros estan fuera.

![](https://github.com/CarIosLopez/POO/blob/main/Notes/Images/public%20int.png)


* No es buena practica escribir "ñ".
* Si son del mismo tipo de dato, te ahorras una linea de codigo, por lo tanto no escribas 2 veces "public int, private int, private o public double" es innecesario.
* Las variables, clases y funciones apareceran en gris hasta que sean utlizadas.

Una manera en la que yo veo una similitud en la función de set es que funciona parecido a un input ya que le pides al usuario que asigne un dato, el set lo que hace es eso e indicarle al programa que los tiene que agregar a otra "hoja" donde se van a usar esos dichos datos

* El detalle esta si no validas el dato que ingresa el usuario o no ingresas alguna validación de algún tipo, lo único que vas a lograr es que tu programa truene cuando ingresen un dato que no deseas como una letra o cualquier cosa que no sea el dato que deseas. Es muy común este tipo de definiciones.
* Cuando pones el tipo de dato tienes que especificar forzosamente un **return** porque si tienes un dato de entrada que tiene que dar algo de salida.
* Cuando pones un **void** no es necesario que te regrese datos
* Una clase de Java tiene **campos, metodos, constructores, bloques**, que viene siendo todo un conjunto y **clases anidadas a interfaces**, puede que no tengamos todas estas caracteristicas pero siempre habrá campos y metodos
* Cuando creas una clase se hace por default un constructor llamado: **public void + &#34;nombre de la clase&#34;** que no se puede ver pero esta ahí, son como los 0 cuando despejas una ecuación, estan ahí pero no es necesario que lo pongas, sin embargo es importante que sepas el porque

  (img))
* **Definición de un metodo, firma o signatura de un metodo, la palabra correcta es signatura del metodo.**

  Nos dara a entender si hay un valor de retorno, cual es el nombre del metodo, cual es el numero, si tiene un tipo, si tiene un orden en los parametros.

  Esto nos ayudara a distinguir sin ambiguedad, tendremos 3 elementos que participan el la signatura del metodo:

  - Valor de retorno
  - Como se llama mi metodo
  - Cúal es el numero, tipo o parametros

    (img))
* **This** se usa para redifinir variables
* Cuando utilizas booleanos, muchos creen que en **else** forzosamente tienes que escribir algo o poner los corchetes pero cuando no se trata de una condición compuesta, no lo amerita, mientras sea una condición simple de un si y no, te puedes dar el lujo de no ponerlos.
* Acostumbren a escribir por tipos de datos, si yo tengo enteros, primero defino los enteros.
* Coloca el tipo de dato en la primera linea de codigo.
* Esto es un pojo, una clase pura, dentro de esta clase se permite y es unico metodo que se permite a manera de control, nos permitira entender como va a funcionar, en una clase pura esto es todo lo que debe contener.

  (pojo)
* En los pojos solo defines el metodo, si quieres sumar, restar, condicionar si escribe una cosa y otra, etc, lo haces en otra parte.
* Metodo de control para saber que fue lo que sucedio:
* Cuando tienes una clase principal y en ella puedes programar, hacer lo que quieras, nunca debe estar esta en la misma clase donde defines el objeto, porque esta ultima es para definir y main ejecutar todo el programa, por lo que tus definiciones no tienen que estar ahí.
* Cuando una clase, una cosa o un metodo en la que estamos trabajando hace una sola cosa se dice que es **"cohesivo"**, **si es capaz de hacer una sola cosa y la hace bien.**

  Por ejemplo nuetra clase para definir, define un objeto y modelamos un objeto que se llama bicicleta y lo estamos **encapsulando** en una sola cosa, porque **es** **cohesivo, su función es definir.**
* Que quiere decir que las clases estan relacionadas, pero no depende su funcionamiento uno del otro, quiere decir que tienen un bajo acoplamiento, cuando algo no este acoplado es porque esta separado, cuando esta acomplado es porque esta amalgamado, cuando tienes un bajo acomplamiento, que es decir que su unica relación son los objetos que se tienen, estamos hablando de que es un codigo bien hecho.
* Un codigo bien hecho es aquel que **tiene bajo acomplamiento y alta cohesión.**
* ! = diferente de o un no

  Esto se leería cómo: "Si el color no esta vacio"

  (img !)

  ---
* PSVM -> Clase estatica que no regresa nada y se llama main, es la clase principal que va a recibir lo que escribamos dentro de ella
* En esta parte vamos a conectar Bicicleta, que es el nombre de nuestra clase con con nuestro main o clase principal.

  Recuerda que debes escribir el nombre de tu referencia exactamente igual que el nombre de tu clase.

  De aqui tu puedes crear diferentes objetos con diferentes caractersticas porque ya tienes modelado en otra clase.

  (nuevo objeto)
* Recuerdas que habíamos mencionado al constructor **public void + "nombre de la clase"** y que reiteramos que este no es una clase o un objeto, es momento que sepas su funcionalidad.

  Lo que hacemos a continuación en nuestra clase main es utilizar el constructor por omisión que viene siendo el mismo constructor que mencionamos antes y por medio de los parentesis que ves aquí:

  ```
      Bicicleta biciMountain = new Bicicleta();
  ```

  se encargará de inicializar, ya que en una clase de Java primero los declaras y luego los inicializas.

---



---

---
