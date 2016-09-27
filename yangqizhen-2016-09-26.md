#2016-09-26工作日报
============================
============================
1.应完成内容
    常用类——Math类，Random类，Arrays类，System类，Date类，Calendar类
    java垃圾回收
2.已完成内容
 
*  Random类
 
 ========================================
 public class DemoMath
 {

                   public static void main(String [] args)
{
	Random r=new Random();
    
     System.out.println(r.nextInt(18));
	
    }
}  

  
 * 
 ================================================
 public class week8 {
	    public static void main(String[] args)  {
	    	Scanner input = new Scanner(System.in);
	    	
            String uname, pwd;
	    	
            System.out.print("请输入用户名： ");
		   
           uname = input.next();
		   
           System.out.print("请输入密码： ");
	    	
            pwd = input.next();
	    	
            if (uname.equals("TOM") && pwd.equals("1234567")) {
		    
            System.out.print("登录成功！ ");
	    	}
              else
            {
		    	
                System.out.print("用户名或密码不匹配，登录失败！");
	    	}
   


  * java垃圾回收
  ==================================================
     public class Test {
	private static Test test=null;
	
    private int num;
	
    public void method(){
		
        System.out.println("测试。。。");
        }	
	
    public static void main(String[] args) throws InterruptedException {
		new Test();//对象进入去活状态
		
        System.gc();
		
        System.runFinalization();
		
        test.method();}
	
    @Override
	
    protected void finalize() throws Throwable
    {
		//当系统来清理资源时，让test引用到该对象，复活
	
    test=this;}
    }

3.未完成工作


4.未完成原因


5.遇到的问题及解决方案
多练习
