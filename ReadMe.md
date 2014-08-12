USB-CDC-Template-18F45k50
=========================
This project is the same from Microchip Library Application, but files are extracted that are specific to PIC18F45K50. When plugged in with with the current firmware the micro-controller will look like a COM port. No drivers required since the PC will treat it as a COM port and use the driver suitable to run a COM port.


*How to use*
------------
You need
	-MPLAB X
	-XC8 Compiler

In main.c file there is a function called CustomTask. User code should go in there.

void CustomTask()
{
	//User Code goes here
}


