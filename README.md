l = int(input())
u = int(input())

print("Prime numbers between", l, "and", u, "are:")

for i in range(l, u + 1):
   if i > 1:
       for j in range(2, i):
           if (i % j) == 0:
               break
       else:
           print(i)

