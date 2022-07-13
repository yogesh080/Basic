namespace - it provide the level of separation
operators/ arthematic operators - (=,+,*,/)etc


OOPs : object oriented Programming system
	-> 
	(1)class  :template/blue print to create object
		-> variable : 
			-> 2 :	-> global/instance
					-> local
					-> static
		-> constructor : special type of method, 
						it is resposible for create object of class
						-> used to initilize variables
			->	default Con
			->	parameteraised Con
			->	non parameteraised Con

			:=> 1. con does not any return type
		-> methods
	(2).Object : realtime entity , state : variables,properties.   behavior:  methods
	(3).Inheritance : 
		it is a process of aquiring all the properties &  behavior of another/parent class 

		-> single
		-> multilevel
		-> Hybrid
		-> multiple
		-> Herarchy



	(4).Abstraction : is process of Hiding Implementation and providing functionality to the user
				: interfaces : is also a type , contains abstractMethods
					abstactmethod : which has only defination no any implementation

					1. create interface => methods defination
					2. create class => inherit interface=> implement the methods
					3. create object of interface using the class

					4. use/call the methods using object of interface
				: abstract class:
					1. create Abstract cls => abs : abstract/non Methods
					2. create class => inherit ABS class 
						=> implement Abs methods : use override key word for implementation 
					3. create object of AbsClass using child class


				
	5.Polymorphisum : 
		-> it is proces of doing a work/functionality in many ways
		1. method overloading
			-> by changidn the sigature : 
				Sinature : 
					name
					return type
					parameters : number of para
								type of para
								order of para
		2. method overriding 

		diff : 
			1. 
	6.Encapsulation

this : => cotains current object address

static : => used to declare class level members

Access Modifiers : => 
	public : it is available for all classes              : High
	internal : it is available inside a assembly/project  : littile than Public
	protected : it is available inheriting classes		  : low
	private : this memberes are iside same class		  : very less
enum : is also a type, lsit of constants

application => 1.projects => 1.namespace1 => multple classes/ types
		
							 2.namespace2
				2.project 
upcasting : 
	creating a object of child class using refference of parent class;
downcasting : 
	creating a object of parent class using refference of child class;
	
	
	



Generic-
	public int GenericFun<T>(T value)  -   Here T is the data type int , string, bool , decimal etc which we provide so that our coding become easier to use
	
	
	
	
	
REGEX - Patterns or Regular expressions are special characters which help search data, matching complex patterns.
Regular expressions are shortened as 'regexp' or 'regex’.	

.NET Reflection makes it possible to View Information at Runtime, without knowing at Compile Time:
• Inspect classes,
• Inspect interfaces,
• Inspects fields and
• Inspect methods
example - Using System.Object.GetType()


DATA Structures- Linear(linkedlist,stacks and qeous) and non-linear(tree and graph are used in Non-Linear)

Collections - framework that provides readymade classes
using interfaces to store and manipulate group of objects.

	
