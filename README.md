# C++-PROGRAMMING-
Self made Notes 
You said:
Your First C++ Program (with \n)
#include <iostream>
using namespace std;

int main() {
    cout << "Hello, Shivendra!\n";
    return 0;
}

Now let’s break every single part.

📘 Line-by-Line Explanation (Easy Notes Version)

1️⃣ #include <iostream>
✔ Meaning:
This line tells C++ to include a library named iostream.
✔ Why we use it:
Because iostream contains tools for input and output


cout → print on screen


cin  → input from keyboard


✔ Without this line:
You cannot use cout, so nothing can be printed.

2️⃣ using namespace std;
✔ Meaning:
This tells the compiler:
"Use the standard (std) library without writing std:: again and again."
Example:
Without this line, you must write:
std::cout << "Hello";

With the line:
cout << "Hello";

✔ Why we use it:
To make the code shorter and cleaner.

3️⃣ int main()
✔ Meaning:
main() is the starting point of every C++ program.
The computer begins execution from the first line inside main().
✔ Why int?
int means the function returns an integer value (usually 0) to the operating system indicating the program ended successfully.

4️⃣ { and }
These braces define the beginning and end of the main function.
Everything between them is your program.

5️⃣ cout << "Hello, Shivendra!\n";
✔ cout


Means console output


Used to print text on screen


Comes from the iostream library


✔ <<
This operator sends data to cout.
Think of it like:
Put this text into cout to display.
✔ "Hello, Shivendra!\n"


Anything inside "   " is a string (text).


\n means new line (go to next line).


It works like pressing Enter.


Why prefer \n over endl?


\n is faster


endl forces flushing the buffer — unnecessary for beginners


Most professionals use \n



6️⃣ return 0;
✔ Meaning:
This sends the value 0 back to the system.
✔ Why?


0 means program ended successfully


If something went wrong, programs return a different number



🌟 Clean Notes (You can copy-paste)
# include <iostream> → allows use of cout and cin (input/output library)

using namespace std; → lets us use cout without writing std::cout

int main() → starting point of the program (returns an integer)

{ } → program block starts and ends

cout << "text\n"; → prints text on screen, \n creates a new line

return 0; → tells OS that program ran successfully


🔥 If you want, we can move to:
✔ variables
✔ data types
✔ operators
✔ conditions (if-else)
✔ loops
✔ functions
✔ classes (OOP)
Just tell me: Next topic?
