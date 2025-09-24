import java.util.Scanner;
import java.util.Random;

public class ReceitasInterativas {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        Random random = new Random();

        String[][] receitas = {
            {
                "Macarrão alho e óleo", 
                "Macarrão, alho, azeite, sal, cheiro-verde",
                "1. Cozinhe o macarrão até ficar 'al dente'.\n" +
                "2. Em uma frigideira, doure o alho fatiado no azeite.\n" +
                "3. Misture o macarrão escorrido com o alho e azeite, acerte o sal e sirva com cheiro-verde."
            },
            {
                "Bolo de cenoura", 
                "Cenoura, ovos, farinha, açúcar, fermento",
                "1. Bata no liquidificador a cenoura, os ovos e o óleo.\n" +
                "2. Misture o líquido com os ingredientes secos (açúcar, farinha, fermento).\n" +
                "3. Asse em forno médio (180°C) por aproximadamente 40 minutos."
            },
            {
                "Arroz de forno", 
                "Arroz cozido, presunto, queijo, creme de leite, milho",
                "1. Em uma travessa, misture todos os ingredientes, exceto metade do queijo.\n" +
                "2. Cubra com o queijo restante.\n" +
                "3. Leve ao forno pré-aquecido a 200°C por 15 minutos para gratinar."
            },
            {
                "Panqueca de frango", 
                "Frango desfiado, massa de panqueca, molho de tomate, queijo",
                "1. Prepare os discos de panqueca na frigideira.\n" +
                "2. Recheie cada disco com o frango desfiado e enrole.\n" +
                "3. Coloque em uma travessa, cubra com molho de tomate e queijo, e leve ao forno para derreter."
            },
            {
                "Omelete simples", 
                "Ovos, sal, queijo, presunto, tomate",
                "1. Bata os ovos com uma pitada de sal.\n" +
                "2. Despeje em uma frigideira quente e, quando começar a firmar, adicione o recheio.\n" +
                "3. Dobre ao meio e sirva imediatamente."
            }
        };

        int opcao;
        do {
            System.out.println("\n Bem-vindo ao Gerador de Receitas!");
            System.out.println("O que você deseja fazer?");
            System.out.println("1 - Ver uma receita aleatória");
            System.out.println("0 - Sair");
            System.out.print(" Digite sua escolha: ");
            opcao = scanner.nextInt();

            if (opcao == 1) {
                int indice = random.nextInt(receitas.length);
                System.out.println("\n--- RECEITA DO DIA ---");
                System.out.println(" Receita escolhida: " + receitas[indice][0]);
                System.out.println(" Ingredientes: " + receitas[indice][1]);
                
                // MUDANÇA 2: Adicionamos esta linha para imprimir o modo de preparo.
                System.out.println(" Modo de Preparo:\n" + receitas[indice][2]);
                System.out.println("----------------------");

            } else if (opcao != 0) {
                System.out.println(" Opção inválida, tente novamente!");
            }

        } while (opcao != 0);

        System.out.println("\n Obrigado por usar o Gerador de Receitas! Bom apetite!");
        scanner.close();
    }
}
