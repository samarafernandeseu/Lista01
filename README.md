# Lista01
Lista de exercícios básicos em Java — Parte 1
///1. Escreva um programa que, com base em uma temperatura em graus celsius, a converta e exiba em Kelvin (K), Réaumur (Re), Rankine (Ra) e Fahrenheit (F), seguindo as fórmulas: F = C * 1.8 + 32; K = C + 273.15; Re = C * 0.8; Ra = C * 1.8 + 32 + 459.67///

import java.util.Scanner;

public class Lista01 {
    public static void main(String[] args) {
        double C, K, F, Re, Ra;
        System.out.println("informe o valor de C: (2.43)");
        
        Scanner sc = new Scanner(System.in);
        C = Double.parseDouble(sc.next());

        F = C * 1.8 + 32;
        K = C + 273.15;
        Ra = C * 1.8 + 32 + 459.67;
        Re = C * 0.8;

        System.out.println("A temperatura em Fahrenheit é: " + F);
        System.out.println("A temperatura em Kelvin é: " + K);
        System.out.println("A temperatura em Reaumur é: " + Ra);
        System.out.println("A temperatura em Rankine é: " + Re);
    }

}
