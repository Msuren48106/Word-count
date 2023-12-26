# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:Create a file with .txt file extension.

### Step 2:Add some texts in that file.
 
### Step 3:Create a python file.

### Step 4:Write a code to count the number of words in that file.

### Step 5:Run the program.

### Step 6:Display the output.

## PROGRAM:
~~~
def program():
    count=0
    with open("text.txt","r") as f:
        for data in f:
            words=data.split()
            for word in words:
                count+=1
    print("Total number of words:",count)
program()
~~~

### OUTPUT:

![image](https://github.com/Msuren48106/Word-count/assets/150503875/024513ac-1f2c-4162-b147-1f20c7c13aa2)

![image](https://github.com/Msuren48106/Word-count/assets/150503875/d67a9ca8-8094-4b83-ac1e-47c2a60e22b1)



## RESULT:
Thus the program is written to find the word count from a text.
