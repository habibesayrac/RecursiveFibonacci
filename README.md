# RecursiveFibonacci
public class Main {

    static int fibonacciSeries(int number) {
        int n1=0,n2=1,n3;
        for (int i = 0; i < 10; i++) {

            n3=n1+n2;

            n1=n2;
            n2=n3;
            System.out.print(n1);
            System.out.println();
        }
        return n1;
    }
        public static void main(String[]args){

            System.out.println(fibonacciSeries(10));
    }
}



