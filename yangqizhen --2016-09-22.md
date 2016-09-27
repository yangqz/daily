#2016-09-22工作日报
===========================================
===========================================

1.应完成工作
    String 构造方法

2.已完成工作   
======================
      import java.nio.channels.UnsupportedAddressTypeException;

public class Method {

public static void main(String [] arge) throws UnsupportedAddressTypeException {

    @SuppressWarnings("unused")
	String t1 = new String();

    String original = "String构造方法";
    String t2 = new String(original);
    System.out.println(t2);

    char[] value = {'3','4','5','6','7','8'};
    String tb = new String(value);
    System.out.println(tb);

    String tb1 = new String(value,5,5);
      
    System.out.println(tb1);

    int[] codePoints = {20,33,56,77,66,65};
    String tb3 = new String(codePoints,3,4);
      
    System.out.println(tb3);

    byte[] bytes =  {2,10,8,3,5,7};
    String  tb4 = new String(bytes);
   
    System.out.println(tb4);

    String tb5 = new String(bytes,3,5);
    
    System.out.println(tb5);

 
    
  }
}
3.未完成工作



4.未完成原因


5.遇到的问题及解决方案
