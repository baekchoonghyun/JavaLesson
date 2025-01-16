public class Operators {
    public static void main(String[] args) {
        int num1;
        int num2;
        int num3;
        /*
        연산자
       1.산술연산자:+-*,/,%(나머지 ,++1씩증가 --1씩감소)
       2.대입연산자 = += -= *= ,/=,%=
       3. 관계(비교)연산자
       4. 논리연산자
       5. 비트연산자
       6. 기타 연산자
         */
        num1 =10;
        num2 = 3;
        System.out.println("num1 :"+num1);
        System.out.println("num2 :"+num2);
        num3=num1+num2;
        System.out.println("num1+num2= :" + num3);
        num3=num1-num2;
        System.out.println("num1-num2= :" + num3);
        num3=num1*num2;
        System.out.println("num1*num2= :" + num3);
        num3=num1%num2;
        System.out.println("num1%num2= :" + num3);
        num3=num1/num2;



//실수형변수를선언할필요가잇다
        //num1=num1+1
    float fNum;
    fNum= num1 / (float)num2; //형변환(Type Casting)
    System.out.println("num1 / num2= :" + fNum);
    //증감연산자
    System.out.printf("num1 : %d\n" ,  num1++);
    System.out.printf("num1 : %d\n" ,  num1++); //post-fix:같은줄에사용된 명령을먼저 실해하고 난뒤 증가
    System.out.printf("num1 : %d\n" ,  num1);
    System.out.printf("num1 : %d\n" ,  ++num1);  //pre-fix:변수의값을 먼저 증가한 뒤 같은줄에있는 명령을실행
        //형변환
        short shNum=num1;
  }
}
