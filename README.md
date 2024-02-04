import java.util.Scanner;
import java.util.Random;
public class Lab10 {
    public static void main(String[] args) {

        Random r = new Random();
        Scanner input = new Scanner(System.in);

        int ranks = r.nextInt(13);
        int suits = r.nextInt(4);

        System.out.println("Do you want to play the game of cards? (Y/N): ");
        String choice = input.next();

        if(choice == "Y")
        {
            System.out.println("The card you picked is: ");
            switch(ranks)
            {
                case 1:
                    System.out.println("Ace");
                    break;

                case 2:
                    System.out.println("2");
                    break;

                case 3:
                    System.out.println("3");
                    break;

                case 4:
                    System.out.println("4");
                    break;

                case 5:
                    System.out.println("5");
                    break;

                case 6:
                    System.out.println("6");
                    break;

                case 7:
                    System.out.println("7");
                    break;

                case 8:
                    System.out.println("8");
                    break;

                case 9:
                    System.out.println("9");
                    break;

                case 10:
                    System.out.println("10");
                    break;

                case 11:
                    System.out.println("Jack");
                    break;

                case 12:
                    System.out.println("Queen");
                    break;

                case 13:
                    System.out.println("King");
                    break;
            }
            System.out.println(" of ");
            switch(suits)
            {
                case 1:
                    System.out.println("Clubs");
                    break;

                case 2:
                    System.out.println("Diamonds");
                    break;

                case 3:
                    System.out.println("Hearts");
                    break;

                case 4:
                    System.out.println("Spades");
                    break;
            }
        }
    }
}
