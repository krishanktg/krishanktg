- š Hi, Iām @krishanktg
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
krishanktg/krishanktg is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

#Max remainder from a list

l=[2,3,3,5,9]
r=[]
n=7
for i in l:
    r.append(i%n)
for i in range(4):
    r.append((l[i]+l[(i+1)])%n)
for i in range(3):
    r.append((l[i]+l[(i+1)]+l[(i+2)])%n)
for i in range(2):
    r.append((l[i]+l[(i+1)]+l[(i+2)]+l[(i+3)])%n)

r.append(sum(l)%n)


print(max(r))
print(r)

