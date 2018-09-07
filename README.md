# handling_student_scores
student=[]
num=int(input("Enter the number of students"))
for i in range(0,num):
    
    name=input("Enter name")
    m1=int(input("Enter m1 marks"))
    m2=int(input("Enter m2 marks"))
    m3=int(input("Enter m3 marks"))
    m4=int(input("Enter m4 marks"))
    m5=int(input("Enter m5 marks"))
    student.append(name)
    student.append(m1)
    student.append(m2)
    student.append(m3)
    student.append(m4)
    student.append(m5)
    
    
    print(student)

user=input("Enter name:")
sub=input("Enter sub:")
ind=student.index(user)
if sub=="math":
        print(student[ind+1])
elif sub=="phy":
        print(student[ind+2])
elif sub=="chem":
        print(student[ind+3])
elif sub=="bio":
        print(student[ind+4])
elif sub=="ss":
        print(student[ind+5])
else:
    print("Invalid sub")

  
