# machine-learning
machine-learning
public class RemoveDups {
  public static void main(String args[])
     {
         String s = "programming";
         int l = s.length();
         char ch;
         String ans="";
          
         for(int i=0; i<l; i++)
         {
             ch = s.charAt(i);
             if(ch!=' ')
                 ans = ans + ch;
             s = s.replace(ch,' '); //Replacing all occurrence of the current character by a space
         }
  
        System.out.println("Word after removing duplicate characters : " + ans);
     }
}
