# Binary-Parity
# cook your dish here
for i in range(int(input())):
    x = int(input())
    y = bin(x)
    z = y.count("1")
    if z%2==0:
        print("EVEN")
    else:
        print("ODD")
