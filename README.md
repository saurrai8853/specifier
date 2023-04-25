# specifier
package mypackage4;
// default constructor
//class EmpInfo{
//	int id;
//	String name;
//	
// 
//void display() {
//	System.out.println(id+" "+name);
//}
//}
//parametrized constructore
class std{
	int id;
	String name;
	
	std(int i,String n){
		id=i;
		name=n;
	}
	void display() {
		System.out.println(id+" "+name);
	}
}
public class Constructor {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		std std1=new std(2,"rahul");
		std std2=new std(10,"Saurabh");
		std1.display();
		std2.display();
		
		//EmpInfo emp1=new EmpInfo();
		
//		EmpInfo emp2=new EmpInfo();
		

	}

}
