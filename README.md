# learning_python_4_functions
#loops and conditionals. Loops are used to repeat a block of code multiple times. Conditionals are used to execute a block of code only if a certain condition is met.
name = "Yaswanth"
for a in name:    #for loop
    print(a, end="_")
    print(a)
    if a == "n":
        print("found")
players_india = ["virat", "rohit", "dhoni", "sachin", "sehwag"]
for player in players_india:
    print(player)
    for i in player :
     print(i)
x=0
while (x<5):
    print(x)
    x=x+1 #while loop
for y in range(11):
    if y==5:
        break
    print("5 x",y+1,"=",5*(y+1))

i=0
while True: #infinite loop 
    print(i)
    i=i+1
    if (i%100==0):
          break
a = 10
b = 12
def calcgmean(a,b): #function is used to perform a specific task. def is used to define a function.
    mean = a*b/(a+b)
    print (mean)
c= 20
d= 30
calcgmean(c,d) 
def average(*numbers):
    sum = 0
    for i in numbers:
        sum = sum + i
    return sum / len(numbers)
a=int(input("Enter science GPA: "))
b=int(input("Enter maths GPA: "))
c=int(input("Enter english GPA: "))
d=int(input("Enter social GPA: "))
average(5, 6, 7, 8)
def fullname(**names):
    print("Hello,", names["fname"], names["mname"], names["lname"],"\nyour GPA is", average(a, b, c, d))  #function with arguments
fullname(fname ="Yaswanth Reddy", lname = "yeddula", mname ="")
