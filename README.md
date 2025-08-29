# Classes-object
AIM: 

       To study and implement Classes and Objects


SOFTWARE USED:

       VS Code



 OBJECTIVE:

 - To understand the foundational principles of Object-Oriented Programming (OOP).
 - To study the structure and behavior of classes and objects in C++.
 - To implement encapsulation by defining data members and member functions.
 - To explore object instantiation, access modifiers, and constructor usage.
 - To demonstrate how objects interact with class definitions to model real-world entities.



 THEORY:

 Object-Oriented Programming (OOP) is a paradigm that organizes software design
 around data, or objects, rather than functions and logic. C++ is one of the most
 widely used languages that supports OOP principles.

 The two core building blocks of OOP are:

    1. Class – A blueprint or template for creating objects.
    2. Object – An instance of a class that holds actual data and behavior.

 -------------------------------------------------------------------------------
 1. CLASS:
 -------------------------------------------------------------------------------
 - A class defines a user-defined data type.
 - It encapsulates data members (variables) and member functions (methods).
 - Syntax:
        class ClassName {
            private:
                // Data members
            public:
                // Member functions
        };

 - Access Specifiers:
     • private   → Members are accessible only within the class.
     • public    → Members are accessible from outside the class.
     • protected → Used in inheritance scenarios.

 -------------------------------------------------------------------------------
 2. OBJECT:
 -------------------------------------------------------------------------------
 - An object is a real-world entity created from a class.
 - It has identity, state (data), and behavior (functions).
 - Syntax:
        ClassName obj;

 - Objects access public members using the dot operator:
        obj.functionName();

 -------------------------------------------------------------------------------
 3. CONSTRUCTORS AND DESTRUCTORS:
 -------------------------------------------------------------------------------
 - Constructor: A special function that initializes objects.
     • Automatically invoked when an object is created.
     • Can be overloaded to support multiple initialization formats.

 - Destructor: A special function that cleans up resources.
     • Automatically invoked when an object goes out of scope.

 -------------------------------------------------------------------------------
 FLOW OF EXECUTION:
 -------------------------------------------------------------------------------

    Class Definition
        |
        |---> Object Instantiation
                    |
                    |---> Constructor initializes object
                    |---> Object accesses member functions
                    |---> Destructor cleans up (at end of scope)

 -------------------------------------------------------------------------------
 EXAMPLE:

    class Student {
        private:
            int rollNo;
            string name;

        public:
            void setData(int r, string n) {
                rollNo = r;
                name = n;
            }

            void display() {
                cout << "Roll No: " << rollNo << ", Name: " << name << endl;
            }
    };

    int main() {
        Student s1;
        s1.setData(101, "Ishika");
        s1.display();
        return 0;
    }

 -------------------------------------------------------------------------------
 ADVANTAGES OF USING CLASSES AND OBJECTS:
 -------------------------------------------------------------------------------
 - Encapsulation: Keeps data safe from outside interference.
 - Reusability: Classes can be reused across programs.
 - Abstraction: Hides complex implementation details.
 - Modularity: Breaks down code into manageable components.
 - Real-world modeling: Makes software design intuitive and scalable.


SAMPLE OUTPUT:

         Area of rectangle-
               Length of rectangle is:7
               Width of rectangle is:4
               Area of rectange is:28

        
        Students of class-
              Student 1 details are:
              Ishika
              ENTC
              Data Structure with C++.
              9.9
              Student 2 details are:
              Tejas
              CS
              Data Structure with Python.
              9.5

       Vehicle Details-
              The details of first car are:-
              Name:Alto
              Brand:Maruti
              Colour:White
              Year of manufacture:2011
              Amount:560000
              
              The details of second car are:-
              Name:Aspire
              Brand:Ford
              colour:Black
              Year of manufacture:2020
              Amount:1100000
              
              The details of first bike are:-
              Name:Pulsar
              Brand:Bajaj
              colour:Black
              Year of manufacture:2019
              Amount:185000
              The details of second bike are:-
              Name:Apache
              Brand:TVS
              colour:Grey
              Year of manufacture:2024
              Amount:278000

     Calculator-
             Enter the value of a: 5
             Enter the value of b: 6
             The sum is: 11
             The difference is: -1
             The product is: 30
             The quotient is: 0.833333

    Volume-
             480
             480

    Finding error -
            Height:- 23.23
            Volume:-2.55617e+06


 CONCLUSION:
 
        This experiment introduces the core concepts of object-oriented programming through the implementation of classes and objects in C++. By encapsulating 
        data and behavior, and modeling real-world entities, OOP enhances code readability, maintainability, and scalability. Mastery of these concepts
        is essential for building robust and modular software systems.
