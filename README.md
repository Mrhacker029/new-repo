# new-repo
This code is writen in c programming
It is used to collect user info of employees, students or any group.

#include <stdio.h>
#include <stdlib.h>
#include <ctype.h>
#include <string.h>
#include <math.h>
#include "shlok_info.h"

 int main()
{
 struct user shlok;
 struct user fernando;

 shlok.userid = 1;

 puts("ENTER THE FIRST NAME OF USER 1");
 gets(user.firstname);
 puts("ENTER THE LAST NAME OF USER 1");
 gets(user.lastname);

 printf("User %d's name is %s and last name is %s", shlok.userid, shlok.firstname, shlok.lastname);

 return 0;
}



Shlok's info file


struct user{
 int userid;
 char firstname[25];
 char lastname[25];
 int age;
 float weight;
 };
