# Shivansh
**#Assignment:5**
#Task:1

dict = {}
n= int(input('Enter the number of students:'))
for i in range(n):
    name = input(('enter name:'))
    marks = int(input('enter marks:'))
    dict[name]=marks
name1= input("Enter the student's name whose marks to be displayed:")

if name1 in dict:
    print("{}'s marks:{}".format(name1,dict[name1]))
else:
    print("{} not found in the data.".format(name1))



#Task:2

l=[1,2,3,4,5,6,7,8,9,10]
extract= l[0:5]
print("Original list:",l)
print("Extracted first five elements:",extract)
extract.reverse()
print("Reversed extracted elements:",extract)
