
"""Exercise 2 :-Create a python program capable of greeting you with Good Morning 
,Good Afternoon and Good Evening your program should use time module to get the current hour"""
# I learned this program from code with harry youtube channel
import time
t=time.strftime('%H:%M:%S')
hour=int(time.strftime('%H'))
hour=int(input("Enter hour:"))
print(hour)
if(hour>=0 and hour<12):
    print("Good Morning Sir!")
elif(hour>=12 and hour<17):
    print("Good Afternoon Sir!")
elif(hour>=17 and hour<0):
    print("Good Night Sir!")