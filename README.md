# Day One- Hello World, Calculator, Tempprture Converter, CLI To Do List, Number Guesser Word, Counter, Markdown Portfolio
<br> <b>Hello World </b> </br> 
<!-- Hello wold is complete August 25 20:43 with html format-->
# calcualtor.py <!--Python calc-->

def calc(a, b, op):
      if op == "+":
          return a + b:
    elif op == "-":
          return a - b
    elif op == "*":
          return a * b
    elif op == "/":
      return "Error" if b == 0 else a/b
a = float(input("First number:  "))
op = input("Operator ( + - * /"): ")
b =float(input("Second number: "))
print("Result:", calc(a, b, op))
