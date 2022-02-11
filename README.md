# ass-1-11-02-22
#Write a program to Generate Student Result.
#Required Fields(sno,name,group,6 subjects,total,avg,grade.
sno=int(input('enter a number:'))
sname=input('enter student name:')
group=input('enter group:')
OB=int(input('online Business marks:'))                     
AS=int(input('Analytical Skills'))
EE=int(input('Environment Education:'))
Acc=int(input('Accounts:'))
java=int(input('java marks:'))
OS=int(input('Operating System:'))
#total for 6 subjects
total=OB+AS+EE+Acc+java+OS
avg=total/6
if avg>91:
    print('O-Grade')
elif avg>81:
    print('A-Grade')
elif avg>71:
    print('B-Grade')
elif avg>61:
    print('C-Grade')
elif avg>51:
    print('D-Grade')
elif avg>=35:
    print('Pass')
else:
    print('Fail')
print('total:',total)
print('avg:',avg)

output:
enter a nnumber:3
enter student name:swathi
enter group:bca
online Business marks:34
Analytical Skills87
Environment Education:67
Accounts:98
java marks:65
Operating System:67
C-Grade
total: 418
avg: 69.66666666666667
