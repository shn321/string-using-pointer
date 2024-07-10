# string-using-pointer
#include<stdio.h>
#include<conio.h>
void main()
{

    int strlength(char*),toc;
    char str[80];
    printf("\n ENTER A STRING - ");
    gets(str);
    toc=strlength(str);
    printf("\n TOTAL CHARACTERS = %d",toc);
    getch();
}
int strlength(char*s)
{
    int tc=0;
    while(*s!='\0')
    {
        tc++;
        s++;
    }
    return tc;

}
