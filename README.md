# **Introduction**

We will learn to code in *markdown* language

## **What we will learn:**

1. Heading
    1. **##**
    2. **#**
1. Subheading
1. How to use these
---
## Code blocks ##
---
### To push code on remote Repo.

`git push -u origin master`

### To pull code from remote Repo

`git pull -u origin master`

### For multiline Code

``` py
#Fibonacci Series code
i = 0
first_value = 1
second_value = 2
number = int(input('enter any no.'))
while(i<number):
    if i<=1:
        next = i
    else:
        next = first_value + second_value
        first_value = second_value
        second_value = next
    print(next)
    i = i+1
```