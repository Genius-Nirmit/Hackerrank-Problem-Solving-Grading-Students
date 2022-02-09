# Hackerrank-Problem-Solving-Grading-Students
#include<stdio.h>
struct my_data
{
    char name[20];
    int roll_number;
    char department[20];
};
void mydata(struct my_data *profile)
{
    printf("%s\t%d\t%s",profile->name,profile->roll_number,profile->department);
}
int main()
{
    struct my_data profile={"Nirmit",85,"Computer"};
    mydata(&profile);
    return 0;
}
