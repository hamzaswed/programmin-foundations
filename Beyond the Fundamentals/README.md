# Beyond the Fundamentals Course Notes :bookmark_tabs:

## I. CHAPTER (COLLECTIONS)

#### 1- Understanding Collections

==> **Collections:** grouping multiple item together and storing them with a single name 

==> **Organizing data in this way has few advantages**

- Uses your code structure to indicate that multiple pieces of data are related
- Avoids creating a potentially huge number of variables to track within our code
- Offers simplefied syntax

#### 2- A simple collection: 

==> **List:** simple collection that groups pieces of data  together in a certain and assign the collection a name [array]

#### 3- **Dictionary:** for storing related information [json in javascript]

===========================================================================================

## II. CHAPTER (ITERATION)

#### 1- Introduction to iteration

==> **Iteration:** repeats the same procedure mutiple times until it reaches a specified endpoint.

==> **Loop:** code that iterates, moving from beginning to end of process, than starting over.

==> **To write code that iterates**
  
  - Specify tha data
  - What should happen to the data during each iteration
  - Indicate whene the loop should stop

==> **Infinite loop:** bug that can occur whene the ending condition is omitted or specified incorrectly.

===========================================================================================

## III. CHAPTER (USING EXTERNAL CODE)

#### 1- Comparing types of external code

==> **Module:** a file that contains code, like variables or functions (you can controll it and edit or type it).

==> **Package or Library:** using multiple modules togather so thay are distributed and used in a group (you can control it and call it whene do you whant).

==> **Framework:** whene a set of code is not just used together but used in a spacific way (you can't call it whene do you whant so you can use it and it's functionality in your app).

```
+-----------------------------------------------+
|  ...........................  ..............  |
|  : f1() f2()  :  f3()      :  : f4() f5()  :  |
|  :            :            :  :            :  |
|  : l1_module1 : l1_module2 :  : l2_module3 :  |
|  :            :            :  :            :  |
|  --library1-----------------  --library2----  |
|                                               |
|   application.c                               |
|                                               |
|       #include l1_module2                     |
|       #include l2_module3                     |
|                                               |
|       int main() {                            |
|           # case 'reload'                     |
|           f5();                               |
|           # case 'start'                      |
|           f1();                               |
|           # case 'stop'                       |
|           f4();                               |
|       }                                       |
|                                               |
+-----------------------------------------------+

.................................................
: FRAMEWORK_X                                   :
:                                               :
:     application start                         :
:     ...                                       :
:     application reload                        :
:     application stop                          :
:     ...                                       :
:...............................................:

```

