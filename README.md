# structure
first code
#include<stdio.h>
#include<string.h>

struct student
{
    char name[20];
    int roll_no;
    float marks;
};
int main(void){

struct student stu1={"mohit",26,34};
struct student stu2,stu3;
strcpy(stu2.name,"rohit");
stu2.roll_no=32;
stu2.marks=98;
printf("enter the name and value of marks and roll no \n");
scanf("%s %d %f",stu3.name,&stu3.roll_no,&stu3.marks);
printf("stu1 : %s  %d %f \n",stu1.name,stu1.roll_no,stu1.marks);
printf("stu2 : %s  %d %f \n",stu2.name,stu2.roll_no,stu2.marks);
printf("stu3 : %s  %d %f \n",stu3.name,stu3.roll_no,stu3.marks);
return 0;
}
