// Matthew Young
// Exempt or Not 

/* This program determine weather a student has to take the final exam or not based 
    on their class average and how many days they were absent. */

#include <iostream>
#include <iomanip>
#include <cmath>

using namespace std;

double avgGrade; // Variable for average grade. 
int absClass;    // Variable for days absent. 


int main()
{          //Beginning of Main Function

    cout << "What is your course grade average? ";        // Ask user for course average. 
        cin >> avgGrade;                                  // User inputed course average. 
        
    cout << "How many days were you absent from class? "; // Ask user how many days they were absent. 
        cin >> absClass;                                  // User input for number of days absent. 
        
    if (avgGrade < 91) {                                                // If statement for avearge grade < 91. 
        cout << "You must take the final exam for the course." << endl; // Tell user they must take the final exam.  
    }
    else if (avgGrade < 93) {                                           // Else if statement for average grade < 93.
        
        if (absClass > 1) {                                                  // If statement for else if statement of < 93.
            cout << "You must take the final exam for this course." << endl; // Tell user they must take the final exam.
        }
            
        else {                                                               // Else statement for else if statement of < 93.
            cout << "You are exempt from the final exam." << endl;           // Tell user they are exempt. 
        }
    }
        
    else if (absClass > 3) {                                                 // Else if statement for > 3 days absent from class. 
            cout << "You must take the final exam for this course." << endl; // Tell user they must take the final exam. 
    }
    
    else {                                                                   // Else statement for original if statment. 
        cout << "You are exempt from the final exam." << endl;               // Tell user they are exempt. 
    }                                       
        


    return 0;
    
}           // End of main function. 
