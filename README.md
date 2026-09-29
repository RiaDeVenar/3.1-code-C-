# 3.5-code-C-
Подстановка любого числа в переменную x и y И обмен значений между ними
#include <iostream>
using namespace std;

int main()
{
    int x=0;
    int y=0;
    int d=0;
    cout << "Enter x: ";
    cin >> x;
    cout << "Enter y: ";
    cin >> y;
    d=x;
    x=y;
    y=d;
    cout << "x = " << x << ", y = " << y << endl;

    return 0;
}
