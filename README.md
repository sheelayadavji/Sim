# Sim
n=int(input("enter the no:"))
f=0
for i in range(2,n):
	if ((n%i)==0):
		f=1
		break
if(f==0):
			print(n,"is prime no.")
else:
			print(n,"is not a prime no.")
