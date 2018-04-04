# Assignment-3.2
a=[i for i in "ACADGILD"]
b=[i*j for i in "xyz" for j in range(1,5)]
c=[i*j for j in range(1,5) for i in "xyz"]
d=[[i+j] for i in range(1,4) for j in range(1,4)]
e=[[i for i in range(2,6)],[i for i in range(3,7)],[i for i in range(4,8)],[i for i in range(5,9)]]
f=[(i,j) for j in range(1,4) for i in range (1,4)]
print (a)
print (b)
print(c)
print(d)
print(e)
print(f)
