# pattern
# 1.Create programme for the given pattern:
*****
*****
*****
*****
*****
# PROGRAM:
~~~java
public class Squarepattern {
        public static void main(String[] args) {

            // size of the square
            int size = 5;
            // outer loop
            for (int i = 0; i < size; i++) {
                // inner loop
                for (int j = 0; j < size; j++) {
                    System.out.print("*");
                }
                System.out.println();
            }
        }
}
~~~
# OUTPUT:

![output](https://user-images.githubusercontent.com/95342910/224887174-14b00a41-d705-4d8f-9c7b-44c68ebb4e88.png)

# 2.Create programme for the given pattern:
*********
 *******
  *****
   ***
    *
    
    
# PROGRAM:
~~~java
public class Inverted
{
    public static void main(String[] args)
    {
        int rows=5;
        for (int i= 0; i<= rows-1 ; i++)
        {
            for (int j=0; j<=i; j++)
            {
                System.out.print(" ");
            }
            for (int k=0; k<=rows-1-i; k++)
            {
                System.out.print("*" + " ");
            }
            System.out.println();
        }
    }
}
~~~
# OUTPUT:

![output-2](https://user-images.githubusercontent.com/95342910/224888239-08b1b4b8-0e5e-405e-a0b5-e12c2b11526f.png)

# 3.Create programme for the given pattern:
*
**
***
****
*****
****
***
**
*

# PROGRAM:
~~~java
public class Pascaltriangle {
    public static void main(String[] args) {
        int size = 5;

        for (int i = 1; i <= size; i++) {
            for (int j = 0; j < i; j++) {
                System.out.print("*");
            }
            System.out.println();
        }

        for (int i = 1; i <= size - 1; i++) {
            for (int j = 0; j < size - i; j++) {
                System.out.print("*");
            }
            System.out.println();
        }
    }
}
~~~
# OUTPUT:

![output-3](https://user-images.githubusercontent.com/95342910/224888025-e24ef9d7-b05f-49a7-be82-c7458fa0ae0b.png)
