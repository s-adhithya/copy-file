# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM:
Step 1:
Open one file called testpro. txt in read mode.   
Step 2:
Open another testpro2. txt in write mode. 
Step 3:
Read each line from the input file and write it into the output file.
Step 4:
Exit. 
## PROGRAM:
```python
To write a python program for copy file
with open('testpro.txt','r') as firstfile:
    with open('testpro2.txt','a') as secondfile:
    # read content from first file
        for line in firstfile:
        # append content to second file
            secondfile.write(line)
```

## OUTPUT:
![output](/output.png)
![output](/output2.png)
![output](/filename19.png)
## RESULT:
Thus the program is written to copy the contents from one file to another file.