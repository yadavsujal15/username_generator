
# this program is simple username gererator

import random
name= input("enter your name:  ")
year= int(input(" enter your birth year: "))
namepart= name[0:5]
rand_num= random.randint(10,99)
username= namepart+str(rand_num)

print("your new username",(username))

