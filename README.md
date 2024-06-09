Text Sequence Type
==================
````ruby
n = input()
cnt = 0
for i in range(len(n)):
    cnt += int(n[i])
print(cnt)
````
-----
````ruby
s = input()
cnt = 0
for i in range(len(s)-1):
    if s[i] == s[i+1]:
        cnt +=1
print(cnt)

````
----
````ruby

n = int(input())
s = ""
while n != 0:
    s = str(n % 2) + s
    n = int(n/2)
print(s)

````
----
