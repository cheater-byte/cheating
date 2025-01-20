Write following programs in AI practical copy. 
program 1: Write a program to display personal information. 
n1=input("enter your name") 
n2=input("enter your father's name") 
n3=input("enter your class") 
n4=input("enter your school name") 
print("my name is",n1) 
print("my fathers name is",n2) 
print("my class is",n3) 
print("my school name is",n4) 
program 2: Write a program to calculate simple interest. 
p=int(input("enter principal amt")) 
r=int(input("enter rate of interest")) 
t=int(input("enter time")) 
si=p*r*t/100 
print("simple interest is”,si) 
program 3: Write a program to find average of three numbers. 
n1=int(input("enter first number ")) 
n2=int(input("enter second number")) 
n3=int(input("enter third number ")) 
avg=n1+n2+n3/3 
print("the average is",avg) 
program 4: : Write a program to find area and perimeter of a rectangle. 
b=int(input("enter breadth ")) 
l=int(input("enter length")) 
area=l*b 
perimeter=2*(l+b) 
print  ("the area is",area) 
print ("the perimeter is",perimeter) 
Program 5: 
To calculate discounted amount with discount% 
cp=input(float(“enter cost price”)) 
sp=input(float(“enter selling price which should be lesser than cp”)) 
d=cp-sp 
print(“the discount is”,d) 
d%=d/cp*100 
print(“the discount percent is”,d%) 
program 6: 
To calculate surface area and volume of a cuboid 
l=input(float(“enter length of cuboid”)) 
b=input(float(“enter breadth of cuboid”)) 
h=input(float(“enter height of cuboid”)) 
sa=2*(lb+bh+hl) 
v=l*b*h 
print(“the surface area is”, sa) 
print(“the volume is”, v) 
program 7: Create a list in Python of children selected for science quiz . 
perform the following tasks  
a. print the whole list 
b. Delete the name “vikram” from the list. 
c. Add the name “Jay” at the end. 
d. Remove the item which is at the second position. 
Ans.  students=[“Arjun”, ”Sonakshi”, “Vikram”, “Sandhya”, “Sonal”, “Isha”, ”kartik”] 
print (students) 
students.remove(“Vikram”) 
print (students) 
students.append(“jay”) 
print (students) 
del students[1] 
print (students) 
program 8: Create a list in python of following numbers. 
a. Print the length of the list. 
b. Print the elements from second to fourth position using positive indexing. 
c. Print the elements from third to fifth position using negative indexing. 
Ans.   li=[23, 12, 5, 9, 65,44] 
print(len(li)) 
print(li[1:3 ]) 
print(li[2:4 ]) 
Program 9: 
Create a list. Add the elements using extend function. Now sort the final list in ascending order and 
print it. 
List_1=[10,20,30,40] 
Print(list_1) 
List_2=[14,15,12] 
List_1.extend(list_2) 
Print(list_1) 
Print(sort(list_1)) 
Program 10: Program to check if a person can vote. 
Age=int(input(“Enter your age”)) 
If age>=18: 
Print(“you are eligible to vote”) 
Else: 
Print(“you are not eligible to vote”) 
Program 11: 
Program to check if a number is positive or negative. 
Num=float(input(“enter a number”)) 
If num>=0: 
Print(“zero”) 
Elif: 
Print(“positive number”) 
Else: 
Print(“negative number”) 
Program 12: 
To check grade of students 
marks=float(input(“enter marks”)) 
if marks>75: 
print(“A grade”) 
elif marks>60: 
print(“B grade”) 
else: 
print(“C grade”) 
program 13: 
To print first 10 natural numbers. 
I=1 
N=10 
While i<=n 
Print(i) 
I=i+1 
Program 14: 
To print first 10 even numbers. 
I=1 
N=input int(“enter any number”) 
While i<=n 
Print(i) 
I=i+2 
Program 15: 
To print sum of10 natural numbers. 
N=10 
Sum=0 
I=1 
While i<=n 
Sum=sum+i 
I=i+1 
Print(“the sum=”,sum) 
Program 16: 
To turn every item of a list into its square. 
Num=[1,2,3,4,5,6] 
Res=[] 
For i in num: 
Res.append(i*i) 
Print(num) 
Print(res) 
Program 17: 
To accept a word from user and reverse it. 
Word=input(“input a word to reverse”) 
For char in range(len(word)-1,-1,-1): 
Print(word[char],ene=””) 
Print(n)
