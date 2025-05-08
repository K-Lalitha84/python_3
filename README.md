# python_3
"""
#code for determinig the character entered by user
input:8
output:the user entered a digit
inut:t
output:the user has entered a character
input: 
output:the user has entered a space
"""
char=input("press any key:")
if char.isalpha():
    print(char,"is a character")
if char.isdigit():
    print(char,"is a digit")
if char.isspace():
    print(char,"is a space")
        
        
code -2

#code to check number is positve or negative
num=int(input("Enter a number:"))
if num>0:
    print(num,"is positive")
if num<0:
    print(num, "is a negative")
if num==0:
    print(num,"is a zero:")
