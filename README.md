# cplus2.0-do_whileloop
what num entered will be counted except the num entered

#include <iostream>
using namespace std;

int main()
{
     int i=1;
     int grade;
     
     cout<<"Enter a number: \n";
     cin>> grade;
     
     do{
          cout <<i<<endl;
          i++;
          
     }
     while (i!=grade);

     return 0;
}
  /*output:
  
  Enter a number: 
  5
  1
  2
  3
  4
  */
  
