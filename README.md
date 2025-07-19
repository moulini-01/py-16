# py-16
printing T shape pattern using python
n=11
for i in range(n):
	for j in range(n):
		if(i==0) or (j==n-(n//1.5)):
		   print("*",end=" ")
		else:
			print(" ",end=" ")
	print()
