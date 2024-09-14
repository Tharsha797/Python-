# Python-

#for loop
'''for i in range(8,16):
    print(i)
a=int(input("Enter the value of a"))
b=int(input("Enter the value of b"))
for i in range(a+1,15):
    print(i)'''

#for and if concept used
'''for i in range(1,11,):
    if(i%2==0):
        print(i)'''

#count
'''count=0
for i in range(1,11):
    if(i%2==0):
        count= count+1
print("even:",count)
if(i!=0):
        count=count+1
print("odd",count)'''

#another counter using if else
#note:the print statement should be straught to the starting line of the concept 
'''e_count=0
o_count=0
for i in range(1,11):
    if(i%2==0):
        e_count=e_count+1
    else:
        o_count=o_count+1
print(e_count)
print(o_count)'''


#the numbers are divisible by 3 and 5
count=0
for i in range (1,101):
    if(i%3==0 and i%5==0):
        count=count+1
print(count)
        
    
