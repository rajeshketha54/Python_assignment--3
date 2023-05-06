# Python_assignment--3
num=int(input())                                   # Input : 9
list_1=[]
count_even=0                                       # Sample input : [1, 2, 3, 4, 5, 6, 7, 8, 9]
count_odd=0
for x in range(num):
    num1=int(input())
    list_1.append(num1)
for x in range(num):                               # Expected output :  Number of even numbers : 4
     if list_1[x]%2==0:                            #                    Number of odd numbers : 5
         count_even += 1 
     else:
         count_odd += 1
print("Number of even numbers :",count_even)       # My output : Number of even numbers : 4
print("Number of odd numbers :",count_odd)         #             Number of odd numbers : 5
    
