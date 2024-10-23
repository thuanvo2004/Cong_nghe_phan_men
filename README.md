#bai2_buoi1
n =int(input("nhap n="))
a=[int(input(f'a[{i}]=')) for i in range(n)]
d= [x for x in a if x>0]
print( f"So duong lon nhat :", max(d) if len(d)>0 else "*")

for x in set(a):
    print(f"{x} xuat hien {a.count(x)} lan")

a.sort(reverse =True)
print(a)
