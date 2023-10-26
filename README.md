### Calculadora java netbeans
Pequeño ejemplo de la sintaxis basica de java 
n Java, puedes utilizar una variedad de funciones y clases para crear una calculadora. Las funciones y clases más comunes que se utilizan para implementar una calculadora incluyen:

    Operadores aritméticos: Java proporciona los operadores aritméticos estándar para realizar cálculos matemáticos, como suma (+), resta (-), multiplicación (*), división (/) y módulo (%).

    Clase Scanner: Para obtener entrada del usuario desde la consola o desde una interfaz gráfica, puedes usar la clase Scanner para leer números y operadores. Aquí hay un ejemplo básico de cómo utilizar Scanner:

import java.util.Scanner;

public class Calculadora {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Ingrese el primer número: ");
        double num1 = scanner.nextDouble();
        System.out.print("Ingrese el operador (+, -, *, /): ");
        String operador = scanner.next();
        System.out.print("Ingrese el segundo número: ");
        double num2 = scanner.nextDouble();
        scanner.close();
        
        // Realizar cálculos aquí según el operador
        // ...
    }
}


Clase JOptionPane: Si estás desarrollando una aplicación de interfaz gráfica, la clase JOptionPane de Swing es útil para mostrar cuadros de diálogo para la entrada y salida de datos.

Estructuras de control: Utiliza estructuras de control, como if, switch, para determinar qué operación realizar en función del operador ingresado.

Funciones personalizadas: Puedes definir tus propias funciones (métodos) para realizar operaciones matemáticas específicas. Por ejemplo, podrías definir un método para sumar dos números:

public static double sumar(double a, double b) {
    return a + b;
}
Y luego, llamar a este método en tu programa para realizar la suma.

Clase Math: La clase Math proporciona métodos estáticos para realizar operaciones matemáticas comunes, como raíz cuadrada, exponenciación, funciones trigonométricas, etc. Puedes utilizar estos métodos para realizar cálculos más complejos.
double raizCuadrada = Math.sqrt(numero);
double seno = Math.sin(angulo);


![Captura de pantalla 2023-10-26 121510](https://github.com/andresfelipeoq/calculadora-en-java-/assets/105876623/54469324-d11b-401e-9823-1deed2310b28)

