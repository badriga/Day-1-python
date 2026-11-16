# Day-1-python
#int
a=10
b=20
c=a+b
print(c)
print(type(c))



#arithmetic operator
a=10
b=25
print("add:",a+b)
print("sub:",a-b)
print("multi:",a*b)
print("division:",a/b)
print("modulus:",a%b)
print("floor division:",a//b)
print("expo:",a**b)

#find the last digit
a=123
b=a%10
print("last digit:",b)

#remove last 2 digit
a=123
b=a//100
print("remove:",b)

#comparison
a=2
b=2
print(a==b)
print(a!=b)
print(a>b)
print(a>=b)
print(a==b)
print(a<b)
print(a<=b)

#logical
x=5
y=2
#and
print(x>10 and y<5)
print(x>=5 and y<5)

#or
print(x>10 or y<5)

#not
print(not(y==2))
print(not(y!=2))

#assignment
a=5
a+=2
a-=3
a*=4
print(a)

#identify operator
a=[3,7]
b=a
c=[3,7]
print(a is b)
print(a is c)
print(a is not c)

#membership operator
x=["hii","hello","ok"]
print("hii" in x)
print("hiii" in x)
print("hiiii" not in x)

#bitwise
a=3
b=2
print("AND:", a & b)
print("OR:", a | b)
print("XOR:", a ^ b)
print("NOT:", ~a)








