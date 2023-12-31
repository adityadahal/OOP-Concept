# OOP-Concepts
OOP stands for <b>Object Oriented Programming </b> <br/> 
Procedural Programming is about writing Procedures or Methods to perform any operation, while Object Oriented Programming is about creating Objects that contain data and method. <br/>
WHY OOP over Procedural Programming : 
- OOP is faster and easy to execute.
- OOP provides clear struture to program.
- OOP has DRY('Dont Repeat Yourself) principle.

### Class
Class is a collection of Objects. It doesn't take any space on memory. Space is taken for Class when Object for that class is made. Class is also called as blueprint or template from which objects are created. <br/> For Example: *Student is a class where particular student Aditya is an Object*
<br/>
### Object 
 Object is a member (an instance) of Class which takes memory. An Object has an  State and Behaviour. <br/> For Example : *A cat’s state includes its color, size, gender, and age, while its behavior is sleeping, purring, meowing for food, or running around like crazy at 4 AM.*.
 <br/>
 ### Method
  Method is a programmed procedure defined as part of that class and is available to object initialized from that class. Each Object can call the method of their respective classes.
  <br/>
 ### Constructor
 Constructor is a special type of method whose name is same as method name. Whenever we use new keyword to create instance(member) of class, Constructor is invoked(called) and Object of class is returned. Since, Constructor can only return Object of the class we are not supposed to add return type to it. If return type is added to the constructor it becomes method of the class, In this way Constructor and Method are distinguished. 
 <br/>
 
### Encapsulation
  The main concept of Encapuslation is to make sure that 'sensitive' data is hidden from users. It is used to hide the value or state of structured data objects inside the class to prevent direct access from unauthorized access. <br/> To achieve Encapsulation you must:
 - declare class attributes/variables private.
 - provide public <b>get</b> and <b>set</b> methods to access those private variables and update those private variables. <br/>
### Get and Set Methods
private variables can only be access within that class (outside class has no access). It is possible to access the private attributes/variable when we provide get and set method to it. The get method returns the variable value and set method sets the value. Syntax for both is that they start with either get or set, followed by the name of the variable, with the first letter in upper case: <br/>
![image](https://github.com/adityadahal/OOP-Concept/assets/107999400/33b2a1c3-dbdf-4dc9-8a96-e163961a6551)
<br/> <b>this</b> keyword is used to refer current object and other is used to refer from parameterized object.
<br/>
<br/>
A Quick Reminder : <br/>
![image](https://github.com/adityadahal/OOP-Concept/assets/107999400/6d20b742-2a98-498c-8c96-1c5d5ea090eb)
<br/>
### Inheritance
Inheritance is the concept to import the attribute and methods from one class to another. 'Inheritance concept' is grouped in two categories:

- subclass(child) : the class that inherits from another class.
- superclass(parent) : the class being inherited from.
  
To inherit from a class <b>extends</b> keyword is used.
![image](https://github.com/adityadahal/OOP-Concept/assets/107999400/c6b96c50-a47f-46d5-9212-f95b5029652c) <br/>
Here, Car is sub-class and Vechile is super-class.
<br/>
### Polymorphism
Polymorphism means "many forms", which occurs when there are many classes related to each other by inheritance. Polymorphism allows to have one interface and multiple implementation of that Interface's method.
- Compile time Polymorphism: Polymorphism that exist during the time of Compilation is called <b>Compile Time Polymorphism </b>. It is achieved by <b>Method Overloading</b> <br/>
  <p> <b>Method Overloading</b> </p>
  <p>Whener class contains more than one method with <b>SAME NAME BUT DIFFERENT PARAMETERS</b>, it is called Method Overloading.</p>

- Run time Polymorphism: Polymorphism that exist at the run time is called Run time Polymorphism . It is achieved by <b>Method Overriding</b> <br/>
<p> <b>Method Overriding</b> </p>
 <p>When method has <b>SAME NAME, SAME PARAMETER AND SAME RETURN TYPE</b>, it is called Method Overriding</p>
 
### Abstraction
Data Abstraction is process of hiding certain details and showing only essential information to users. Abstraction can be achieved by using <b>Abstract</b> classes or <b>Interfaces</b>.
The <b>abstract</b> keyword is non-access modifier, used for classes and methods.

- Abstract Class : restricted class that cannot be used to make objects. (to access it, it must be inherited from another class)
- Abstract Method: can only be used in Abstract class . Abstract Method cannot have body(logic inside method)
  <br/>
  ### Interface
  Interface is a way to achieve Abstraction. Interface is compeletely abstract class that is used to group methods with empty bodies. <br/> To access interface methods, the interface must be 'implemented' (kinda like inherited) by another class with <b>implements</b> keyword and then body of interface method can be provided by accessing interface method. <br/>
  ![image](https://github.com/adityadahal/OOP-Concept/assets/107999400/4d0c2b15-0219-4df4-8c60-f7a69e6f0cbc)
<br/>
   <b>few points to remember: </b> <br/>
   - Interfaces cannot be used to create objects. <br/>
   - Interface method cannot have a body. Body is provided by Class which implements Interface. <br/>
   - On implementing Interface all of its method should be overridden. <br/>
   - Interface method are by default abstract and public. <br/>
   - Interface attribute are by default public, static and final. <br/>
   - Interface cannot contain constructor. (As it cannot be used to create a object) <br/>



















































































 
 
