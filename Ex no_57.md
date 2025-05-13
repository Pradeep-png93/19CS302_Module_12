# EX 57 WRITE A FUNCTION TO PUSH AN ELEMENT IN STACK USING LINKED LIST.( STORE FLOAT DATA IN STACK
## AIM:
To write a C function to perfom push,pop and peek functions in Stack using Linked List.

## Algorithm
1.	Start.
2.	Define a variables.
3.	Write a program to push an element in stack using linked list.
4.	Read the value using scanf.
5.	Ask the user to make an input.
6.	Print out the answer.
7.	End

## Program:
```
struct Node
{
float data;
struct Node *next;
}*head;
void push(float data)
{
struct Node *temp;
temp=(struct Node*)malloc(sizeof(struct Node));
 if(temp==NULL)
{
temp->data=data; temp->next=NULL;
 head=temp;
}
else
{
temp->data=data; temp->next=head;
 head=temp;
}

}

```

## Output:

![image](https://github.com/user-attachments/assets/acc74c12-df9f-479a-a8a7-ab6d3026e330)


## Result:
Thus the program was executed and the output was verified successfully.
