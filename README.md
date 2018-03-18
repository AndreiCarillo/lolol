import java.util.Scanner;
public class AspirantesHD {
	public static void main(String[] args) {
		Scanner scan = new Scanner (System.in);
		String Nombre;
		int Edad, Genero, Carrera, Respuesta;
		int C1=0, C2=0,C3=0,C4=0,C5=0,C6=0,C7=0,C8=0,C9=0,C10=0,C11=0;
		for (int i= 1; i<=10; i++){
		System.out.println("Escribe tu Nombre: ");
		Nombre = scan.next();
		System.out.println("Si la edad es menor a 18. Presione la tecla '7'");
		System.out.println("Si la edad esta entre los 18 y los 20. Presione la tecla '8'");
		System.out.println("Si la edad es mayor a  20. Presione la tecla '9'");
		System.out.println("Escribe tu Edad: ");
		Edad = scan.nextInt();
		System.out.println("Si es hombre. Presione la tecla '1' ");
		System.out.println("Si es mujer . Presione la tecla '2' ");
		System.out.println("Escribe tu genero: ");
		Genero = scan.nextInt();
		System.out.println("Si la carrera a elegir es Ingenieria en Sistemas Computacionales . Presione la tecla '3' ");
		System.out.println("Si la carrera a elegir es Ingenieria en tecnologias de la informacion y comunicacion. Presione la tecla '4' ");
		System.out.println("Selecciona la carrera a la cual deseas ir: ");
		Carrera = scan.nextInt();
		System.out.println("Si  es un SI. Presione la tecla '5'");
		System.out.println("Si es NO. Presione la tecla '6'");
		System.out.println("¿Te gustan las matemáticas?: ");
		Respuesta = scan.nextInt();
		if ((Genero==1)&&(Carrera==3)){
			C1= C1 + 1;
		}
		if ((Genero==1)&&(Carrera==4)){
			C2 = C2 + 1;
		}
		if ((Genero==2)&&(Carrera==3)){
			C3 = C3 + 1;
		}
		if ((Genero==2)&&(Carrera==4)){
			C4 = C4 + 1;
		}
		if ((Genero==1)&&(Carrera==3)&&(Respuesta==5)){
			C5 = C5 + 1;
		}
		if ((Genero==1)&&(Carrera==4)&&(Respuesta==5)){
			C6 = C6 + 1;
		}
		if ((Genero==2)&&(Carrera==3)&&(Respuesta==5)){
			C7 = C7 + 1;
		}
		if ((Genero==2)&&(Carrera==4)&&(Respuesta==5)){
			C8 = C8 + 1;
		}
		if ((Edad==7)&&(Respuesta==6)){
			C9 = C9 + 1;
		}
		if ((Edad==8)&&(Respuesta==6)){
			C10 = C10 + 1;
		}
		if ((Edad==9)&&(Respuesta==6)){
			C11 = C11 + 1;
		}
		}
		System.out.println("El numero de Hombres que desea Entrar a Ingenieria en Sistemas Computacionales es de: "+C1);
		System.out.println("El numero de Mujeres que desea Entrar a Ingenieria en Sistemas Computacionales es de: "+C3);
		System.out.println("El numero de Hombres que desea Entrar a Ingenieria en tecnologias de la informacion y comunicacion es de: "+C2);
		System.out.println("El numero de Mujeres que desea Entrar a Ingenieria en tecnologias de la informacion y comunicacion es de: "+C4);
		
		System.out.println("El numero de Hombres de Ingenieria en Sistemas ComputacionalesISIC y que les gustan la Matematicas es de: "+C5);
		System.out.println("El numero de Mujeres de Ingenieria en Sistemas Computacionales y que les gustan la Matematicas es de: "+C7);
		System.out.println("El numero de Hombres de Ingenieria en tecnologias de la informacion y comunicacion y que les gustan la Matematicas es de: "+C6);
		System.out.println("El numero de Mujeres de Ingenieria en tecnologias de la informacion y comunicacion y que les gustan la Matematicas es de: "+C8);
		
		System.out.println("El numero de Aspirantes Menores de 18 años y que no les gustan las Matemáticas es de: "+C9);
		System.out.println("El numero de Aspirantes Entre 18 y 20 años y que no les gustan las Matemáticas es de:"+C10);
		System.out.println("El numero de Aspirantes Mayores de 20 años y que no les gustan las Matemáticas es de: "+C11);			
	}

}
