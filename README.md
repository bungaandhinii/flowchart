## Deret Bilangan

#include <iostream>
using namespace std;
  
  
int main(int argc, char**argv) {
        int n, f1=0, f2=1, berikutnya=0;
  
        cout<<"masukkan deret bilangan:";
                cin>>n;
                cout<<endl;
  
        cout<<"deret bilangan:";
        for(int i=1; i<=n; ++i)
        
        {
                if(i==1)
                {
                        cout<<""f1<<"";
                        continue;
                }
                if(i==2)
                {
                cout<<""<<f2<<"";
                        continue;
                }
                selanjutnya=f1+f2;
                f1 = f2;
                f2=berikutnya;
                cout<<berikutnya<"";
  
        }
        return 0;
  }


