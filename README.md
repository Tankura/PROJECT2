# PROJECT2
#INCLUDE<STDIO.H>
#INCLUDE<CONIO.H>
VOID MAIN()
{
FILE*fs; //1
char ch;
clrscr();
fs=fopen('strcopy.v","r");//2
if(fs==NULL)
{
 printf("can't open the source file\n");
 exit(1)
}
 while(1)
{
  ch=fgetch(s)
