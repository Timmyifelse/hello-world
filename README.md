#include "stdafx.h"
#include <iostream>
#include <conio.h>
using namespace std;

int main()
{
	//\/\/\/\/\/\/\/\//\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/\/
	//\\//\\//\\//\\//Multiplication Calculator//\\//\\//\\//\\//\\/\//\/
	cout << "************This Program Multiplies All Three NUmbers You Type**************" << endl;
	int Number1, Number2, Number3, result;
	cout << "Enter The Value Of Number1 :";
	cin >> Number1;
	cout << "Enter The Value Of Number2 : ";
	cin >> Number2;
	cout << "Enter The Value Of Number3 : ";
	cin >> Number3;
	result = Number1 * Number2 * Number3;
	cout << "Their multiplication is : " << result << endl;
