# GUN-CODE
A code for the winner 
n=list(map(str,input().split()))
l=n
l1=l[::2]
while(len(l1)!=1):
	if(l1[-1]==l[-1]):
		l=l1
		l1=l1[1::2]
	else:
		l=l1
		l1=l1[::2]
print(l1)		
