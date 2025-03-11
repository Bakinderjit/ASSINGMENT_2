#1
x=int(input("Enter a number :"))
if x%2==0:
    print(f"{x}is an Even number.")
else:
    print(f"{x} is an Odd number.")

#OUTPUT
Enter a number :7
7 is an Odd number.


##2
sum=0
for i in range (1,51):
    sum+= i
print(f"The sum of all integers from 1 to 50 is  :{sum}")

##OUTPUT
The sum of all integers from 1 to 50 is  :1275
