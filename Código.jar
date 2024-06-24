import javax.swing.JOptionPane;

public class GeradorTabuada {
    public static void main(String[] args) {
        // Solicitar um número ao usuário usando JOptionPane
        String numeroInput = JOptionPane.showInputDialog(null, "Digite um número para gerar a tabuada:");
        int numero = Integer.parseInt(numeroInput);

        // Gerar e exibir a tabuada utilizando um loop for
        JOptionPane.showMessageDialog(null, "Tabuada do " + numero + ":\n" + gerarTabuada(numero));
    }

    // Método para gerar a tabuada de um número
    public static String gerarTabuada(int numero) {
        StringBuilder tabuada = new StringBuilder();
        for (int i = 1; i <= 10; i++) {
            int resultado = numero * i;
            tabuada.append(numero).append(" x ").append(i).append(" = ").append(resultado).append("\n");
        }
        return tabuada.toString();
    }
}
