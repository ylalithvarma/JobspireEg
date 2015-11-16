# JobspireEg
Jobspire Challenge

//A Simple Python code that takes a Variable name and generates a Random Number between 6 and 15 returns as: varname+Generated    Random number (eg: Rahul 11):
# Function definition
from random import randint
def Challenge(name):
   # Generate a Random number between 6 and 15
   randNum=randint(6,15)
   stmt=name+" "+randNum
   return stmt;

# Now you can call the Challenge function
Challenge(Rahul);
