import javax.swing.JOptionPane;


public class somatoria {
    public static void main(String args[]) {
        double soma=0;
        double n1;
        int i;

        for(i=1; i<=5; i++) {
            n1 = Double.parseDouble(JOptionPane.showInputDialog("Digite um numero"));
            soma = soma + n1; //Acumulador
        }
        JOptionPane.showMessageDialog(null, "A soma dos numeros e: " + soma);
    }
}
