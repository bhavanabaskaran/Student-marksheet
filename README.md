# Student-marksheet
name=input('enter name:')
rollno=int(input('enter roll no:'))
course=input('enter course:')

print('-------------------------------')

print('enter marks of five subjects')
S1=int(input('enter mark of sub1:'))
S2=int(input('enter mark of sub2:'))
S3=int(input('enter mark of sub3:'))
S4=int(input('enter mark of sub4:'))
S5=int(input('enter mark of sub5:'))

total=S1+S2+S3+S4+S5/5
percentage=total/5

print('percentage :',percentage)

print('--------------------------------')

if percentage>=80:
      Grade='A'
elif percentage>=70:
     Grade='B'
elif percentage>=60:
     Grade='C'
elif percentage>=50:
      Grade='D'
else:
       Grade='Fail'
       
print('         MARKSHEET              ')
print('--------------------------------')

print('Student name: ',name)
print('Student Rollno: ',rollno)
print('Course: ',course)

print('--------------------------------')

print('Subject 1: ',S1)
print('Subject 2:',S2)
print('Subject 3:',S3)
print('Subject 4:',S4)
print('Subject 5:',S5)

print('-------------------------------')

print('Overall percentage: ',percentage)

print('-------------------------------')

print('Grade of the student: ',Grade)

print('---------------------------------')
