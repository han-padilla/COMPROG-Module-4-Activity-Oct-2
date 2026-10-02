// Problem 1, the Canteen Group Order
#include <iostream>
#include <iomanip>
using namespace std;

int main()
{
    float quantOrder, serviceCharge, noStudents;
    double mealPrice, subTotal, servChargeFee, finalBill, share;
   
    cout << "Enter the Meal Price: ₱";
    cin >> mealPrice;
    cout << fixed << setprecision(2) << "Meal Price: ₱" << mealPrice;
    //meal price
    
    cout << "\nEnter the Quantity of Meals Ordered:";
    cin >> quantOrder;
    cout << "You Ordered " << quantOrder << " Meals!";
    //number of ordered meals
    
    subTotal = mealPrice*quantOrder;
    cout << fixed << setprecision(2) << "\nYour Subtotal is ₱"<<subTotal;
    //subtotal price is done
    
    cout << "\nEnter the Service Charge Fee: ";
    cin >> serviceCharge;
    servChargeFee = subTotal*serviceCharge/100;
    cout << "\nThe Service Charge is ₱"<<servChargeFee;
    finalBill = (subTotal*serviceCharge/100) + subTotal;
    cout << fixed << setprecision(2) << "\nYour Final Bill is: ₱"<<finalBill;
    //final bill is done
    
    cout << "\nYou said you wanted to split the bill with your friends." << "\nHow many of you will be splitting the bill? :";
    cin >> noStudents;
    share = finalBill/noStudents;
    cout << fixed << setprecision(2) << "\nThere will be " << noStudents << " people splitting the bill, and all will pay ₱"<< share << " equally.";
    //final share between the students 
    
    return 0;
}
