# GroupProject
Chapter 2 Questions: 

1.)Let’s say we have a class called Class.How do you create an object for this class?
    Answer: 
		
    Class1 test = new class1();
	
2.)True or false: objects are instance methods?
     Answer: 
       
       false

3.) Create a building class and declare instance variables within it, then Make an object in the main method and call the instance variables.
      Answer: 
    
    public class Building{
		Int floors = 3;
		String color = brown;
		}
		Class buildingTester{
		public static void main(String[] args){
		Building test = new Building();
		System.out.println(test.floors());
		System.out.println(test.color());
		}
		}

4.) What is a tester class?
   Answer:
   
     a separate class in which the main method is used to test your code

5.) What is the void method?(public void….)
    Answer: 
    
    its a method which does not return a value 

6.) Create a class called phone and declare instance variables that describe the phone you have ex: size, color, etc. Create a tester for the phone class and create a new object for the phone class. Use this to call the other methods and print out the information for the phone.
ex: phone size: 6 inches
      phone color: blue
    Answer:
    
    public class Phone{
		String color = “blue”;
		String brand = “apple”;
		Double size = 5.23;
		}
	       Class phoneTester{
		public static void main(String[] args){
		Phone test = new Phone();
		System.out.println(“Phone brand: “ + test.brand());
		System.out.println(“Phone color: “ + test.color());
		System.out.println(“Phone height: “ + test.size() + “ inches” );
		}
		}
	      


7.)Create a class called car and declare instance variables to describe your car,make sure you include speed as one of the variables but leave it unassigned. Create a method that then lets the user type in a speed for the car, make sure to create a scanner for this.Then,create a method that tells us if the car is moving or is parked based on the speed. Then create a tester for the class and create a new object to call the methods and print out the information of the car.
ex: car color: blue
      car brand: Hyundai 
      car status: parked
	Answer:
	
 
    Import java.util.Scanner;
	  Public class Car{
	  String color = “Red”;
	  String brand = “BMW”;
	  Int speed; 
	

  	Public void getspeed(){
  	Scanner input = new Scanner(System.in);
  	System.out .println(“Enter the speed for the car,”);
  	speed = input.nextInt();
  	}
  
  	public boolean isMoving(int speed){
  		boolean moving;
  		if(speed > 0){
  		moving = true;
  		}else {
  		moving = false;
    }
    return moving;	
    }

    public void display(boolean moving){
    	if(moving){
    	System.out.println(“The car is moving”);
    	}else{
    	System.out.println(“The car is parked”);
    	}
    	}
    Class carTester{
    public static void main(String[] args){
    	car obj = new car();
    	Obj.input = new Scanner(System.in);
    	obj.getSpeed();
    	int speed = obj.speed();
    	boolean isMoving = obj.isMoving(speed);
    	obj.color();
    	obj.brand();
    	obj.display(isMoving);
    	}
    	}

8.) What is the key difference between a class and an object?
     Answer: 
       
       class is the structure or blueprint of the object and the object is the one that holds all the information
     

9.)Create a class called person and declare instance variables within it, it can be as many variables as you like.Then create a tester class and print out the information for that person.
	Answer:
   
    public class Person{
		String name = “Bob”;
		int age = 32;
		}
	Class personTester{
		Person obj = new Person();
		System.out.println(“Name: “ + obj.name());
		System.out.println(“Age: “ + obj.age());

10.)If there was a public class called cat with instance variables:
	String name = “Ruby”
	Int age = 7;
      How would you call the instance variables in the tester main method?
	Answer:
    
    cat ex = new cat():
	  ex.name();
	  ex.age();
