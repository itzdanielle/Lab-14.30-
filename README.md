# Lab-14.30-
#include <iostream>
using namespace std;

int main() {
int time = 0;
double sec = 0;
double distance;
cout << "Please input the time of fall in seconds:" << endl;
cin >> time;

cout << endl << endl;

cout << "Time Falling (seconds)  Distance Fallen (meters)" << endl;
cout << "**********************  ************************" << endl;

for (int sec = 0; sec <= time; sec++) {
  
  distance = 0.5 * 9.8 * (sec * sec);
cout << sec << "                       " << distance << endl;
}




}
