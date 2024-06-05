# M3C6
## Checkpoint_6
## ¿Para qué usamos Clases en Python?

    • Una  clase en Python es una estructura de progrmación que permite definir un conjunto de 
      métodos y atributos que describen un objeto o entidad.
      
    • Las clases son un concepto fundamental en la programación orientada a objetos. Las clases en Python 
      se pueden utilizar como plantillas con el fin de crear objetos que comparten métodos y atributos.
      
    • Los objetos creados a partir de una clase tiene las mismas propiedades y comportamientos definidos 
      por la clase, pero pueden tener valores diferentes para los atributos que se definen en la clase.
      
    • El cuerpo de la clase contiene definiciones de métodos y atributos, que pueden ser públicos o 
      privados según su acceso

		‘CLASS PERSON:
			DEF__INIT__(SELF, NOMBRE,EDAD):
				SELF.NOMBRE=NOMBRE
				SELF.EDAD=EDAD
				DEF SALUDAR(SELF):
				PRINT(“HOLA, MI NOMBRE ES”+SELF.NOMBRE)’

__Ventajas__

    • Reutilización de código: 
    • las clases pueden reutilizarse en diferentes partes del programa o en distintos programas, lo que ahorra tiempo y reduce 
      la duplicación de código.
    • Encapsulación: permiten ocultar la complejidad de un objeto y exponer solo una interfaz simple y fácil de usar para 
      interactuar con él.
    • Modularidad: pueden descomponer un programa en componentes más pequeños y manejables, lo que facilita el mantenimiento 
      y la solución de problemas.
    • Polimorfismo: ayudan a implementar el mismo conjunto de métodos con diferentes comportamientos para distintos tipos de objetos, 
      lo que permite una mayor flexibilidad y extensibilidad en el diseño de programas.
      
__Desventajas__

    • Sobrecarga de complejidad: las clases pueden agregar complejidad adicional a un programa y hacer que sea más difícil 
      de entender y depurar.
  
    • Uso innecesario: a veces, las clases se utilizan innecesariamente en situaciones en las que una función simple podría 
      haber hecho el trabajo de manera más eficiente.
      
__Atributos en las clases de Python__

    • Un atributo es una variable que se define dentro de una clase, la cual almacena datos que pertenecen a un objeto de esa clase. 
    
    • Los atributos se utilizan para representar características o propiedades de un objeto, como su estado actual, su identificador, 
      su tamaño, su color, etc.
    
    • Los atributos pueden ser de diferentes tipos de datos, como enteros, flotantes, cadenas, listas, diccionarios, entre otros. 
    
    • Además, los atributos pueden tener distintos niveles de visibilidad, que se especifican mediante los modificadores de acceso en
      la definición de la clase. 
    
    • Por defecto, los atributos son públicos en Python, lo que significa que puede accederse a ellos desde cualquier lugar del programa.
    
    • En la definición de una clase, los atributos se definen como variables que se inicializan en el método especial __init__. 
    
    • Por ejemplo, en la clase Persona que definimos anteriormente los atributos «nombre" y «edad» se definen de la siguiente manera:
    
    • «nombre» y «edad» son atributos públicos de la clase Persona, que se inicializan con los 	valores proporcionados al crear un objeto 
      de la clase. Para acceder a los atributos de un objeto de la clase, se  utiliza la notación de punto (.), 
      seguida del nombre del atributo. Por ejemplo, para acceder al atributo «nombre» de un 
      objeto «persona1» de la clase Persona, se utiliza el siguiente código:
      
      	'CLASS PERSON:
			DEF__INIT__(SELF, NOMBRE,EDAD):
				SELF.NOMBRE=NOMBRE
				SELF.EDAD=EDAD'
				
      



__Los tres tipos principales de atributos son:__

    •   Atributos públicos:  se puede acceder a ellos desde cualquier parte del programa, incluso desde fuera de la clase. 
	En Python, los atributos se consideran públicos por defecto, lo que significa que no se requiere ningún modificador 
 	de acceso para especificar que un atributo es público. 
  
	Para acceder a un atributo público, se utiliza la notación de punto (.) seguida del nombre del atributo.
 	Atributos privados: solo se puede acceder a ellos desde dentro de la clase en la que se definen. 

    •   Atributos privados se definen mediante el prefijo «__» seguido del nombre del atributo. 
	Por ejemplo, si se quiere definir un atributo privado llamado «saldo» en una clase llamada 	
 	CuentaBancaria, podemos hacerlo de la siguiente manera:
  
	"En este caso, «__saldo» es un atributo privado de la clase CuentaBancaria, que solo se 	
 	puede acceder a él desde dentro de la clase. Si se intenta acceder a este atributo desde fuera de la clase se producirá un error.

    •   Atributos protegidos: solo se puede acceder a ellos desde dentro de la clase en la que se definen y desde las clases 
    derivadas (heredadas) de esa clase.
    En Python, los atributos protegidos se definen mediante el prefijo "__" seguido del nombre del atributo. 
	Sin embargo, en Python no existe un verdadero modificador de acceso protegido como en otros lenguajes 
 	de programación orientados a objetos, por lo que el uso del prefijo ""
	es una convención para indicar que un atributo está protegido, pero aún es posible acceder a él desde fuera de la clase.



[Enlaces](https://blog.hubspot.es/website/clases-python)
[Enlaces](https://www.w3schools.com/python/python_classes.asp)



## ¿Qué método se ejecuta automáticamente cuando se crea una instancia de una clase?

    • Es un método especial también llamdo dunder, que se utiliza para iniciar una instancia de una clase.
      
    • Cuando se crea una instancia de una clase, el método __init__es llamado automáticamente por el intérprete de Python y se 
      utiliza para realizar cualquier inicialización que sea necesaria para la instancia.
      
    • Se usa para asignar valores iniciales a los atributos de una instancia de la clase. Los atributos son las variables 
      que pertenecen a una instancia particular de la clase. Al llamar al método __init__, podemos 	 
      establcer valores de estos atributos y configurar la instancia de la clase para su uso posterior.
      
    • Si se quiere crear una clase llamada Persona con dos atributos nombre y edad podriamos definir la clase de la siguiente manera 
		‘CLASE PERSONA:
			DEF__INIT__(SELF,NOMBRE,EDAD):SELF.NOMBRE=NOMBRE
			SELF.EDAD=EDAD’

    • En este ejemplo, el método __init__ toma dos parametros nombre y edad. Estos se utilzian para inicializar los atributos 
      nombre y edad de la instancia de la clase.
      
    • Al crear una instancia de la clase Persona, se debe proporcionar un valor para cada umo de los parámetros nombre y edad

			‘PERSONA1=PERSONA(“JUAN”,30)’


[Enlaces](https://blog.hubspot.es/website/clases-python)
[Enlaces](https://www.geeksforgeeks.org/__init__-in-python/)



## ¿Cuáles son los tres verbos de API? 

Los verbos más utilizados son los siguientes:

    • GET: se utiliza para recuperar o consultar, desde un recurso.

    • POST: creación de un recurso
    
    • PUT: modificación total de un recurso.
    
    • PATCH: modificación parcial de un recurso.
    
    • DELETE: eliminación de un recurso, sirve para un dato, como para un conjunto de datos
    

[Enlaces](https://blog.hubspot.es/website/que-es-api-rest)
[Enlaces](https://codigofacilito.com/articulos/verbos-http-rest)


## ¿Es MongoDB una base de datos SQL o NoSQL?


    • NoSQL viene de Not Only SQL, no solo SQL. Estos tipos de bases de datos surgen por una gran demanda de 
      bases de datos que puedan trabajar con datos masivos de forma más eficiente.
    
    • Las bases de datos NoSQL no utilizan ni tablas ni registros como harían las bases de datos relacionales 
      como SQL; no necesitan una estructura fija
    . 
    • Esto da más flexibilidad a la hora de diseñar el esquema y sus relaciones. Hay una gran variedad de bases 
     de datos NoSQL como MongoDB, Cassandra, CouchDB y muchos más. 
      


__¿Cómo se guardan los documentos en MongoDB?__

    • Los documentos de una base de datos MongoDB se almacenan utilizando el formato JSON o BSON. BSON es una 
      versión binaria de un archivo JSON. Son documentos compuestos por clave y valor. 
      
		“nombre”:”Jon”,
		“edad”:35
		“dirección”:
			{	“ciudad”: “Bilbao”
			},
			“aficiones”:[
				{“nombre”: “Fútbol”},
				{“nombre”: “Surf”}’






[Enlace](https://datademia.es/blog/que-es-mongodb)
[Enlace](https://www.w3schools.com/mongodb/)


## ¿Qué es una API? 

    • Las siglas para Application Programming Interface es un conjunto de funciones y procedimientos que permite integrar sistemas, 
      permitiendo que sus funcionalidades puedan ser reutilizadas por otras aplicaciones o software.
      
    • Sirve para intercambiar datos entre diferentes tipos de software y así utilizar procedimientos y desarrollar nuevas funcionalidades.


__5 Tipos de API__

__1. API pública__  las API públicas o abiertas__son interfaces que están disponibles para cualquier usuario.

    • Por ejemplo, existen bibliotecas de algunos lenguajes de programación que cuentan con una amplia gama de bibliotecas y 
      aplicaciones que son necesarias para hacer funcionar un software. 
    
    • Se puede emplear estas reglas o códigos sin restricciones y facilitar el proceso de diseño y desarrollo.
    
    • Para integrar una imagen o un video dentro de un blog online. Con la API adecuada se puede añadir el enlace y 
       hacer que aparezca en el sitio web.
    
      
__2. API privada las API privadas o cerradas__ son herramientas a las que únicamente pueden acceder los usuarios que 
     han sido autorizados para ello.

    • Estas aplicaciones generalmente están diseñadas para el funcionamiento de una empresa en particular, por lo que sirven
      para hacer llamadas a datos de un área, aplicar reglas definidas o establecer formatos preexistentes y propios de una organización. 
    
    • Estas API cuentan con gateways o puertas cerradas que solo permiten el acceso a quienes se identifican como 
      parte del grupo o usuarios.
      
      
__3. HTTP API las HTTP API o web API__ 

    • son interfaces diseñadas específicamente para usarse en el desarrollo de sitios web por medio del protocolo de 
      transferencia de hipertexto (HTTP). 
    
    • Al desarrollar un sitio, es necesario transferir información de una fuente a otra disponible en internet. 
      Estas API están optimizadas para ubicar, extraer o aplicar alguna regla o rutina dentro de una página 
      o en un servidor que funcione en la red.

__4. SOAP API las SOAP API__

    • API de protocolo simple de acceso a objetos consisten en una serie de pautas que permiten a un programa acceder 
      a información básica de otra ubicación. 
    
    • Estas API no proveen archivos o datos de otros repositorios. Solamente dan las indicaciones que regulan 
      la extracción e integración de estos elementos de manera segura. 

__5. RESTful API__

    • Las RESTful API o API de transferencia de estado representacional son interfaces que sirven para hacer 
      llamadas a un estilo específico de arquitectura de software basado en el contenido multimedia.
    
    • Las API de este tipo son excelentes para el diseño de plataformas más complejas, como las aplicaciones móviles, 
      que requieren la integración de tablas, imágenes y videos. Extraen la información solicitada y la 
      integran al software.
      

[Enlace](https://www.sydle.com/es/blog/api-6214f68876950e47761c40e7)
[Enlace](https://blog.hubspot.es/website/que-como-usar-api)





## ¿Qué es Postman?

    • Postman es una herramienta de desarrollo de API (interfaz de programación de aplicaciones) que ayuda a crear, 
      probar y modificar APIs. Casi cualquier funcionalidad que se pueda necesitar está encapsulada en 
      esta herramienta
      
    • Postman en sus inicios nace como una extensión que podía ser utilizada en el navegador Chrome de Google y 
      básicamente permitía realizar peticiones de una manera simple para testear APIs de tipo REST propias o de 
      terceros.
      
    • Gracias a los avances tecnológicos, Postman ha evolucionado y ha pasado de ser de una extensión a una 
      aplicación que dispone de herramientas nativas para diversos sistemas operativos como lo son Windows, Mac y 
      Linux.
      
    • Cuenta con una versión libre de pago.
      
__Utilidad y ventajas__

    • Testear colecciones o catálogos de APIs tanto para Frontend como para Backend.
    
    • Organizar en carpetas, funcionalidades y módulos los servicios web.
    
    • Permite gestionar el ciclo de vida (conceptualización y definición, desarrollo, monitoreo y mantenimiento) de una API.
    
    • Generar documentación de  APIs.
    
    • Trabajar con entornos (calidad, desarrollo, producción) y de este modo es posible compartir a través de un 
      entorno cloud la información.
       
    • Cuenta con una extensión para el navegador web Google Chrome.
    
    • Es posible agregar scripts (JavaScript) para añadir validaciones, automatizar y/o configurar pruebas.
    
    • Permite trabajar con colecciones, base de datos con las peticiones realizadas.



      
[Enlace](https://openwebinars.net/blog/que-es-postman/)
[Enlace](https://www.postman.com/)


## ¿Qué es el polimorfismo?

    • El polimorfismo permite que un objeto se comporte de manera diferente en distintos contextos.
    
    • En Python, el polimorfismo se implementa de manera natural gracias a la capacidad de las funciones y 
      métodos para aceptar argumentos de diferentes tipos. 
    
    • En el ejemplo dos clases diferentes casandra y amadeus utlicen los mismos nombres de método info e init 
      para proporcionar las respectivas cotizaciones de precios del producto
    
	__Ejemplo__
		‘class amadeus:
  
  			  def __init__(self, name, price):
       
    				self.name = name
	
				self.price = price
    
				def info(self):
    
    		print("This is product and amadeus class is invoked. The name is {self.name}. This costs {self.price} €.")’
      
		class casandra:
  
  		  def __init__(self, name, price):
      
    			self.name = name
       
			self.price = price
   
			def info(self):
   
    	print(f "This is product and casandra class is invoked. The name is {self.name}. This costs {self.price} €.")
     
	CASAN = casandra ("Iphone", 250)
 
	AMD = amadeus("Iphone", 400)
 
		for product1 in (CASAN AMD):
  
   		 product1.info()’

		<This is a product, and casandra class is invoked. The name is iPhone, and this costs 250 €.
  
		This is a product, and amadeus class is invoked. The name is iPhone, and this costs 400 €.>
  

    • El polimorfismo se puede definir como una condición que se presenta de muchas formas diferentes.
    
    • Un operador en Python ayuda a realizar tareas matemáticas y de programación de otro tipo.
    
    • Un método definido por el usuario son métodos que crea el usuario y se declara utilizando la palabra clave def con el nombre de la función.
    
    • El polimorfismo en Python ofrece varias cualidades , como es la reutilización de códigos escritos para diferentes clases y métodos.
    
    • El polimorfismo también se logra mediante la anulación de métodos en tiempo de ejecución y la sobrecarga de métodos en tiempo de compilación.


[Enlaces](https://blog.hubspot.es/website/clases-python)
[Enlace](https://ellibrodepython.com/polimorfismo-en-programacion)
[Enlace](https://www.guru99.com/es/polymorphism-in-python.html)

## ¿Qué es un método dunder?

    • Métodos especiales, también conocidos como métodos Dunder o métodos Mágicos. Se utilizan para emular 
     el comportamiento de las funciones integradas.
    
    • Sus nombres empiezan y terminan en __ (doble guión bajo). Por ejemplo init.
    
    • Normalmente estos métodos no son invocados directamente. Por ejemplo cuando se hace una simple 
      suma 2 + 2 se está invocando al método __add__ internamente.
    
          __Métodos de iniciación y constructores__
		__init__ Inicializa un objeto
		Crea un nuevo objeto cuando se llama a la instancia de una clase.

			‘class Car(object):
    				def __init__(self):
  				      ...
    			def __repr__(self):
       				 …’

			__new__ Crea un objeto
   
			__del__ Elimina un objeto


[Enlace](https://geekflare.com/es/magic-methods-in-python/)
[Enlace](https://www.netinetidesign.com/post/metodos-especiales-en-python/)


## ¿Qué es un decorador de python?

    • Los decoradores son funciones de Python que permiten envolver otra función como entrada y modificar su comportamiento 
      sin alterar el código de la función envuelta.
    
    • Se utilizan para extender el comportamiento de un objeto en particular, como una clase, método o función. 
    
    • Sintaxis de los Decoradores en Python. La sintaxis de un decorador en Python es bastante simple. Comienza con la palabra clave 'def' 
      para definir una función, seguida de una (@) y el nombre del decorador. Después de eso, se puede añadir cualquier argumento necesario y 
      luego pasar la función de destino como argumento.

__Los decoradores de clase__

    • permiten extender el comportamiento de una clase sin cambiar el código fuente original;  
      Toman una clase como entrada y devuelven una nueva clase con un comportamiento modificado o 
      ampliado. 
      
    • Los decoradores de clase pueden utilizarse para varios propósitos, como añadir o modificar atributos, métodos o propiedades de la clase.
    
		‘def class_decorator(cls):

    			class NewClass(cls):

    			def new_method(self):

   			 print("This is a new method added by the decorator")

			return NewClass

			@class_decorator

		class MyClass:

   		 def original_method(self):

   		 print("This is the original method")

		obj = MyClass()

		obj.original_method()

		obj.new_method()’‘

__Decoradores con argumentos__

    • Los decoradores con argumentos proporcionan una flexibilidad adicional a la hora de modificar o ampliar el comportamiento de funciones o clases. 
    
    • Estos decoradores aceptan argumentos y devuelven otra función , que a su vez toma la función o clase como entrada y 
      devuelve la función o clase modificada.

       Ejemplo:

	‘def class_decorator(cls):

  		  class NewClass(cls):

    		def new_method(self):

    	print("This is a new method added by the decorator")

		return NewClass

		@class_decorator

		class MyClass:

    		def original_method(self):

    print("This is the original method")

	obj = MyClass()

		obj.original_method()

		obj.new_method()’


[Enlace](https://blog.hubspot.com/website/decorators-in-python)
[Enlace](https://realpython.com/primer-on-python-decorators/)
[Enlace](https://www.ionos.com/digitalguide/websites/web-development/python-decorators/)

