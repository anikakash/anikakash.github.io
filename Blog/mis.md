
## PassWord Generator

Sometimes we need to generate a strong password. So for this you can use this code.
Just copy this c++ code and run this [online ide](https://ideone.com/l/cpp){:target="\_blank"} 

```cpp

#include <bits/stdc++.h>
using namespace std;

int main(){
    string rendom = " )aAb^B+1c[Cd(9D`e#}Ef_2.F!g$Gh|Hi{\"I3j+Jk'KlL<4m\\~M@nN-o/O5,p&P:qQrR->6s;]tTu?U=7v!Vw[W%x8&XyYzZ`>{";
    cout << "PASSWORD LENGHT: ";
    int passlen;
    cin >> passlen;
    srand(time(NULL));
    for(int i = 0; i < passlen; i++){
        int j = rand() % 99 + 1;
        cout << rendom[j];
    }
    cout << endl;
}

```

## Find Last Digit

```cpp

#include<bits/stdc++.h>
using namespace    std;

int main(){
    int n=, lastDigit=0; 
    
    while(n>0){
        lastDigit = n%10;
        n=n/10;
    }
    cout<<lastDigit<<endl;
}

```