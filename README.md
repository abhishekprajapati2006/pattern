# pattern
#include<bits/stdc++.h>
using namespace std;

void pattern1(){
    int n;
    cout<<"Enter the number:";
    cin>>n;
    for(int i=1; i<=n; i++){
        for(int j=1; j<=n; j++){
            cout<<"*";
        }
        cout<<endl;
    }
    pattern2();
}
void pattern2(){
    int n;
    cout<<"Enter the number:";
    cin>>n;
    for(int i=1; i<=n; i++){
        for(int j=1; j<=i; j++){
            cout<<"*";
        }
        cout<<endl;
    }
    
}
void pattern3(){
    int n;
    cout<<"Enter the number:";
    cin>>n;
    for(int i=1; i<=n; i++){
        for(int j=1; j<=i; j++){
            cout<<j<<" ";
        }
        cout<<endl;
    }
    pattern4();
}
void pattern4(){
    int n;
    cout<<"Enter the number:";
    cin>>n;
    for(int i=1; i<=n; i++){
        for(int j=1; j<=i; j++){
            cout<<i<<" ";
        }
        cout<<endl;
    }
    pattern5();
}
void pattern5(){
    int n;
    cout<<"Enter the number:";
    cin>>n;
    for(int i=1; i<=n; i++){
        for(int j=1; j<=n-i-1; j++){
            cout<<"*";
        }
        cout<<endl;
    }
    pattern6();
}
void pattern6(){
    int n;
    cout<<"Enter the number:";
    cin>>n;
    for(int i=1; i<=n; i++){
        for(int j=1; j<=n-i-1; j++){
            cout<<j<<" ";
        }
        cout<<endl;
    }
    pattern7();
}
void pattern7(){
    int n;
    cout<<"Enter the number:";
    cin>>n;
    for(int i=1; i<=n; i++){
        for(int j=1; j<=n-i-1; j++){
            cout<<i<<" ";
        }
        cout<<endl;
    }
    pattern8();
}
void pattern8(){
    int n;
    cout<<"Enter the number:";
    cin>>n;
    for(int i=1; i<=n; i++){
        for(int j=1; j<=n-i-1; j++){
            cout<<" ";
        }
        for(int j=1; j<=2*i+1; j++){
            cout<<"*";
        }
        for(int j=1; j<=n-i-1; j++){
            cout<<" ";
        }
        cout<<endl;
    }
    pattern9();
}
void pattern9(){
    int n;
    cout<<"Enter the number:";
    cin>>n;
    for(int i=1; i<=n; i++){
        for(int j=1; j<=n-i-1; j++){
            cout<<"*";
        }
        for(int j=1; j<=2*i+1; j++){
            cout<<" ";
        }
        for(int j=1; j<=n-i-1; j++){
            cout<<"*";
        }
        cout<<endl;
    }
    pattern10();
}
void pattern10(){
    int n;
    cout<<"Enter the number:";
    cin>>n;
    for(int i=1; i<=n; i++){
        for(int j=1; j<=i; j++){
            cout<<" ";
        }
        for(int j=1; j<=2*n-(2*i+1); j++){
            cout<<"*";
        }
        for(int j=1; j<=i; j++){
            cout<<" ";
        }
        cout<<endl;
    }
    cout<<endl;
    pattern11();
}
void pattern11(){
    int n;
    cout<<"Enter the number:";
    cin>>n;
    for(int i=1; i<=n; i++){
        for(int j=1; j<=i; j++){
            cout<<"*";
        }
        for(int j=1; j<=2*n-(2*i+1); j++){
            cout<<" ";
        }
        for(int j=1; j<=i; j++){
            cout<<"*";
        }
        cout<<endl;
    }
    cout<<endl;
    pattern12();
}
void pattern12(){
    int n;
    cout<<"Enter the number:";
    cin>>n;
    for(int i=1; i<=n; i++){
        for(int j=1; j<=n-i-1; j++){
            cout<<" ";
        }
        for(int j=1; j<=2*i+1; j++){
            cout<<"*";
        }
        for(int j=1; j<=n-i-1; j++){
            cout<<" ";
        }
        cout<<endl;
    }
    for(int i=1; i<=n; i++){
        for(int j=1; j<=i; j++){
            cout<<" ";
        }
        for(int j=1; j<=2*n-(2*i+1); j++){
            cout<<"*";
        }
        for(int j=1; j<=i; j++){
            cout<<" ";
        }
        cout<<endl;
    }
    pattern13();
}
void pattern13(){
    int n;
    cout<<"Enter the number:";
    cin>>n;
    for(int i=1; i<=n; i++){
        for(int j=1; j<=i; j++){
            cout<<"*";
        }
        cout<<endl;
    }
    for(int i=1; i<=n; i++){
        for(int j=0; j<=n-i-1; j++){
            cout<<"*";
        }
        cout<<endl;
    }
    pattern14();
}
void pattern14(){
    int n;
    cout<<"Enter the number:";
    cin>>n;
    for(int i=1; i<=2*n-1; i++){
        int stars=i;
        if(i>n)stars=2*n-i;
        for(int j=1; j<=stars; j++){
            cout<<"*";
        }
        cout<<endl;
    }
    pattern15();
}
void  pattern15(){
    int n;
    cout<<"Enter the number:";
    cin>>n;
    int stars=1;
    for(int i=1; i<=n; i++){
        if(i%2==0)stars=1;
        else stars=0;
        for(int j=1; j<=i; j++){
         cout<<stars;
          stars =1-stars;
        }
        cout<<endl;
    }
    pattern16();
}
void  pattern16(){
    int n;
    cout<<"Enter the number:";
    cin>>n;
    int stars=1;
    for(int i=1; i<=n; i++){
        if(i%2==0)stars=1;
        else stars=0;
        for(int j=1; j<=n-i-1; j++){
         cout<<stars;
          stars =1-stars;
        }
        cout<<endl;
    }
    pattern17();
}
void pattern17(){
    int n;
    cout<<"Enter the number:";
    cin>>n;
    int spaces=2*n-1;
    for(int i=1; i<=n; i++){
        for(int j=1; j<=i; j++){
            cout<<j;
        }
        for(int j=1; j<=spaces; j++){
            cout<<" ";
        }
        for(int j=i; j>=1; j--){
            cout<<j;
        }
        cout<<endl;
        spaces-=2;
    }
    pattern18();
}
void pattern18(){
    int n;
    cout<<"Enter the number:";
    cin>>n;
    for(int i=1; i<=n; i++){
        for(int j=1; j<=n-i-1; j++){
            cout<<i;
        }
        for(int j=1; j<=2*i+1; j++){
            cout<<" ";
        }
        for(int j=1; j<=n-i-1; j++){
            cout<<i;
        }
        cout<<endl;
    }
    pattern19();
}
void pattern19(){
    int n;
    cout<<"Enter the number:";
    cin>>n;
    int number=1;
    for(int i=1; i<=n; i++){
        for(int j=1; j<=i; j++){
            cout<<number<<" ";
            number+=2;
        }
        cout<<endl;
    }
    pattern20();
}
void pattern20(){
    int n;
    cout<<"Enter the number:";
    cin>>n;
    int number=1;
    for(int i=1; i<=n; i++){
        for(int j=1; j<=n-i-1; j++){
            cout<<number<<" ";
            number+=2;
        }
        cout<<endl;
    }
    pattern21();
}
void pattern21(){
    int n;
    cout<<"Enter the number:";
    cin>>n;
    char ch = 'A';
    for(int i=0; i<=n; i++){
        for(char ch='A'; ch<='A'+i; ch++){
            cout<<ch<<" ";
        }
        cout<<endl;
    }
    pattern22();
}
void pattern22(){
    int n;
    cout<<"Enter the number:";
    cin>>n;
    char ch = 'A';
    for(int i=0; i<=n; i++){
        for(char ch='A'; ch<='A'+n-i-1; ch++){
            cout<<ch<<" ";
        }
        cout<<endl;
    }
    pattern23();
}
void pattern23(){
    int n;
    cout<<"Enter the number:";
    cin>>n;
    char ch='A';
    for(int i=1; i<=n; i++){
        for(int j=1; j<=i; j++){
            cout<<ch<<" ";
        }
        cout<<endl;
        ch++;
    }
    pattern24();
}
void pattern24(){
    int n;
    cout<<"Enter the number:";
    cin>>n;
    char ch='A';
    for(int i=1; i<=n; i++){
        for(int j=1; j<=n-i-1; j++){
            cout<<ch<<" ";
        }
        cout<<endl;
        ch++;
    }
    pattern25();
}
void pattern25(){
    int n;
    cout<<"Enter the number:";
    cin>>n;
    char ch='A';
    for(int i=1; i<=n; i++){
        for(int j=1; j<=n-i-1; j++){
            cout<<" ";
        }
        for(int j=1; j<=2*i+1; j++){
            cout<<ch<<" ";
        }
        for(int j=1; j<=n-i-1; j++){
            cout<<" ";
        }
        cout<<endl;
        ch++;
    }
}
int main (){
    pattern1();
    return 0;
}
