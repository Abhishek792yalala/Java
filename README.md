// Problem: Directly accessing the method in main class without assigning to a variable

class Code{

        @Deprecated

    public void method(){

            System.out.println("I am a deprecated method in class Code");

    }

    public int add(int x, int y){

            int z=(x+y);

            System.out.println("On addition of the given numbers, the sum is: "+ z);

            return z;

    }

    public static void main(String... java) {

        System.out.println("Welcome to java practice");

        ArrayList<Integer> a = new ArrayList<>();

        a.add(1);

        a.add(2);

        int b = a.get(1);

        System.out.println(b);

        Code c = new Code();

        c.method();

        new Code().add(2,3);// Directly accessing the method in main class without assigning to a variable.

    }

}

/*

Welcome to java practice

2

I am a deprecated method in class Code

On addition of the given numbers, the sum is: 5

 */
