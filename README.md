# ExamenIngreso
Responder las siguientes preguntas:
1. ¿C# permite herencia múltiple?
2. ¿Cuándo utilizaría una Clase Abstracta en lugar de una Interfaz? Ejemplifique.
3. ¿Qué implica una relación de Generalización entre dos clases?
4. ¿Qué implica una relación de Implementación entre una clase y una interfaz?
5. ¿Qué diferencia hay entre la relación de Composición y la Agregación?
6. Indique V o F según corresponda. Diferencia entre Asociación y Agregación:
a. Una diferencia es que la segunda indica la relación entre un “todo” y
sus “partes”, mientras que en la primera los objetos están al mismo
nivel contextual.
b. Una diferencia es que la Agregación es de cardinalidad 1 a muchos
mientras que la Asociación es de 1 a 1.
c. Una diferencia es que, en la Agregación, la vida o existencia de los
objetos relacionados está fuertemente ligada, es decir que si “muere”
el objeto contenedor también morirán las “partes”, en cambio en la
Asociación los objetos viven y existen independientemente de la
relación

1- C# no permite la herencia múltiple. Se pueden implementar varias interfaces pero no clases
2- Las clases abstractas se pueden implementar una única vez debido a que se trabajo únicamente con herencia simple, mientras que una clase puede tener múltiples tipos, múltiples interfaces.
Lo implementaría en una clase que realice más de una acción, ya que las interfaces son una especie de "contrato"

3- La relación de Generalización entre dos clases implica que la clase Padre se considera como Generalización de la clase Hija.
Se podría también denominar relación de Herencia.

4- Una relación de Implementación entre una clase y una interfaz implica que implementa todos sus métodos

5- La Agregación es un tipo de asociación que indica que una clase es parte de otra clase. Los componentes pueden ser compartidos por varios compuestos. La destrucción del compuesto no conlleva la destrucción de los componentes.
En la Composición, la vida de la clase contenida debe coincidir con la vida de la clase contenedor. Los componentes no pueden ser compartidos por varios objetos compuestos. La destrucción del objeto conlleva a la destrucción de los componentes.

6-  a: V
    b: V
    c: V Hace referencia a la Composición que es un tipo fuerte de Agregación
