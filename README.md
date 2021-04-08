# MedirIMC

public class ProjectIMC{

    import java.text.DecimalFormat;

public static void main(String []args){

    //Variáveis 
    double  peso , imc , altura;

    //Objetos
    Scanner teclado = new Scanner (System.in);
    DecimalFormat formatador = new DecimalFormat("#0.00");
    System.out.println("Cálculo do IMC ");

    //Entrada
    system.out.print ("Informe o seu peso");
    peso  = teclado .nextDouble ();

    system.out.print("Informe sua altura ")
    peso = teclado.nextDouble ();

    //Processamento

    imc  = peso /  (altura * altura );

    // Saída 
System.out .println ("IMC :"+ formatador .format (imc));
teclado.close ();

//Classificação verificar as condições do IMC.

if (imc < 18.5 >){
  system.out.println("Abaixo do peso! ");
}else if (imc < 25 >){
  system.out.println(" Peso ideal! ");
}else if (imc < 30 >){
  system.out.println("Levemente acima do peso! ")
}else if (imc < 35>){
  system.out.println("Obesidade grau I ! ");
}else if (imc < 40 >){
  system.out.println("Obesidade grau II ! ");
}else if (imc < 45 >){
  system.out.println("Obesidade grau III ! ");
}else{
    system.out.println("Procurar um médico ! ");

}








}

}



 
