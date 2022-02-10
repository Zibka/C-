#include <iostream>

using namespace std;

int sqr(int x)
{
    int res;
    res = x * x;
    x = x * 20;
    return res;
}


int main()
{
    int a = 3;
    int b = 7;
    std::cout << sqr(5) << std::endl;
    std::cout << sqr(a) << std::endl;
    std::cout << "a = " << std::endl;
    std::cout << sqr(b) << std::endl;
    std::cout << sqr((a + b) / 2) << std::endl;

    int x = 2;
    sqr(x);
    std::cout << "x = " << x << std::endl;


    return 0;
}
  
