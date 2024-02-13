# patterns-10
    
a=[]
n=8
for i in range(2):
  x=[]
  for i in range(2):
    x.append(n)
    n=n-1
  a.append(x)
for i in a:
  print(*i,sep=" ")
