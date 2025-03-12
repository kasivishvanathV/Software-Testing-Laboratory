# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:  12/03/2025
### REGISTER NUMBER : 212224230120

### AIM:  
To write python programs for do…while, while…do, for, switch and if…else and test with possible Test Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:

i) do…while:
```
def display():
     start=input("Enter a positive value for START: ")
      end=input("Enter a positive value for END: ")
      if start.isnumeric() and end.isnumeric():
        while True:
            start=int(start)
            end=int(end)
            print(start,end=‘ ‘)
            if start<end:
                start+=1
            else:
                break
      else:
        print("Enter a valid positive number.") 
  display()
```

ii) while…do
```
start=input("Enter a positive value for START: ") 
end=input("Enter a positive value for END: ")
if start.isnumeric() and end.isnumeric():
     start=int(start)
     end=int(end)
     while start<end:
          print(start)
          start+=1
else:
   print("Enter a valid positive number.")
```

iii) switch
```
def switch():
    switcher={
 0:"even",
  1:"odd"
}
n=input('Enter a value for N: ') try:
  n=int(n)
  print(switcher[n%2])
except ValueError:
   print("Enter a valid number.")
switch()
```

iv) if else
```
def compare():
  a=input("Enter a value for A: ")
  b=input("Enter a value for B: ")
  try:
     a=int(a)
     b=int(b)
     if a>b:
        print("A is greater than")
     elif a<b:
        print("B is greater than")
     else:
        print("A is equal to B")
  except ValueError:
        print(“Enter a valid number.”)
```

v) for
```
def iterate():
  string=input("Enter a string: ")
  for i in string:
    print(ord(i),end=" ")
iterate() 

```

### Output:

i) do…while:

![Screenshot 2025-03-12 211024](https://github.com/user-attachments/assets/3d21cd39-5b61-4858-8328-f0c864f7f818)

ii) while…do

![Screenshot 2025-03-12 211634](https://github.com/user-attachments/assets/a1976d00-7bb5-4737-88e9-7659414bb92d)

iii) switch

![Screenshot 2025-03-12 212151](https://github.com/user-attachments/assets/4ec1806c-f342-4bf7-8ea9-981aa12c689e)

iv) if else

![Screenshot 2025-03-12 212610](https://github.com/user-attachments/assets/bfd1c065-6642-42bc-b3ba-c8e1c5b0e515)

v) for

![Screenshot 2025-03-12 213401](https://github.com/user-attachments/assets/5cddb871-6b4b-419f-bd80-63cfab1ed5fb)

### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


