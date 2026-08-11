import java.util.ArrayList;
import java.util.Stack;
public class StackInsert
{
    public static void main (String[] args) {
        int [] stack=new int[5];
        int top=-1;
        //push
        stack[++top]=10;
        stack[++top]=20;
        stack[++top]=30;
        stack[++top]=40;
        //display
        for (int i=top;i>=0;i--)
        {
            System.out.print(stack[i]+" ");
        }
        System.out.println();
        //pop
        System.out.println(stack[top--]);
        for(int i=top;i>=0;i--)
        {
            System.out.print(stack[i]+" ");
        }
    }
}
