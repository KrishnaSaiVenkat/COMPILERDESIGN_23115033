📘 Custom Instruction Compiler (SI & TRAPEZIUM)

==============================================


This project implements a simple compiler using **Flex** and **Bison** that recognizes and processes custom instructions for:

🧮 Simple Interest (SI)  

📐 Area of a Trapezium (TRAPEZIUM)

🔣 General expressions like: (P * R * T) / 100


----------------------------------------

🛠️ Requirements

----------------------------------------


Make sure you have the following tools installed:

🔧 Flex 

📏 Bison  

💻 g++ (GNU C++ Compiler)

To install on Ubuntu/Debian:

    sudo apt-get install flex bison g++

----------------------------------------

⚙️ How to Build

----------------------------------------



1. Open terminal in the project directory.
   
2. Run:

 make

🟢 This will generate the executable: `mycompiler`

----------------------------------------
▶️ How to Run
----------------------------------------

    ./mycompiler

💬 You’ll be prompted to enter expressions.


----------------------------------------
🧪 Example Inputs
----------------------------------------


📌 Simple Interest:


    SI A = 1000, 2, 5;

📌 Trapezium Area:


    TRAPEZIUM B = 10, 6, 5;

📌 General Expression:


    C = (1000 * 2 * 5) / 100;

----------------------------------------

✨ Features

----------------------------------------


✅ Recognized Instructions:


1. **SI** – Calculates simple interest  
   Syntax: `SI <var> = P, T, R;`
   

3. **TRAPEZIUM** – Calculates area of a trapezium  
   Syntax: `TRAPEZIUM <var> = a, b, h;`
   

5. **General Expression** – Evaluates expressions  
   Example: `C = (P * R * T) / 100;`
   

📤 Output Includes:

- 🧱 Three Address Code
  
- 🧠 Optimized Instructions
  
- 📈 Evaluated Result
  
- 🗂️ Final Code (STORE)
  

----------------------------------------

🧹 Cleaning Up

----------------------------------------


To remove all compiled files:


    make clean
    

🗑️ This will remove `.o` files, `parser.tab.*`, `lex.yy.c`, and the binary.


----------------------------------------

📁 Project Structure

----------------------------------------


📄 lexer.l       – Lexical analyzer (Flex)  

📄 parser.y      – Grammar and parsing logic (Bison)  

📄 main.cpp      – Program entry point  

📄 makefile      – Compilation instructions  

📄 README.txt    – You’re reading it now!


----------------------------------------

👤 Author

----------------------------------------

GANDE SAI VENKAT

----------------------------------------

📜 License

----------------------------------------


This project is free to use, modify, and share for educational and personal purposes. 🎓

📸 output 📸

----------------------------------------

![Screenshot 2025-04-06 192852](https://github.com/user-attachments/assets/98b6eeb8-6ef2-44d1-a3c2-39a26f36d7bd)



