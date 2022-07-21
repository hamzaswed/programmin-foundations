## I. CHAPTER (OBJECT-ORIENTED THINKING)

#### 1- Objects

==> **All objects has:**

- Identity => Olivia's coffee mug
- Attributes => Color, Size, Fullness
- Behaviors => fill(), empty(), clean()

#### 2- Class

==> **Class:** code-template for creating program objects

==> **Class Components:**
 
 - Name (What is it?) => RoundCookie
 - Attributes (What describes it?) => weight, color, icing
 - Behaviors (What can it do?) => decorate(), consume()
 
 ==> **Method:** a program procedure that can return a value (functions defined as a part of class) and can only accses data known to that object
 
 ```
+-----------------------------------------------+
Class:
 
 Name: 
  RoundCookie
            
 Attributes (properties): 
  - Weight
  - Color
  - Icing
    
 Behaviors (methods):             
  - decorate()
  - consume()
+-----------------------------------------------+

+-----------------------------------------------+
Object One:

 Name: 
  barronCookie
            
 Properties:
  Weight: 16 gram
  Color: red
  Icing: true
    
 Methods:           
  decorate()
  consume()
+-----------------------------------------------+

+-----------------------------------------------+
Object Two:

 Name: 
  oliviaCookie
            
 Properties:
  Weight: 12 gram
  Color: blue
  Icing: false
    
 Methods:           
  decorate()
  consume()
+-----------------------------------------------+
```

 ==> **Existing Classes In OO Languages:** 
 
 ```
 At Minimum
  - String
  - Date
  - Collections
  - Networking
 ```

#### 2- Explaning "A PIE" (Abstraction, Encapsulation, Inheritance, Polymorphism)


- Abstraction:
 
--> Made for other classes to inherit Props & Methods from.

--> Abstraction classes can't be instantiated [con't create object from].

--> By using absturaction we discard what's unimportant or irrelevant Props and Methods.

  ```
+-----------------------------------------------+
Class:
 
 Person: 
            
Properties: 
  - Name
  - Heihgt
  - Gender
    
+-----------------------------------------------+

+-----------------------------------------------+
Another Calsses

Class One <inherit Perons class properties>
            
Properties: 
  - Name => Hamza
  - Heihgt => 174
  - Gender => Male
    
Class Two <inherit Perons class properties>
            
Properties: 
  - Name => Hind
  - Heihgt => 160
  - Gender => Female
    
+-----------------------------------------------+

 ```
 
 - Encapsulation:
 
--> Make properties and methods privet.

--> Whene make its privet you can access theme only with class method.


 ```
+-----------------------------------------------+
Class 'Has Encapsulated property'

User <User class gets user's info and save them>
            
Properties: 
  - privet password;
    
Methods:

- setThePassword(setPassword)
      privet password = hash(setPassword);
 
+-----------------------------------------------+

 Explanation:
 --> In above Example we can set a new password only by using setThePassword Method.
 ```

 - Inheritance:
 
--> Base a new object or class on an existing one.

--> Inherite an existing attribute or method.

--> Great form of code reuse.

```
+-----------------------------------------------+
Lets sade we whant two classes have same Properteis and Methods.
So we can create a class (Abstract class) has needed Properties and Methods

Class Person (parent class)

Properties: 
  - Name
  - Phone
  - Address

Class Customer (child class) inherites Person class's Properties and Methods
            
Properties: 
  - (Person class's Properties and Methods)
  - costumerID
    
Class Employee (child class) inherites Person class's Properties and Methods
            
Properties: 
  - (Person class's Properties and Methods)
  - employeeID
 
+-----------------------------------------------+
 ```

- Polymorphism:
 
--> Works same as Abstruction class.

--> but whene we use impelemnted (inherited) Properties and Methods form Polymorphism class we should use all them.

--> Or we can override inherited Properties and Method from Polymorphism class to do a same task but in another ways (or doing another taskes).

--> Like make a cup of coffee, we can in several ways do a same cup of coffee.

--> Input (coffee) ==> using the method defined in Polymorphism class 'makeCoffee()' ==> output (cup of coffee).
