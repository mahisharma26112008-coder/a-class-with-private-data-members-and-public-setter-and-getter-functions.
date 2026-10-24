# a-class-with-private-data-members-and-public-setter-and-getter-functions.

#include<iostream>
 using namespace std;
  class cafe{
      private:
      int chai;
      int cofee;  

      public:
      void setdata(int c,int C){
          cofee=c;
          chai=C;
      }

      int  getcofee(){
          return cofee;
      }

      int getchai(){
          return chai;
      }
  
};

int main(){
    cafe c1;

    c1.setdata(100,120);

    cout<<"price of cofee : "<<c1.getcofee()<<"\n";
    cout<<"price of chai :  "<<c1.getchai()<<"\n";

    return 0;
}
