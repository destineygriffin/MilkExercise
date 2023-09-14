# MilkExercise
programing unit 1 homework
#include <iostream>

using namespace std;

int main() {
    double tMilkProMorn;
    int numNeeded;
double cart=3.78;
double cost;
double cost1=.38;
double profit;
double profit1=.27;

    cin>>tMilkProMorn;
numNeeded=tMilkProMorn/cart;
cost=cost1*tMilkProMorn;
profit=numNeeded*profit1;

cout<<numNeeded;
cout<<" "<<cost<<" "<<profit;
    return 0;
}
