# Respuestas

1. Si deseo modificar el mensaje del método pitar al crear un objeto moto sin alterar la clase Auto, ¿qué debo agregarle al código? (Por ejemplo, al llamar el método pitar imprima: Las motos no pitan).

- se debe agregar un método pitar en la clase moto que sobreescriba el método pitar de la clase Auto.

2.Suponga que se agrega una nueva clase al código, class Motoneta, y esta hereda de la clase Moto, ¿evidencia algún problema? ¿Por qué?

- No hay problema, ya que la clase Motoneta hereda de la clase Moto, y la clase Moto hereda de la clase Auto, por lo que la clase Motoneta también hereda de la clase Auto.

3.Suponga que se definió el método:

```java
public void arrancar() {
System.out.println("Arrancando");
}
```

en la clase Moto, ¿es posible sobrescribir el método? ¿Por qué?

- sí es posible sobrescribir el método arrancar de la clase Moto, ya que el método arrancar de la clase Moto es público.

4.En la línea 13 de la clase moto, ¿Por qué puedo utilizar el método pitar?

- porque se hereda de la clase Auto.

5.Haciendo una pequeña modificación a la clase Auto y utilizando la variable num autos, sin modificar su modificador de acceso, ¿cómo puedo obtener el número de autos creados desde la clase ObjTaller5H?

- la variable es statica, por lo que se puede acceder a ella desde la clase ObjTaller5H con la siguiente instrucción: Autonum_autos.

6.En la línea 7 de la clase ObjTaller5H, ¿Por qué no puedo utilizar el método adelantar, si
este fue heredado?

- Es un método privado de la clase Auto, por lo que no se puede acceder a él desde la clase ObjTaller5H, no fue heredado.

7.En la línea 8, ¿por qué es posible utilizar el método arrancar si la clase Bus no lo define?

- porque la clase Bus hereda de la clase Auto.

8.En la línea 9 de la clase ObjTaller5H, ¿por qué no puedo utilizar el método pitar, si este fue heredado?

El método si puede ser utilizado.

9.En la línea 10 de la clase ObjTaller5H, ¿qué imprime el método getV elocidad()? ¿Por qué?

- imprime la velocidad de la clase Auto. Porque el método es heredado y no es sobreescrito.

10.Si quisiera obtener el valor de la placa de las clases Moto y Bus, además de su modelo y capacidad respectivamente, ¿Que debo agregar al código?

- Se puede refactorizar, moviendo los atributos placa, modelo y capacidad a la clase Auto, y creando los métodos get y set correspondientes.
