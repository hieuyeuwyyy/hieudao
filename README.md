import random as rd
n=int(input(" nhap so phan tu cua day, N ="))
a=[0]*n
for i in range(n):
        a[i] = rd.randint(-300,300)

print(" mang A")
print(*a)

a.sort(reserve=True);
print(" in theo thu tu giam dan ",*a)

tong_chan=0
for j in a;
   if(j%2==0): tong_chan +=j
