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
````ruby
s = str(input())
l = len(s)
print (s[l//2 + l % 2:] + s[:l//2 + l % 2])
````
----
````ruby
s = input()
cnt = 0
for i in range (len(s)):
    if s[i]!=s[i].upper():
        if s[i] not in '1234567890':
            cnt +=1
print (cnt)
````
----
