
# Practicals:

# Practical 1:  print statement

import random
import math

print("i am ironman")

# practical 2: input integer and perform a basic operation

a=int(input("enter a number a = "))
b=int(input("enter a number b = "))
print()
c=a+b
print("sum of a and b = ",c)

c=a-b
print("substraction of a and b = ",c)

c=a*b
print("multiplication of a and b = ",c)

c=a/b
print("division of a and b = ",c)

c=a%b
print("modules of a and b = ",c)


# practical 3:add two complex number

print("sum of compelx number 12+45j and 12+46j")
a=complex(12,45)
b=complex(12,46)
c=a+b
print(c)

# practical 4:use float value for function trunc(),ceil(),floor()

print("float value for 145.82938 use funtion trunc()is ",math.trunc(145.82938))

print("float value for 145.82938 use funtion ceil() is ",math.ceil(145.83938))

print("float value for 145.82938 use funtion floor()is ",math.floor(145.82938))



# practical 5 :generate 5 random number from user take input of range and seed value 

import random
a=float(input("enter a seed  value = "))
print("enter a range ")
b=int(input())
c=int(input())
randomlist=[]
for i in range(0,5):
    n=random.randint(b,a)
    randomlist.append(n)
    
print(randomlist)
    

# Practical 6: write a program to perform all operation on string.

string="i am ujjainiya viren"
s="and i am engineering student "

#string operation no change in original string
print(string+s)
print(string.isalnum())
print(string.isalpha())
print(string.islower())
print(string.isupper())
#string convertion
print(string.upper())
print(string.lower())
print(string.capitalize())
print(string.casefold)
print(string.swapcase())

#string search and replace
print(s.find("student"))
print(string.replace("ujjainiya viren","ironman"))

#string lenght and index and count 
print(len(s))
print(s.index("e"))
print(s.count("e"))

#string format using diffent place holders
x="i am {name} "
y="my  name is {0} "
z="how are you {} "
print(x.format(name="ujjainiya viren"))
print(y.format("iron man"))
print(z.format("viren"))

#slicing a string not change in original string
print(string[0:4])
print(string[:4])
print(string[4:])
print(string[-5:])
print(string[:-5])

# Practical 7:Write a progam to perform all operation on list

avengers=["ironman","captian america","thor","hulk","black widow","howkay"]
magician=["dr.strange"]

avengers.append("ant man")
print(avengers)

print(avengers.count("ironman"))

avengers.extend(magician)
print(avengers)

print(avengers.pop(0))
print(avengers)

print(avengers.index("howkay"))
avengers.pop(4)
print(avengers)

avengers.insert(0,"ironman")
print(avengers)

avengers.reverse()
print(avengers)

avengers.sort()
print(avengers)

marvel=avengers.copy()
print(marvel)

marvel.clear()
print(marvel)





# Practical 8: Write a program to perform all operation on tuples

tup1=(1,2,3,4,4)
tup2=(5,6,7,8,9)

#concetnating of tw0 tuples
print (tup1+tup2)

#slicing of tuples not change in original tuples 
print(tup1[1:3])
print(tup1[0:])
print(tup1[:-1])
print(tup1[1:-1])
print(tup1[-1:])

#update and change in tuples is not possible because tuples are immutable we cannot update and change tuple after
# we can only use portion of the tuples

#delete tuple
del tup2

#create tuple which is deleted
tup2=(5,6,7,8,9)
tup3=("ironman","hluk","thor")

#basic operations on the tuples

print(len(tup1)) #find the lenghteh of the tuple
print(tup1*2) # repeattion on tuple
print(3 in tup1) # check element available or not 

print(max(tup3)) #return max vlaue in the tuple
print(min(tup3)) #return min value in the tuple

#convert list into tuple but no change in original list
number=[1,2,3,4,5,6]
print(tuple(number))

#methods for tuples

print(tup1.count(4)) #count the repeat values

print(tup2.index(8)) #give index of the given value 

#unpacking of the tuples

print(*tup1)
print(*tup2)
print(*tup3)





# Practical 9: Write program to perform all operation on the set

# set are unodered and unindexed in python and written in curly brackets

shinobi={"naruto","kakashi","sasuke","obito","madara","uchiha clan","shinju clan"}

print("naruto" in shinobi) #check the element is present or not

# once the set is created we cannot change the items but we can add item through add method for add one and more 
#we can use update method

#add method
shinobi.add("itachi")
print(shinobi)
#update method
shinobi.update(["hokage ","shikamaru","uzumaki clan"])
print(shinobi)

#unpack set
print(*shinobi)

#basic opertaion on the set
print(len(shinobi))
shinobi.discard("obito")#remove the element
print(shinobi)
print(shinobi.pop())#pop any element 
ninja=shinobi.copy()#copy the set values in other set
print(ninja)
ninja.clear()#clear the set
print(ninja)
ninja=shinobi.copy()

#union and intersecton update method 
#union make new set with given two sets and remove the duplicate
set3=shinobi.union(ninja)
print(set3)
set4=shinobi.intersection(ninja)#return comman values 
print(set4)

#check subset or uperset symmetric differnces
print(set3.issubset(set4))
print(shinobi.issuperset(ninja))
print(set3.symmetric_difference(set4))


# Practical 10: Write program to Experiment om different comprehension on list ,set and Dictionary

# list comprehensive 

#using list comprehencen find odd 

number = [1,2,3,4,5,6,7,8,9,10]

odd=[var for var in number if var%2!=0]

print(odd)

#create list using comprehence

num=[var for var in range(1,10)]

print(num)



# set comprehensive

#find using set comprehensive 

even_set={ var for var in number if var%2==0 }

print(even_set)

#create set using comprehensive 

num={ var for var in range(11,21)}

print(num)

# dictionary comprehensive


#fing name of 8th class student using comprehensive

name=["ironman","thor","itachi","shouyo","madara","naruto","gon","viren"]

std=[1,2,3,4,5,6,7,8]

find_name={ key:value for(key,value) in zip(std,name) if key==8}

print(find_name)

find_std={ key:value for(key,value) in zip(std,name) if value=="shouyo"}

print(find_std)


