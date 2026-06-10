🎓 Grade Calculator in C++

A simple and beginner-friendly C++ program that takes marks as input from the user and displays the corresponding grade using if-else if conditions.

📌 Features
* Takes marks input from the user
* Uses if-else if conditional statements
* Displays grades based on marks range
* Clean and easy-to-understand logic
* Beginner-friendly C++ project

🛠️ Technologies Used
* C++
* Standard Input/Output Library (iostream)

📂 Project Structure
Project/
│── main.cpp
│── README.md
│── Screenshot.png

💻 Source Code
#include<iostream>
using namespace std;

int main() {
    int marks;
    cin >> marks;

    if (marks < 25) {
        cout << "Grade is: " << "F";
    }
    else if (marks >= 25 && marks <= 39) {
        cout << "Grade is: " << "E";
    }
    else if (marks >= 40 && marks <= 49) {
        cout << "Grade is: " << "D";
    }
    else if (marks >= 50 && marks <= 59) {
        cout << "Grade is: " << "C";
    }
    else if (marks >= 60 && marks <= 79) {
        cout << "Grade is: " << "B";
    }
    else if (marks >= 80 && marks <= 100) {
        cout << "Grade is: " << "A";
    }

    return 0;
}

📊 Grade Criteria
Marks Range	Grade
Below 25	F
25 - 39	E
40 - 49	D
50 - 59	C
60 - 79	B
80 - 100	A

▶️ How to Run
Using Code::Blocks / VS Code
1. Open the project
2. Compile the program
3. Run the executable
4. Enter marks as input
   
Example
Input:
78

Output:
Grade is: B
📸 Screenshot

<img width="1442" height="901" alt="Screenshot 2026-06-10 131527" src="https://github.com/user-attachments/assets/1837a000-9085-4986-8924-bb91383ab6c0" />

🎯 Learning Concepts

This project helps beginners understand:
* Variables & User Input
* Conditional Statements
* Logical Operators (&&)
* Multiple else if Conditions
* Basic Program Flow in C++
  
🚀 Future Improvements
* Add input validation for marks above 100
* Handle negative inputs
* Add percentage calculation
* Convert into menu-driven application
  
👨‍💻 Author
Rishab Raj

⭐ Support
If you found this project helpful, consider giving it a ⭐ on GitHub.
