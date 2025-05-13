# EX 60 WRITE FUNCTIONS TO PRINT THE PEEK ELEMENT IN QUEUE USING LINKED LIST
## AIM:
To write a C function to find the peek element of the queue using linked list.

## Algorithm
1.	Start.
2.	Define a variables.
3.	Write a functions to find peek in Queue using linked list.
4.	Read the value using scanf.
5.	Ask the user to make an input.
6.	Print out the answer.
7.	End

## Program:
```
struct Node
{
char data;
struct Node *next;
}*front=NULL,*rear=NULL;

void peek()
{
printf("peek:");
printf("%c\n",front->data);
}

```

## Output:

![image](https://github.com/user-attachments/assets/702f1af4-819f-47de-b227-3e477d564379)


## Result:
Thus the program was executed and the output was verified successfully.
