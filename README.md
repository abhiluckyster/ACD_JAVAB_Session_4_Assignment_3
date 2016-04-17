# ACD_JAVAB_Session_4_Assignment_3


public class Employee {
	int empid;
	double salary;
	String name;
	
	public Employee() {
		// TODO Auto-generated constructor stub
	}
	
	public Employee(int empid, double salary, String name) 
	{
		super();
		this.empid = empid;
		this.salary = salary;
		this.name = name;
	}
 public void display()
 {
 System.out.println("Employee is "+name);
 System.out.println("Id is "+empid);
 System.out.println("Salary is "+salary);
 
 }
 
	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Employee e = new Employee(1111111,2000000,"Abhinav");
		e.display();

	}

}
