package aula19_Arrays;

import java.util.Scanner;

public class Exercicio31 {

	public static void main(String[] args) {
		/*
		 * Ler um vetor A com 20 elementos. Separar os elementos pares e impares de A
		 * utilizando apenas um vetor extra B. sugestão: no inicio do vetorB armazene os
		 * elementos pares de A e nas posições restantes do vetorB armazene os elementos
		 * de A que são impares.
		 */
		Scanner ler = new Scanner(System.in);
		int[] vetorA = new int[20];
		int[] vetorB = new int[vetorA.length];
		int posicaoB = 0;

		for (int x = 0; x < vetorA.length; x++) {
			System.out.println("Entre com o valor da posicao " + (x + 1));
			vetorA[x] = ler.nextInt();
		}
		for (int x = 0; x < vetorA.length; x++) {
			if (vetorA[x] % 2 == 0) {
				vetorB[posicaoB] = vetorA[x];
				posicaoB++;
			}
		}
		for (int x = 0; x < vetorA.length; x++) {
			if (vetorA[x] % 2 != 0) {
				vetorB[posicaoB] = vetorA[x];
				posicaoB++;
			}
		}
		System.out.println();
		System.out.print("VetorA = ");
		for (int x = 0; x < vetorA.length; x++) {
			System.out.print(vetorA[x] + " ");
		}
		System.out.println();
		System.out.print("VetorB = Pares Depois Impares ");
		for (int x = 0; x < posicaoB; x++) {
			System.out.print(vetorB[x] + " ");
		}
	}
}
