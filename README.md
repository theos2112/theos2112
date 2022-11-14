-package parcial3

mport java.util.Scanner;

public class parcial3
{
    public static void sumaPro(String[] args) 
    {
        Scanner sumar=new Scanner(source:System.in);//importacion Scanner para recibir datos por teclado
        int Suma=0;//declaro la variable suma
        for(int i=0;<5;i++)//ciclo for hace que la operacion se repita
        {
            System.out.println("ingreso valor del pro:");//solicitud de valores
            int numero=sumar.nextInt();//la variable numero almacena los datos
            suma=suma+numero;// se suman los datos
            System.out.println("el valor total es"+suma); //se imprime el valor
        }
    }  
    public static void multiplicacionPro(String[] args)
    {
        Scanner multiplicar=new Scanner(source:System.in);//importacion Scanner para recibir datos por teclado
        int multiplicar=0;//declaro la variable multiplicar
        for(int i=0;<5;i++)//ciclo for hace que la operacion se repita
        {
            System.out.println("ingreso valor del pro:");//solicitud de valores
            int numero1=multiplicar.nextInt();//la variable numero almacena los datos
            multiplicar=multiplicar*numero1;// se suman los datos
            System.out.println("el valor total es"+multiplicar); //se imprime el valor
        }
    }
    public static void promediarPro(String[] args)
    {
        Scanner promediar=new Scanner(source:System.in);//importacion Scanner para recibir datos por teclado
        int promedio;//se declara el promedio
        int p1,p2,p3,p4,p5; // se declaran variables para almecenar
        System.out.println("ingreso valor del pro:");// se solicita vallores
        p1=promediar.nextInt();//se almacenan datos
        System.out.println("ingreso valor del pro:");// se solicita vallores
        p2=promediar.nextInt();//se almacenan datos
        System.out.println("ingreso valor del pro:");// se solicita vallores
        p3=promediar.nextInt();//se almacenan datos
        System.out.println("ingreso valor del pro:");// se solicita vallores
        p4=promediar.nextInt();//se almacenan datos
        System.out.println("ingreso valor del pro:");// se solicita vallores
        p5=promediar.nextInt();//se almacenan datos

        promedio = ((p1+p2+p3+p4+p5)/5);//realizo la operacion
        System.out.println("el valor total es"+promedio); //se imprime el valor
    }
}
