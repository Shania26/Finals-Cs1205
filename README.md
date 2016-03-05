# Finals-Cs1205
#include <iostream>
#include <string>

const string NAME="admin";
   const string PASSWORD="admin";
   
   string username, password;
   
   cout<<"Enter username="<<"";
   cin>>username;
   
   if (username.length() < 5)
{
   
   cout<<"Invalid characters need atleast 5 above"<<"";
    return 0;
}
   else 
   
    cout<<"Enter password="<<"";
   cin>>password;
   
    if (password.length() < 5)
   {
   
   cout<<"Invalid characters need atleast 5 above"<<"";
    return 0;
}


   if ( username==NAME && password==PASSWORD)
   {

   system("CLS");
   
   Sleep(1000);
   cout<<"L"<<"";
     Sleep(1000);
   cout<<"O"<<"";
     Sleep(1000);
   cout<<"A"<<"";
     Sleep(1000);
   cout<<"D"<<"";
     Sleep(1000);
   cout<<"I"<<"";
     Sleep(1000);
   cout<<"N"<<"";
     Sleep(1000);
   cout<<"G"<<"";
     Sleep(1000);
   cout<<"."<<"";
   cout<<"."<<"";
   cout<<"."<<"";
   cout<<"."<<"";
}

return 0;

}
