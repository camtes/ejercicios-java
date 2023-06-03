# Ejercicios-java

```
Recuerda que para compilar y ejecutar los archivos deberás de hacerlo mediante los comandos:

javac -d . *.java
java package_name.class

ejemplo (package ejercicio1):
javac -d . Principal.java
java ejercicio1.Principal
```

## Ejercicio 1

Crea una clase llamada Cuenta que tendrá los siguientes atributos: titular y cantidad (puede tener decimales).

El titular será obligatorio y la cantidad es opcional. Crea dos constructores que cumpla lo anterior.

Crea sus métodos get, set y toString.

Tendrá dos métodos especiales:
- [ ] Ingresar(double cantidad): se ingresa una cantidad a la cuenta, si la cantidad introducida es negativa, no se hará nada.

- [ ] Retirar(double cantidad): se retira una cantidad a la cuenta, si restando la cantidad actual a la que nos pasan es negativa, la cantidad de la cuenta pasa a ser 0.

## Ejercicio 2

Haz una clase llamada Persona que siga las siguientes condiciones:

Sus atributos son: nombre, edad, DNI, sexo (H hombre, M mujer), peso y altura. No queremos que se accedan directamente a ellos. Piensa que modificador de acceso es el más adecuado, también su tipo. Si quieres añadir algún atributo puedes hacerlo.

Se implantaran varios constructores:

- [ ] Un constructor por defecto.
- [ ] Un constructor con el nombre, edad y sexo, el resto por defecto.
- [ ] Un constructor con todos los atributos como parámetro.

Los métodos que se implementaran son:

- [ ] calcularIMC(): calculara si la persona esta en su peso ideal (peso en kg/(altura^2  en m)), si esta fórmula devuelve un valor menor que 20, la función devuelve un -1, si devuelve un número entre 20 y 25 (incluidos), significa que esta por debajo de su peso ideal la función devuelve un 0  y si devuelve un valor mayor que 25 significa que tiene sobrepeso, la función devuelve un 1.
- [ ] esMayorDeEdad(): indica si es mayor de edad, devuelve un booleano.
- [ ] toString(): devuelve toda la información del objeto.
- [ ] Métodos set de cada parámetro, excepto de DNI.

Ahora, crea una clase ejecutable que haga lo siguiente:
- [ ] Pide por teclado el nombre, la edad, sexo, peso y altura.
- [ ] Crea 3 objetos de la clase anterior, el primer objeto obtendrá las anteriores variables pedidas por teclado, el segundo objeto obtendrá todos los anteriores menos el peso y la altura y el último por defecto, para este último utiliza los métodos set para darle a los atributos un valor.
- [ ] Para cada objeto, deberá comprobar si esta en su peso ideal, tiene sobrepeso o por debajo de su peso ideal con un mensaje.
- [ ] Indicar para cada objeto si es mayor de edad.
- [ ] Por último, mostrar la información de cada objeto.

Puedes usar métodos en la clase ejecutable, para que os sea mas fácil.
