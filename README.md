# Project-1-c-
#include <iostream> 
using namespace std;

void drawLine()
{
	cout << "  * \n";
	cout << "  * \n";
}
void drawTriangle()
{
	cout << "  *\n";
	cout << " *  *\n";
	cout << "*    *\n";
	cout << "*******\n";
}
void drawRectangle()
{
	cout << "********\n";
	cout << "*      *\n";
	cout << "*      *\n";
	cout << "********\n";
}

int main()
{
	cout << "Line:\n";
    drawLine();
	cout << "Triangle:\n";
    drawTriangle();
	cout << "Rectangle:\n";
	drawRectangle();
	cout << "Beaker\n";
	drawLine();
	drawTriangle();
	cout << "Fudge Bar:\n";
	drawRectangle();
	drawLine();
	cout << "Pine Tree:\n";
	drawTriangle();
	drawLine();
	cout << "House:\n";
	drawTriangle();
	drawRectangle();
	system("pause");
	return 0;
