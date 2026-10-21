//1.문자열 출력하기
import java.util.Scanner;

public class Solution {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        String a = sc.next(); 
        
        System.out.println(a); 
    }
}

//2. a b 출력하기
3. import java.util.Scanner;

public class Solution {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int a = sc.nextInt();
        int b = sc.nextInt();

        System.out.println("a = "+a);
        System.out.println("b = "+b);
    }
}

//3. 문자열 반복출력하기

import java.util.Scanner;

public class Solution {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        String str = sc.next();
        int n = sc.nextInt();
        for(int i=0; i<n; i++){
        System.out.print(str);
        }
    }
}
