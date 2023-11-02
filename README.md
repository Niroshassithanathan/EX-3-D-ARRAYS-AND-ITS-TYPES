# EX-3-D-ARRAYS-AND-ITS-TYPES
## AIM :
Write a C program to delete last element in an array.
## ALGORITHAM :
1.Declare variables for the size of the array (size), an array (arr) to store elements, and a variable to store the new size after deletion (new_size).

2.Prompt the user to enter the size of the array (size) and read it into the variable.

3.Initialize the array with the given size.

4.If the array is empty (size is 0), print an error message and exit.

5.Decrement the size by 1 (new_size = size - 1).

6.Copy all elements from the original array to a new array of size new_size, excluding the last element.

7.Print the original array before deletion and the updated array after deletion.

8.End.
## PROGRAM :
```
#include<stdio.h>
int main(){
int a,i;
scanf("%d",&a);
int b[a];
for(i=0;i<a;i++) {
scanf("%d",&b[i]);
}
for(i=0;i<a-1;i++)
{
printf("%d ",b[i]);
}
return 0;
}
```
## OUTPUT :

![image](https://github.com/Niroshassithanathan/EX-3-D-ARRAYS-AND-ITS-TYPES/assets/121418437/bac3a1dd-1ac5-4523-bacb-0a7fa311a61e)

## RESULT :
Thus , The C program has been executed successfully.
