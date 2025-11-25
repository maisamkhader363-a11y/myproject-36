#include<iostream>
#include<cctype>
using namespace std;


double isMax(double num3, double num2, double num1) {
	int max = num1;
	if (num2 > num1)
		max = num2;
	if (num3 > num2)
		max = num3;
	return max;
}

int main() {
	cout << "please enter 3 numbers to find the maximum" << endl;
	double num1, num2, num3;
	cin >> num1 >> num2 >> num3;
	cout << "Max number is:"<<isMax(num3, num2, num1);
	return 0;
}
