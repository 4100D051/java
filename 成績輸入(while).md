```java
import java.util.Scanner;
public class test
{
    public static void main(String[] args)
    {
        Scanner scn=new Scanner(System.in);
        System.out.printf("請輸入你的成績");
        int num;
        num = scn.nextInt();
        while (num < 0 || num > 100)
        {
            System.out.printf("輸入錯誤請重新輸入");   
        }
        if(num < 60)
        {
            System.out.printf("請至學校網站進行補考登記");
        }
        else 
        {
            System.out.printf("恭喜妳通過考試!!!!!!!");
        }
    }
}
