# Piyush Keshari
## sec -> C Roll-No -> 11

# one.sh

```bash
#!/bin/bash
echo $PPID #returns the pId of the current process's parent process
echo $$ #returns the pId of the current process
echo $0 #returns the name of the current process
echo $# #returns the no of total input from the user
echo $@ #returns the all the input from the user
echo $* #returns the all the input from the user
echo $1 #returns the value of 1st argument from the user
echo $2 #returns the value of 2nd argument from the user
echo $3 #returns the value of 3rd argument from the user
echo "$(bash two.sh)"
```
# two.sh

```bash
#!/bin/bash
echo "Current process name is $0 and it's pID is $$"
echo "current process's parent pID is $PPID"
```

# Output

![output](./output.png)