#include<graphics.h>
#include<conio.h>
void main()
{
int gd=DETECT,gm;
initgraph(&gd,&gm,"C:\\TC\\BGI");
outtext("press any key to clear screen");
getch();
cleardevice();
outtext("press any key to exit");
getch();
closegraph();
}
