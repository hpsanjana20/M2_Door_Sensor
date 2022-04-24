
#include <avr/io.h>
int main(void)
{
	DDRB=DDRB&0b11111101; //& with fd to set first bit zero
	DDRC=DDRC|0b01000000; //OR with 40 to set DDRC's 6th bit high
	while(1)
	{
if(PINB & 0b00000010) //02
	PORTC=PORTC|0b01000000; //40
		else
		PORTC=PORTC&0b10111111; //bf
	}
	return 0;
	}
