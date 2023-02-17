# HexawareQUE

limit=int(input('enter the number'))
l1=[]
sum=0
for i in range(1,20):
   if limit % i == 0:
        for j in range( 2,limit):
            if i % j ==0:
                l1.append(i)
            else:
                False
   else:
       pass
for i in l1:
    a=l1.count(i)
    if a == 1:
        sum+=i
print(sum)
