# -Haywood--cop3330-ch-7--ex-123-
Application Assignment in C++ (EXTRA CREDIT) - Chapter 7, Exercises 1, 2, 3

/*
 *  UCF COP3330 Fall 2021 Assignment 6 Solution
 *  Copyright 2021 Kaylah Haywood
 */
 
 // Exercise 1 //
 // Allowing underscores in the calculator's variable names //
 
 class GFG {
  
    public static void main(String args[])
    {
    
    // Declaring underscore as variable
        int _ = 10;
        
   //Printing stored value
        System.out.println(_);
    }
}

///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

// Exercise 2 //
// Providing an Assignment Operator = //
 
 class Main {
  public static void main(String[] args) {
    
    // Creating Variables
    int a = 2;
    int var;

    // Utilizing = To Assign Values
    var = a;
    System.out.println("var using =: " + var);

    // Utilizing =+ To Assign Values
    var += a;
    System.out.println("var using +=: " + var);

    // Utilizing =* To Assign Values
    var *= a;
    System.out.println("var using *=: " + var);
  }
}

// Utilizing let //
// The let statement is useful as this statement declares a local variable in a block scope //
// This statement can be problematic as it is only initialized to a value when a parser evaluates it and also does not create properties 
// of the window object when declared globally //

let x = 1;

if (x === 1) {
  let x = 2;

  console.log(x);
}

console.log(x);

///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

// Exercise 3 //
// Providing Named Constants //
 
 class Test {
 
    public static void main(String[] args) {
       // User Defined Constants
       const pi = 3.14;
        
        double variablel = 2*Pi*10;
        double variable2 = 2*Pi*25;
        System.out.println ("Perimeter of circle with radius of 10 cm is " + variablel + "); 
        System.out.println ("Perimeter of circle with radius of 25 cm is " + variable2 + "); 
        
        // Utilizing setValue() Method
        CircleRadius<variable1, variable2> pi1 = pi.setValue("Assignment6");
  
    }
}

// For Chapter 7, The Drill problems build off "calculator08buggy.cpp" file and the "std_lib_facilities.h" header file, which was provided
// via Webcourses from Professor Cacoulidis 
// These files are found on Programming: Principles and Practice Using C++, 2nd Edition[Archive.zip](https://github.com/KayHay/-Haywood--cop3330-ch-7--ex-123-/files/7665405/Archive.zip)
