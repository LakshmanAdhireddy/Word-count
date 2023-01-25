# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:
Open file in read mode.

Step 2:
Read the text using read funcion.

Step 3:
Split the text using space separator.

Step 4:
The length of the split list should be equal to the number of words in the text file.

Step 5:
Now give print().

Step 6:
End the program.
## PROGRAM:
~~~
developed by : Lakshman reddy

reference number: 22004423
num=0
with open("file1.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words are in the file is ",num)
~~~

### OUTPUT:
![output3](https://user-images.githubusercontent.com/118707265/214601745-d22961ec-0e25-4d03-a9ee-8675917c88ec.jpg)
![output12333](https://user-images.githubusercontent.com/118707265/214601819-c5cfd283-c918-4f0b-936c-0bdb74bc8ab9.jpg)

## RESULT:
Thus the program is written to find the word count from a text.
