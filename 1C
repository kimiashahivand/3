#include <iostream>
#include <cmath>

int main() {
    double x;
    std::cout << "x ra vared konid (radian): ";
    std::cin >> x;

    double left = std::cos(2.0 * x);
    double right = 2.0 * std::cos(x) * std::cos(x) - 1.0;

    std::cout << "cos(2x) = " << left << std::endl;
    std::cout << "2cos^2(x)-1 = " << right << std::endl;

    if (std::fabs(left - right) < 1e-9)
        std::cout << "Rabete bargharar ast." << std::endl;
    else
        std::cout << "Rabete bargharar nist." << std::endl;

    return 0;
}
