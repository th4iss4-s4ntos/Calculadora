# Calculadora
Projeto desenvolvido em Java
public class Calculadora {

    private static Object JOptionPane;

    public static void main(String[] args) {
        System.out.println("Hello World!");
    
        System.out.println("Hello World and Fuck You!!!");
        //'sout' comando para aparecer o código a cima
        System.out.println("AAAAAAAAAAAAAAAAAAAAAAAh"); 
        // '\n' para quebrar no prinln
        System.out.println("I hate you \nand I still hate you");
        String nome;
        nome="Guilherme";
        System.out.println("By from "+nome);
        int a;
        a=1;
        int b;
        b= 1;
        int real;
        real=a+b;
        System.out.println("Deacordo com Newton 1+1=4 \nMas de acordo com o Filósofo Pitón é:"+ real +" Fim");
        System.out.println("Quem estava certo:");
        if (real==2){
            System.out.println("Pitòn");}
        else{
            System.out.println("Newton");}
       
        JOptionPane.showInputDialog(null, nome);
       
        String n;
        n = JOptionPane.showInputDialog(null,"Digite o nome Completo");
       
        JOptionPane.showMessageDialog(null,n);
       
        int num1;
        int num2;
       
        num1 = Integer.parseInt(JOptionPane.showInputDialog(null,"Digite o numero 1"));
        num2 = Integer.parseInt(JOptionPane.showInputDialog(null,"Digite o numero 2"));
       
        JOptionPane.showMessageDialog(null,num1 + num2);
      
}
