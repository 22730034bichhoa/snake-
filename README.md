# snake
#include <studio.h>
#include <window.h>
#include <conio.h>
#include <string.h>
#include <time.h>
struct ToaDo
{
int x,y;
};
ToaDo Head,tail,Body;
ToaDo TD[401];
int demTD=0,demV=90;
int DoDai=2,CheckAnV=0,CheckV=0,ktDoAn=0;
int DiemCT=0,Diem0LD=0,DiemV=0;
ToaDo DoAn,DoAnV=0;
int doKho=100;
int wherey ()
{
CONSOLE_SCREEN_BUFFER_INFO coninfo;
GetConsoleScreenBufferInfor (GetStdHandle(STD_OUTPUT_HANDLE), &coninfo);
