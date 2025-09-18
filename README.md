# python_codes_Basic
fruits=[]
n=2
for i in range (n):
    bask=input("enter the fruit of your choice")
    fruits.append(bask)
print(fruits)

print("peru" in fruits)




2] 
 num = int(input("Enter the number "))
for i in range (num):
    for j in range (i+1):
        print("#", end=" ")
    print(" ")
for i in range (num):
    for k in range (i,num):
        print("* ", end="")
    print("")
print("56")


o/p
#  
# #  
# # #  
# # # #  
# # # # #  
* * * * * 
* * * * 
* * * 
* * 
* 

56



3] 
fruits=[]
n=2
for i in range (n):
    bask=input("enter the fruit of your choice")
    fruits.append(bask)
print(fruits)
print("peru" in fruits)


4]
a=[1,2]
b=[3,4]
a.extend(b)
print(a)

o\p
[1, 2, 3, 4]


5]
a=[1,2,3,3]
b=[3,3,3,3,3,4]
a.extend(b)
print(a.count(3))
it counts the number of times a number is repaeated in the list


6]
b=[3,3,3,4,2,8,4,9,6,4,3,3,4]
b.sort()
print(b)



7]
b=[3,3,3,4,2,8,4,9,6,4,3,3,4]
b.sort(reverse= True)
print(b)



8]
abc= 'i am a girl'
stuff = abc.split()
print(stuff)

o/p 
['i', 'am', 'a', 'girl']


9]
a=[1,2,3,3]
b=[3,3,3,3,3,4]
b.remove(3)
print(b)


10]
fhand= open('mbox-short.txt')
for line in fhand:
    line= line.rstrip()
    if not line .startswith('from '):continue
    word= line.split()
    print(word(21))
