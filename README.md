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
    print(char,"is a digit")
if char.isspace():
    print(char,"is a space")
        
