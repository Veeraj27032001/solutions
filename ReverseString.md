# REVERSE using String Builder
class ReverseStr{

public static void main (String args[])
{
      
      String str="hello";
       
       StringBuilder strBuild=new StringBuilder(str);
       
       System.out.println("reverse of "+str+" is " +strBuild.reverse());
      
}
}
# output of StringBuilder reverse
reverse of hello is olleh

# REVERSE using loop
class ReverseStr{

public static void main (String args[])
{

        String str="hello";
        
        //empty string  variable
        
        String rev="";
        
        for (char CharOfStr : str.toCharArray())
        {
            //to  each char add rev variable value at the end and store it rev variable  
            rev=CharOfStr+rev;
        }
        System.out.println("reverse of "+str+" is " +rev);
  }
}
 # output of reverse using loop
reverse of hello is olleh
