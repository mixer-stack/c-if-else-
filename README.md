#include <iostream>
using namespace std;
int main()
{
//1
	int parne;
	cout << "\nvvedit chislio: ";
	cin >> parne;
	if (parne % 2 == 0)
	{
		cout << "\nchislo " << parne << " parne";
	}
	else
	{
		cout << "\nchislo " << parne << " ne parne";
	}
//2
	int pershe_2;
	int druge_2;
	cout << "\nvvedit pershe chislio: ";
	cin >> pershe_2;
	cout << "\nvvedit druge chislio: ";
	cin >> druge_2;
	if (pershe_2 > druge_2)
	{
		cout << druge_2 << " menshe chislo";
	}
	else if(pershe_2 < druge_2)
	{
		cout << pershe_2 << " menshe chislo";
	}
	else
	{
		cout << "chisla rivni";
	}
//3
	int chislo;
	cout << "\nvvedit chislio: ";
	cin >> chislo;
	if (chislo > 0)
	{
		cout << chislo << " dodatnye";
	}
	else if (chislo < 0)
	{
		cout << chislo << " vidyemne";
	}
	else
	{
		cout << "dorivnye nuly";
	}
//4
	int pershe_4, druge_4;
	cout << "\nvvedit dva chisla: ";
	cin >> pershe_4 >> druge_4;
	if (pershe_4 == druge_4)
	{
		cout << "chisla rivni";
	}
	else if (pershe_4 > druge_4)
	{
		cout << druge_4 << " , " << pershe_4;
	}
	else
	{
		cout << pershe_4 << " , " << druge_4;
	}
//5
	int persha, druga, tretya, chetverta, pyata;
	cout << "vvedit otsinki uchnya: ";
	cin >> persha >> druga >> tretya >> chetverta >> pyata;
	if ((persha + druga + tretya + chetverta + pyata) / 5 >= 4)
	{
		cout << "\n uchen dopushcheniy do ispitu ";
	}
	else
	{
		cout << "\n uchen ne dopushcheniy do ispitu ";
	}
//6
	int parne_6;
	cout << "\nvvedit chislio: ";
	cin >> parne_6;
	if (parne_6 % 2 == 0)
	{
		cout << (float)parne_6 * 3;
	}
	else
	{
		cout << (float)parne_6 / 2;
	}
//7
	int pershe_7, druge_7;
	string znak_7;
	cout << "vvedit vash priklad (pershe chislo)(+,-,*,/)(druge chislo): ";
	cin >> pershe_7 >> znak_7 >> druge_7;
	cout << "\n";
	if (znak_7 == "+")
	{
		cout << pershe_7 << " + " << druge_7 << " = " << pershe_7 + druge_7;
	}
	else if (znak_7 == "-")
	{
		cout << pershe_7 << " - " << druge_7 << " = " << pershe_7 - druge_7;
	}
	else if (znak_7 == "*")
	{
		cout << pershe_7 << " * " << druge_7 << " = " << pershe_7 * druge_7;
	}
	else if (znak_7 == "/")
	{
		cout << pershe_7 << " / " << druge_7 << " = " << pershe_7 / druge_7;
	}
	else
	{
		cout << "nekorektne vedennya";
	}
}

