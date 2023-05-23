- 👋 Hi, I’m @Karunagubbala
-package employee;  
 
class EmployeeDetails {  
    
int emp_id, salary, Phonenumber, DOJ;  
String name, email;  
  
  
public int getEmp_id() {  
    return emp_id;  
}  
public void setEmp_id(int emp_id) {  
    this.emp_id = emp_id;  
}  
public int getSalary() {  
    return salary;  
}  
public void setSalary(int salary) {  
    this.salary = salary;  
}  
public String getName() {  
    return name;  
}  
public void setName(String name) {  
    this.name = name;  
}  
public int getDOJ() {  
    return DOJ;  
}  
public void setDOJ(int DOJ) {  
    this.DOJ = DOJ;  
}  
public int getPhonenumber() {  
    return Phonenumber;  
}  
public void setPhonenumber(int Phonenumber) {  
    this.Phonenumber = Phonenumber;  
}  
public String getEmail() {  
    return email;  
}  
public void setEmail(String email) {  
    this.email = email;  
}  
  

@Override  
public String toString() {  
    return "Employee [emp_id = " + emp_id + ", salary = " + salary + ", name = " + name + ", DOJ = " + DOJ 
            + ",Phonenumber = " + Phonenumber + ", email = " + email + "]";  
    }  
      
}  

class employee
	{  
    
    public static void main(String args[]) {  
          
         
        EmployeeDetails emp = new EmployeeDetails();  
        
        emp.setEmp_id(101);  
        emp.setName("Karuna");  
        emp.setDOJ(22/3/2023);  
        emp.setSalary(15000);  
        emp.setPhonenumber(8888);  
        emp.setEmail("KKK@gmail.com");  
          
        
        System.out.println(emp);  
          
        int sal = emp.getSalary();  
        int increment = 0;  
        
        if ((sal >=1000) && (sal <=1500))  
        {  
           
            increment += (sal * 2)/100;  
            sal = sal+increment;  
              
            emp.setSalary(sal);  
            System.out.println("\n Salary is incremented \n");  
            System.out.println(emp);  
              
        }else if ((sal >=1500) && (sal <=20000)){  
            
            increment += (sal * 5)/100;  
            sal = sal+increment;  
              
            emp.setSalary(sal);  
            System.out.println("\n Salary is incremented \n");  
            System.out.println(emp);  
        }else {  
            System.out.println("\n Salary is not incremented \n");  
            System.out.println(emp);  
        }         
    }  
}  
 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Karunagubbala/Karunagubbala is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
