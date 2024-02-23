# EXPLICACION DE NUESTRO PROGRAMA PARA FABRICAR OBJETOS DE TRANSPORTE

***CREAMOS LAS CLASES QUE SERÁN LOS TRANSPORTES***

1. primero leemos el enunciado y nos pide que los objetos tienen que sert de tipo camion y bicicleta
2. creamos las clases camion y bicileta 
3. creamos la interfaz IComunTransporte en la que definimos los metodos que deben implementar las clases camion y bicicleta


**interfaz IComunTransporte**
aqui creamos los metodos que serán comunes a las clases que las implementen
1. el primer metodo calculará el coste en funcion del codigo postal
2. el segundo nos dará el tipo de embalaje en función del peso

**Clase Camion**

1. creamos los atributos estaticos que serán el tipo de embalaje
2. recordemos que las clases deben implementar la interfaz IComunTransporte y luego implementar los metodos de la interfaz
3. implementamos los metodos y los modificamos según nuestras necesidades

**Clase Bicicleta**

1. creamos los atributos estaticos que serán el tipo de embalaje
2. recordemos que las clases deben implementar la interfaz IComunTransporte y luego implementar los metodos de la interfaz
3. implementamos los metodos y los modificamos según nuestras necesidades


**Clase FactoryTransport**

1. creamos los atributos estaticos finales que, segun lo elegido en el metodo que vamos a describir luego, será un objeto de tipo camión o uno de tipo bicicleta
2. creamos el metodo getProducto que tiene un parametro en el que vamos a definir si queremos que nos cree un objeto de tipo camion o de tipo bicicleta
3. si no eligimos nada, nos dará un nulo

***Clase Main***

Aquí se ejecuta nuestro programa

1. primero creamos una variable que será de tipo interfaz, que será la interfaz IComunTransporte
2. esa variable será igual a la factoria y sus metodos
3. metemos el tipo que queremos por parametro para que fabrique un camion o una bicicleta
4. llamamos a los metodos y lo sacamos por pantalla para comprobar que funciona

**hacemos un javadoc**

realizamos un javadoc en el que explicamos paso a paso todo el procedimiento

***Objetivo del factory***

el objetivo es ni mas ni menos, una fabrica de objetos




