import java.util.*;
import java.io.*;
class Series
{
public static void main(String args[])
{
Scanner in = new Scanner(System.in);
int t=in.nextInt();
for(int i=0;i<t;i++)
{
int a=in.nextInt();
int b=in.nextInt();
int n=in.nextInt();
int count= 0;
int constant= 0;
int sum= 0;
while(count < n)
{
if(count == 0)
{
constant = 1;
sum =a + (constant*b) + sum;
}
else
{
constant = constant * 2;
sum = (constant * b) + sum;
}
System.out.println(sum +" ");
count += 1;
}
System.out.println();
}
in.close( );
}
}
OUTPUT;
D:\>javac Series.java

D:\>java Series
2
0 2 10
2
6
14
30
62
126
254
510
1022
2046

5 3 5
8
14
26
50
98

