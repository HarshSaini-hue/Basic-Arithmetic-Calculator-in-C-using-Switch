# Basic-Arithmetic-Calculator-in-C-using-Switch
A simple command-line calculator built using C++ and the switch statement. This program allows users to perform basic arithmetic operations like:  Addition (+)  Subtraction (-)  Multiplication (*)  Division (/)

char op; // for operator
double n1; // for number 1
double n2; // for number 2
double result; // for the calculated output

std::cout << "#*#*#*#*#*#*#*#*#* Welcome to Calculator.cpp #*#*#*#*#*#*#*#*#*" << '\n';

std::cout << "-> Which function you want to perform?" << '\n';
std::cout << "-> Press + for addition" << '\n';
std::cout << "-> Press - for substraction" << '\n';
std::cout << "-> Press * for multiplication" << '\n';
std::cout << "-> Press / for dividation" << '\n';
std::cin >> op;

std::cout<< '\n';

std::cout << "Write number 1 : ";
std::cin >> n1;

std::cout << "Write number 2 : ";
std::cin >> n2;

std::cout << '\n';

switch(op) {
  case '+' : result = n1 +n2;
  break;
  case '-' : result = n1 - n2;
  break;
  case '*' : result = n1 * n2;
  break;
  case '/' : result = n1 / n2;
  break;
  default : std::cout << "Please write correct Arithmetic Operator";
}

std::cout << "Output : " << result << '\n';


std::cout << "#*#*#*#*#*#*#*#*#*#*#*#*#*#*#*#*#*#*#*#*#*#*#*#*#*#*#*#*#*#*#*#*#*#*#";
