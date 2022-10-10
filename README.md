# hesapmakinesi
switch/break ile hesap makinesi

    import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        int n1, n2, select;

        Scanner input = new Scanner(System.in);
        System.out.print("İlk sayıyı giriniz :");
        n1 = input.nextInt();
        System.out.print("İkinci sayıyı giriniz :");
        n2 = input.nextInt();

        System.out.println("1-Toplama\n 2-Çıkarma\n 3-Çarpma\n 4-Bölme");
        System.out.print("Seçiminizi yapınız: ");
        select = input.nextInt();

        switch (select)  {
            case 1:
            System.out.print("Toplama : "+ (n1+n2));
            break;
            case 2:
                System.out.print("Çıkarma : "+ (n1-n2));
                break;
            case 3:
                System.out.print("çarpma : "+ (n1*n2));
                break;
            case 4:
                switch (n2){
                    case 0:
                        System.out.println("Bir sayı sıfıra bolunemez !!");
                        break;
                    default:
                        System.out.print("Bölme : "+ (n1/n2));
                }
            break;
            default:
                System.out.print("Yanlış sayı girdiniz");








        }

        }




        }

