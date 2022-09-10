# Remove-Consecutive-Duplicates
public class Lec12 {
    public static void main(String[] args)
    {
        String str="aabbc";
        int le=str.length();
        String res="";
        for(int i=0;i<le;i++)
        {
            if( i<le-1 && str.charAt(i)==str.charAt(i+1))
            {
                continue;
            }
            else
            {
                res=res+str.charAt(i);
            }
        }
      //  return res;
      System.out.println(res);
    }
    
}
