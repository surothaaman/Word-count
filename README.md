# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
```
Step 1: Define the variable to count the number of words in the file and defined with 0.
Step 2: Open the text file using the with open keyword.
Step 3: Using r command i.e:read mode.
Step 4: Using for loop iterate the file to split the space in the words.
Step 5: The splited and stored in the variable, use len() function of the splited word variable.
Step 6: End the program.
```

## PROGRAM:
```
'''
Developed by: SUROTHAAMAN R
Register number: 212222103003
'''
fname = input('Enter file name: ')
num_word = 0
with open(fname, 'r') as f:
    for line in f:
        word = line.split ()
        num_word += len(word)
print('Number of words: ', num_word)

```
### OUTPUT:
![image](https://github.com/surothaaman/Word-count/assets/133313653/88341cf6-b38e-4b21-876e-f29bb10d4e4f)
![image](https://github.com/surothaaman/Word-count/assets/133313653/23f21406-bb20-4e1f-b508-ecf6756e8929)





## RESULT:
Thus the program is written to find the word count from a text.
