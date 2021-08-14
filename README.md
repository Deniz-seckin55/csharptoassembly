# csharptoassembly
A program that converts C# code to Assembly x64 NASM

# Important
This is not a program! This is a library (.dll) for C#.

# How to use
  1. Create an instance of "CSharpToAssembly.Assembly" and store it in a variable
  2. Now, you can use the functions inside the variable

# Functions
  Write(string):
    Print the paramater string to screen without a newline character at the end
  WriteLine(string):
    Print the paramater string to screen with a newline character at the end
  ReadLine(int):
    !! CURRENTLY WOKING ON IT !!
  ReadKey():
    !! CURRENTLY WOKING ON IT !!
  WriteVariable(string)
    Print the variable that's name is parameter string
  WriteLineVariable(string)
    Print the variable that's name is parameter string and put a newline character at the end

# Assembly.Manual Functions
  AppendCode(assembly, code):
    Manually appends code to given assembly
  GetCode(assembly):
    Returns the generated assembly code


