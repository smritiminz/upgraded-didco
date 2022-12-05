# upgraded-didco
d={}
n=int(input("enter no of students:"))
for i in range(n):
    name=input("Enter name:")
    x=list(map(int,input("enter marks:").split(',')))
    d[name]=x
d1={}
for i in d:
      d1[i]=sum(d[i])
    
    
print(d1)
