# fibonacci-serise
n = int(input())
a = 0
b = 1
s = 0
print(a)
print(b)
for i in range(n):
    s = a + b
    print(s)
    a = b
    b = s
