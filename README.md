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



code-3

#if-else
age=int(input("Enter the age of the person :"))
if age>=18:
    print("Eligible to vote")
else:
    print("the person is underaged")

code--4:
#check the number is a even or odd
num=int(input("enter a number:"))
if num%2==0:
    print(num,"is even")
else:
    print(num,"is odd")


code--5:
'''#program to enter any character .If the enter char  is in lowercase
than convert the char into uppercase and viseversa..'''
ch=input("Enter a char from a to z:")
if ch>='A' and ch<='Z':
    ch=ch.lower()
    print("the enter character was in uppercase...lower:"+ch)
else:
    ch=ch.upper()
    print("the enter character was in lowercase...upper:"+ch)
  output::
  Enter a char from a to z: L
the enter character was in uppercase...lower:l




code --6
#(nested if-elif-else)
# if-else if conidition
#code for checking the interval of a given number

num=int(input("enter a number:"))
if num>=0 and num<=10:
    print(num ,"is in 0-10 range")
elif num>=11 and num<=20:
    print(num,"is in 11-20 range")
elif num>=21 and num<=30:
    print(num,"is in 21-30 range")
else:
    print("out of range:")
    
output::
enter a number: 35
out of range

code--6
#check the condition for nested if-elif-else for postive oer negative
num=int(input())
if num>0:
    print(num,"is positive")
elif num<0:
    print(num,"is negative")
else:
    print("Zero")


LOOPS

code--7:
#print the whole numbers till n
n= int(input("Enter a  value of n:"))
loop=0
while loop<=n:
    print(loop,end=" ")
    loop+=1

output::
Enter a  value of n: 8
0 1 2 3 4 5 6 7 8 


code-8
#reverse loop

num=int(input("enter the value of n"))
while num>=0:
    print(num,end=' ')
    num-=1
output::
enter the value of n 6
6 5 4 3 2 1 0 


code--9:
#print the even numbers till n by using while loop
n= int(input("Enter a  value of n:"))
i=0
while i<=n:
    if i%2==0:
        print(i,end=" ")
    i+=1
output::
Enter a  value of n: 10
0 2 4 6 8 10 


code--10
#print the odd numbers till n by using while loop
n= int(input("Enter a  value of n:"))
i=0
while i<=n:
    if i%2!=0:    ( or if i%2==1:)
        print(i,end=" ")
    i+=1
output:;
Enter a  value of n: 10
1 3 5 7 9 


code--11:;

\'''
program to read the numbers until  -1 is encountered.
also count negatives,positives and zeros entered by the user
'''
n=p=z=0
print("enter -1 to exit !!!")
while(1):
    num=int(input("enter any number:"))
    if num==-1:
        break
    if num==0:
        z+=1
    elif num>0:
        p+=1
    else:
        n+=1
print("count of positive entered :",p)
print("count of negative entered :",n)
print("count of zeros entered :",z)

output::
'''enter -1 to exit !!!
enter any number: 8
enter any number: 4
enter any number: -11
enter any number: -26
enter any number: 0
enter any number: 4
enter any number: 6
enter any number: 0
enter any number: -2
enter any number: -33
enter any number: -1
count of positive entered : 4
count of negative entered : 4
count of zeros entered : 2
'''

    


