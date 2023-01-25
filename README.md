# ejercicio-3
solucion ejercicio 3 openBootcamp

Crear una función con tres parámetros que sean números que se suman entre sí.
Llamar a la función en el main y darle valores

public class ejercicio1{

    public static void main(String[] args){
        int resultado = suma(1,2,3);
        System.out.println("resultado: "+resultado);
    }


    public static int suma(int num1, int num2, int num3 ){
        return num1+num2+num3;
    }

}


Crear una clase coche.

Dentro de la clase coche, una variable numérica que almacene el número de puertas que tiene.

Una función que incremente el número de puertas que tiene el coche.

Crear un objeto miCoche en el main y añadirle una puerta.

Mostrar el número de puertas que tiene el objeto.

public class coche{
    public int numPuertas =4;

    public void incrementarPuertas(){
        this.numPuertas++;
    }

    public static void main (String[]args){
        coche miCoche = new coche();
        System.out.println("Resultado: "+ miCoche.numPuertas);

    }
}
