# Assignment-3.2
a=[i for i in "ACADGILD"]
b=[i*j for i in "xyz" for j in range(1,5)]
c=[b[i] for i in (0,4,8,1,5,9,2,6,10,3,7,11)]
d=[[i+j] for i in range(1,4) for j in range(1,4)]
e=[[i for i in range(2,6)],[i for i in range(3,7)],[i for i in range(4,8)],[i for i in range(5,9)]]
f=[(i,j) for j in range(1,4) for i in range (1,3)]
print (a)
print (b)
print(c)
print(d)
print(e)
print(f)
