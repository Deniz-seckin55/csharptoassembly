# csharptoassembly
A program that converts C# code to Assembly x64 NASM

# Important
This is not a program! This is a library (.dll) for C#.

# How to use
  1. Create an instance of "CSharpToAssembly.Assembly" and store it in a variable
  2. Now, you can use the functions inside the variable

# Functions
  1. Write(string):
  2.  Print the paramater string to screen without a newline character at the end
  3. WriteLine(string):
  4.   Print the paramater string to screen with a newline character at the end
  5. ReadLine(int):
  6.   !! CURRENTLY WOKING ON IT !!
  7ReadKey():
  8  !! CURRENTLY WOKING ON IT !!
  9. WriteVariable(string)
  10.   Print the variable that's name is parameter string
  11. WriteLineVariable(string)
  12.   Print the variable that's name is parameter string and put a newline character at the end

# Assembly.Manual Functions
  1. AppendCode(assembly, code):
  2.   Manually appends code to given assembly
  3. GetCode(assembly):
  4.   Returns the generated assembly code
