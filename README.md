class student:
 def __init__(self):
 self.rollno=input("Enter Roll Number : ")
 self.name = input("Enter Name : ")
 self.python =int(input("Enter Python Marks : "))
 self.java = int(input("Enter JAVA Marks : "))
 self.os = int(input("Enter OS Marks : "))
 self.se = int(input("Enter SE Marks : "))
 def display(self):
 print("\nStdeunt name is:",self.name)
 print("Stdeunt Roll_NO is:",self.rollno)
 print("Python marks is:",self.python)
 print("java marks is:",self.java)
 print("OS marks is:",self.os)
 print("SE marks is:",self.se)
 def total_avg(self):
 total=self.python+self.java+self.os+self.se
 avg=total/4
 print("Total marks is:",total)
 print("avg marks is:",avg)
 def result(self):
 if(self.python<35):
 print("failed in python")
 else:
 print("pass in python")
 if(self.java<35):
 print("failed in java")
 else:
 print("pass in java")
 if(self.os<35):
 print("failed in os")
 else:
 print("pass in java") 
 if(self.se<35):
 print("failed in se")
 else:
 print("pass in se")
 
n=int(input("enter number of students")) 
for i in range(n):
 si=student()
for i in range(n):
 si.display()
 si.total_avg()
 si.result()

