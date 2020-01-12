#include "reg52.h"   

sbit led=P2^0;	  \\give LED a definition in your micro control system 51 series


void main()
{
	while(1)
	{
		led=0;	\\when you give LED a low elcectric potencial,and it light 
	}		
}
