# soletra
Programa pega uma palavra e imprime letra a letra.

package controle;

import javax.swing.JOptionPane;

public class Exercicio8Soletra {

	public static void main(String[] args) {

		String entrada = JOptionPane.showInputDialog("Entre com a palavra:");

		for(int mudaletra = 0; mudaletra < entrada.length(); mudaletra ++) {
			System.out.println(entrada.charAt(mudaletra));
		}

	}

}
