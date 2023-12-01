Chapter 9 Questions:

Create a class named dog with a constructor consisting of name age and color in the parameter
Answer:


    public class Dog {
	  String name;
	  int age;
	  String color;	
	  public Dog(String name, int age, String color){
  	this.name = name;
  	this.age = age;
  	this.color = color;
  	}
Create a reference variable which can be any name and then create an object for that variable, and lastly assign the object to that refernce.
Answer:
	
     reference variable name: laptop
	   Laptop newLaptop = new Laptop();
Create a class name monster and declare an instance variable called height.Next, Create a constructor with an int parameter, and set the height equal to that parameter.Lastly, create a tester class to call the constructor to the main method.
	Answer:
		
    public class Monster {
		Int height;
		
		public Monster(int monsterHeight){
		Height = monsterHeight;
		}
		Public class MonsterTest{
		Monster m = new Monster(32);


Create a class called  pants with a color instance variable.Create a no-arg constructor for the color and pick a color. Next, create another constructor with a String parameter and set the color equal to the parameter.Then create a testclass with a  main method which calls the no-arg constructor and call the method with parameter and change the color of the pants.
Answer: 
	
   
    public class Pants{
  	String color;
  	public Pants(){
  	color =  “green”;
  	}
    public Pants(String newColor){
    color = newColor;
    	}
    }
    public class TestPants{
    	Pants n = new Pants();
    	Pants n2 = new Pants(“blue”);
    }
    }
	
Let's say we have a class called Number:
    
    public class Number{
    Number  n = new Number();	
    
With the method:
   
    public void num(){
    	Missing code
    }
How would you assign a reference to another object in the method above?
Answer: 
  
    n = new Number();


What is the output of this code
      
      public class Cowboy{
      public Cowboy(){
       system.out.println(“Howdy,  Partner!!”);
    }
    }
    
    Public class Foe extends Cowboy{
    Public Foe(){
    System.out.println(“This town ain’t big enough for the both of us.”);
    }
    }
    Public class WildWest{
    Public static void main (String[]args){
    System.out.println(“Welcome to Town!”);
    Cowboy c = new Cowboy();
    Foe f = new Foe();
    }
    }
Answer: 

    Welcome to Town!
    Howdy, Partner!!
    This town ain’t big enough for the both of us.
Create a superclass constructor using the keyword  ‘super()
Answer: 
    
    public class Something {
    int size;
    
    Public Something(int newSize){
    super(); // super is reference variable that is used to refer to parent class constructors. Can be used in variables/methods
    Size = new Size;

True or false is this constructor Overloaded ?

    public class Person() {
    
    public Person(int age) {}
    public Person(String name) {}
    public Persone(String name, int age) {}
    }
Answer:

    True an overloaded constructor is the use of multiple different constructor bodies


In this class below
    
    public class LifeSpin {
    	Public void Read() {
    		int k = 80;
    		sleep();
    }
    Public void Sleep(){
    	k = 20
    }
    }
Explain how in this class why is k dead in the Sleep() method? Answer:
      
      k is dead because in the Read() method k was declared as a scope which can only be used in that method only, not in other methods.



Use null in a reference to kill an object
Answer:

    public class Candy{
    
    Candy c= new Candy();
    
    Public void eat(){
    c= null; 
    } 
     }
