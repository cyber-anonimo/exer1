# exer1
#include<iostream>

using namespace std;

float soma(float a, float b){
	
	return a + b;
}

float divisao(float a, float b){
	
	return a / b;
}

float multiplicao(float a, float b){
	
	return a * b;
}

float subtracao(float a, float b){
	return a - b;
}

int main(){
     
     float num1 = 0;
	 float num2 = 0;
	 
	 cout << "digite o 1 numero: \n";
       cin >> num1;
	 cout << "digite o 1 numero: \n";
       cin >> num2;
	 
	cout << "subtracao: " << subtracao(num1, num2) << "\n";
	cout << "multiplicao: " << multiplicao(num1, num2) << "\n";
	cout << "divisao: " << divisao(num1, num2) << "\n";
system("pause");
return 0;
}
