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

#### 2- Explaning "A PIE" (Abstraction, Encapsulation, Inharitance, Polymorphism)


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
