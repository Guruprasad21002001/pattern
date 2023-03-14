# pattern
# 1.Create programme for the given pattern:
~~~
*****
*****
*****
*****
*****
~~~
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
~~~
*********
 *******
  *****
   ***
    *
    
~~~    
# PROGRAM:
~~~java
public class Pattern2
{
    public static void main(String[] args) {
        int i,j,n;
        n=5;
        for(i=n;i>0;i--)
        {
            for(j=0;j<n-i;j++)
                System.out.print(" ");
            for(j=1;j<=i*2-1;j++)
            {
                System.out.print("*");
            }
            System.out.println();
        }
    }
}
~~~
# OUTPUT:

![output-2](https://user-images.githubusercontent.com/95342910/224890602-2eab7e96-c3cf-49b7-8d56-eaf393669acf.png)

# 3.Create programme for the given pattern:
~~~
*
**
***
****
*****
****
***
**
*
~~~
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
