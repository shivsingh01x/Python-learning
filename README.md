# Python-learning

----Table of Content----
* Saving N Working on Github & Git.
* Comments, Escape Sequences & Print Statement
* Variables & Data Types
* Taking User Input in Python
* Small Proj: Creating a calculator using Python
* Typecasting in Python
* String in Python
* String Slicing & it's Operationsin Python
* String Methods in Python


-----Content----
(*) Comments, Escape Sequences & Print Statement.
    ^ \n: Print("This is \n example of Escape Sequence.")
    ^ #: Comment
    ^ ```Multiline comment```:Multi-line Comment
    ^ Print('Double \"Quote"\ text while printing')
    ^ Print("Hey", 6, 7, sep="~", end="009\n") Seperator & Ending

(*) Variables & Data Types
    ^ way to define variable: a = 4
    ^ print("The type of a is", type(a))
    ^ Data Types: ---------------------
                  **Numeric Types:**
                  int:- 3
                  float:- 3.0
                  Complex Numbers:- 2+3j
                  ----------------------
                  **Sequence Types:**
                  str:- ""
                  List:- []
                  Tuple:- ()
                  ----------------------
                  **Mapping Types:**
                  Dictionary:- {}
                  ----------------------
                  **Set Types:**
                  Set:- {}
                  ----------------------
                  **Boolean Types:**
                  True/False
      ^ Defing Let and Const in Python
                  Python does not have let and const.
                  **Rule to declare var**
                  my_variable = 10
                  **Rule to decalre const**
                  PI = 3.14159
                  MAX_VALUE = 100

(*) Taking Input from User
                  user_input = input("Enter something: ")
                  print("You entered:", user_input)

(*) Building a Calculator using Python
                  Enter the value of a:
                  Enter operation:
                  Enter the value of b:
                    a = input("Enter the value of a:")
                    a = int(a)
                    x = input("Enter the opertor:")
                    b = input("Enter the value of b:")
                    b = int(b)
                    if x == '+':
                        result = a + b
                    elif x == '-':
                        result = a - b
                    elif x == '*':
                        result = a * b
                    elif x == '/':
                        if b != 0:
                            result = a/b
                        else:
                            result = "Error: Division by zero"
                    else:
                        result = "Invalid Operation"
                    print(int(result))

(*) Typecasting in python
    ^ Explicit typecasting - Done by user; 
    ^ Implicit typecasting - Done by Python.
    ^ a = int(a) #converting string/float to int
    ^ a = float(a) #converting string/int into float

(*) String in python
    ^ name = "Shiv" / 'Shiv'Both are string
    ^ quote = 'This is "too much" good' 
    ^ Quote =  "This is \"too much" good"
    ^ multiline = '''this is 
                     tooo good to add
                     this much'''
   
(*) String Slicing & it's Operation
    ^ Indexing in string 
                    a = "Shiv Singh"
                    print(a[0])
    ^ Slicing of a String 
                    name = "ShivSinghKeer"
                    print(name[0:5])
                    print(name[4:8])
    ^ Negative Slicing of a string
                    fruit = "Mango"
                    print(fruit[-3:-1]) i.e 2:4 i.e. ng                    
    ^ Length of a String
                    lenthus = "ShivSingh"
                    print(len[lenthus])

(*) String Methods in Python (strings are immutable)
    ^ Uppercase method:
                    a = "Shiv"
                    print(a.upper())
    ^ Lowercase method:
                    a = "Shiv"
                    print(a.lower())
    ^ String rstrip method:
                    a = "Shiv!!!!"
                    print(a.rstrip("!")) i.e. Shiv
                    a = "!!Shiv!!!!!!"
                    print(a.rstrip("!")) i.e. !!Shiv
    ^ Replace Method in String:
                    a = "Shiv, Shiv"
                    print(a.replace("Shiv","John")) i.e. John, John
    ^ Splitting string into list:
                    a = "Shiv Singh is born to rule"
                    print(a.split(" "))
    ^ Capatilize method:
                    a = "introduction tO PythoN"
                    print(a.capitalize())
    ^ string center method:
                    a = "Welcome to Python Classes!"
                    print(a.center(50)) 
                    #try finding it's length with/withour center method
    ^ count method in string:
                    a = "Shiv is Shiv, best of best"
                    print(a.count("Shiv")) i.e. 2
    ^ endswitch method in string:
                    a = "Shiv is on a nice pace!"
                    print(a.endswitch("!)) i.e. true
    ^ find method in string:
                    a = "Let's find your intelligency"
                    print(a.find("intelligency"))
    ^ isalnum method in string:
                    a = "WelcomeToTheCourse"
                    print(a.isalnum())
    ^ isalpha method in string:
                    a = "Welcome00"
                    print(a.isalpha())
    ^ islower method in string:
                    a = "WELcome"
                    print(a.islower())
    ^ isprintable method in string:
                    a = "haapy birthdday\n"
                    print(a.isprintable())
    ^ isspace method in string:
                    a = "white space check"
                    print(a.ispace())
    ^ istitle method in string:
                    a = "Welcome to the title check"
                    print(a.istitle())
    ^ startswitch method in string:
                    a = "Python learning is very benifical"
                    print(a.startswitch("Python"))
    ^ swapcase method in string:
                    a = "Python swapcse method in string"
                    print(a.swapcase())
    ^ title method in string:
                    a = "this is title for testing"
                    print(a.title())
                    
    
                        
    
    

                  
