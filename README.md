# sayinin-rakamlarini-toplar
Bir tam sayının basamak sayılarının toplamını hesaplayan program yazınız.

    import java.util.Scanner;

    public class Main {

    public static void main(String[] args) {
        Scanner inp = new Scanner(System.in);
        System.out.print("Sayı Giriniz :");
        int number = inp.nextInt();
    
        int basValue, result = 0;


        while (number != 0) {
            basValue = number %10;
            System.out.println(basValue);
            result += basValue;
            number /= 10;

        }
        System.out.println("rakamların toplamı :" + result);


     }
    } 
    
  
   
   https://app.patika.dev/ahmetfurkan
   
   ![image](https://user-images.githubusercontent.com/107626332/180719233-8bca437b-6881-4c8f-acc4-914c66c8be4b.png)



