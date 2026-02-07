#include<iostream>
#include<string>
using namespace std;
string username="Usman";
string password="us2119";
int main()
{
    cout<<"\t\t***Log In***\t\t";
    cout<<"\n\nEnter your username: ";
    string inputUsername;
    getline(cin,inputUsername);
    cout<<"Enter your password: ";
    string inputPassword;
    getline(cin,inputPassword);
    if(inputUsername==username &&inputPassword==password)
    {
        cout<<"Welcome to the Gym Management System, Usman!\n Let's Start Program."<<endl;
    }
    else
    {
        cout<<"Invalid username or password. Please try again."<<endl;
    }

return 0;

}
