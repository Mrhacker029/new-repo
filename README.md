# new-repo

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
 struct user amit;
 struct user jay;
 struct user varsha;
 struct user jaydeep;
 struct user avicii;
 struct user hardwell;
 struct user dimitary;
 struct user vegas;
 struct user likemike;
 struct user snake;
 struct user bucky;
 struct user callofduty;
 struct user emenim;
 struct user thuglife;
 struct user florida;
 struct user jaggs;

 shlok.userid = 1;

 puts("ENTER THE FIRST NAME OF USER 1");
 gets(shlok.firstname);
 puts("ENTER THE LAST NAME OF USER 1");
 gets(shlok.lastname);

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
