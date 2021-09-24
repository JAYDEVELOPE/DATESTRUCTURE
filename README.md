# DATESTRUCTURE
Ds c program 
Develop simple program using pointer to structure
Pointer to structure

#include <stdio.h>
int main(int argc, char *argv[])
{

struct student_database {
    char name[10];
    int roll;
    int marks;
}stud1 = {"Pritesh",90,90};

struct student_database *ptr;
ptr = &stud1;

printf("Roll Number : %d",(*ptr).roll);
printf("Marks of Student : %d",(*ptr).marks);

return 0;
}
Output :
Roll Number : 90
Marks of Student : 90
