# python-assignment-1
fiboonic sequence

# case 1:USING WHILE LOOP

nterms = int(input("enter no of terms? "))
n1, n2 = 1, 1
count = 0
print("Fibonacci sequence:")
while count < nterms:
       print(n1)
       nth = n1 + n2
       # update values
       n1 = n2
       n2 = nth
       count += 1
       
 # case 2:USING IF CONDITION
 
 nterms = int(input("enter no of terms? "))
n1, n2 = 1, 1
count = 0
if nterms == 1:
   print("Fibonacci sequence upto",nterms,":")
   print(n1)
else:
    print("Fibonacci sequence:")
while count < nterms:
       print(n1)
       nth = n1 + n2
       # update values
       n1 = n2
       n2 = nth
       count += 1
       
case 3:

x,y=0,1

while y<50:
    print(y)
    x,y = y,x+y

 
