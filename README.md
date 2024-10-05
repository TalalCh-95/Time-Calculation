# Time-Calculation
In this repository there is code about what time is it and according to time the program calls you.

import time
t = time.strftime("%H:%M:%S")
hour = int(time.strftime("%H"))
#hour = int(input("Enter hour :"))
print(hour)

if (hour>=0 and hour<12):
  print("Good Morning Buddy")
  
elif(hour>=12 and hour<18):
  print("Good Afternoon Buddy")
  
elif(hour>=18 and hour<0):
  print("Good Night Buddy")





