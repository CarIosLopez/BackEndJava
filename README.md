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
* Cuando creas una clase se hace por default un constructor llamado: **public void + "nombre de la clase"** que no se puede ver pero esta ahí.

  (img))
* Definición de un metodo, firma o signatura de un metodo, la palabra correcta es signatura del metodo.

  Nos dara a entender si hay un valor de retorno, cual es el nombre del metodo, cual es el numero, si tiene un tipo, si tiene un orden en los parametros.

  Esto nos ayudara a distinguir sin ambiguedad, tendremos 3 elementos que participan el la signatura del metodo:

  - Valor de retorno
  - Como se llama mi metodo
  - Cúal es el numero, tipo o parametros

    (img))
