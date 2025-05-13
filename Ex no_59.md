# EX 59 : WRITE FUNCTIONS TO PERFORM-ENQUEUE, DEQUEUE, PEEK, DISPLAY IN QUEUE USING LINKED LIST.(USE CHARACTER DATA IN QUEUE).
## AIM:
To write a C functions to perform-enqueue, dequeue, peek, display in Queue using Linked List.

## Algorithm
1.	Start.
2.	Define a variables.
3.	Write a functions to perform enqueue, dequeue,peek,display, in Queue using linked list.
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
void enqueue(char data)
{
struct Node *n=(struct Node*)malloc(sizeof(struct Node));
n->data=data;
n->next=NULL;
if(front==NULL)
{
front=rear=n;
}
else
{
rear->next=n;
rear=n;
}
}
Void display()
{
struct Node *temp;
temp=front;
if(temp==NULL)
{
printf("queue elements:\n");
}
else
{
printf("queue elements:\n");
while(temp!=NULL)
{
printf("%c\n",temp->data);
temp=temp->next;
}
}
}
void dequeue()
{
struct Node *temp;
temp=front;
if(temp==NULL)
{
printf("queue is empty\n");
}
else
{
front=temp->next;
free(temp);
}
}
void peek(){
printf("peek:");
printf("%c\n",front-
>data);}
```

## Output:

![image](https://github.com/user-attachments/assets/247e9c30-5a4b-40e8-ae7a-3a18fac4cad5)


## Result:
Thus the program was executed and the output was verified successfully.
