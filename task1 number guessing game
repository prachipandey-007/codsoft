//number guessing game
 
        import java.util.Scanner;
        import java.util.Random;
        public class task1{
        public static void main(String[] args){
        System.out.println("this is a number guessing game \nyou have 5 attempts to guess the correct number");
        System.out.println("with each wrong attempt you eill lose 20 points\nall the best!!!!!");
        int score=100;
        Random r = new Random();
        int number = r.nextInt(100);
        Scanner sc = new Scanner(System.in);
        System.out.println("enter a number of your choice:");
       
        for (int i = 1;i<6;i++){
             int guess = sc.nextInt();
            if (number==guess){
            System.out.println("you guessed the correct number");
            System.out.println("your score is;"+score);
            break;
              
        }
            else if(number>guess){
             System.out.println("the number you entered is less than the number\n take another guess");

        }
            else if(number<guess){
             System.out.println("the number you entered is greater than the number\n take another guess");
        }
        score-=20;
        

         if(i==5){
             System.out.println("you have run out of try\nBETTER LUCK NEXT TIME!!!");
        }
        
        }
       
        System.out.println("your score is"+score);

    }
}
