a=[1,7,3,6,5,6]
total=sum(a)
left=0
for i in range(len(a)):
right=total-left-a[i]
if left==right:
print("equilibrium index:",i)
break
left+=a[i]
else:
print(-1)

output:
equilibrium index:3