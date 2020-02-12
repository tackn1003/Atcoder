T = input().split(" ")
s = T[0]

a,b = map(int,input().split(" "))
u = input()

if s == u:
  a += -1
else:
  b += -1

print("{} {}".format(a,b))







