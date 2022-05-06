##Poligonos Regulares Simples 

Na geometria Euclidiana, um polígono regular é um polígono em que todos os ângulos são iguais e todos os lados tem o mesmo comprimento. Um polígono simples é aquele cujos segmentos de reta não se interceptam.
Você deve escrever um programa que, dados o número e o comprimento dos lados de um polígono regular, mostre seu perímetro.


##Solução

import java.util.Scanner;

public class Main {
  public static void main(String[] args) {
    Scanner scan = new Scanner(System.in);
    String N = scan.next(); //número de lados 
    String L = scan.next(); // comprimento de cada lado 
//TODO: Complete os espaços em branco com uma possível solução para o desafio
    int P = Integer.parseInt(N) * Integer.parseInt(L); // calculo do comprimento do poligono 
    
    System.out.println( P    );
  }
}