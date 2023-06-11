# 5th
#include<iostream>
using namespace std;

// Patterns Problems

//1. Rectangular pattern
// int main(){
//     int n,m;
//     cout<<"Enter the colums : ";
//     cin>>n;
//     cout<<"Enter the rows : ";
//     cin>>m;
//     for(int i=1;i<=m;i++){
//         for(int j = 1;j<=n;j++){
//             cout<<"* ";
//         }
//         cout<<endl; 
//     }
//     return 0;
// }


// Q2. To print a frame/ hollow rectangle

// int main(){
//     int n,m;
//     cout<<"Enter the colums : ";
//     cin>>n;
//     cout<<"Enter the rows : ";
//     cin>>m;
//     for(int i=1;i<=m;i++){
//         for(int j = 1;j<=n;j++){
//             if(i==1 || i==m || j==1 || j==n){
//                 cout<<"*";
//             }else{
//                 cout<<" ";
//             }
//         }
//         cout<<endl; 
//     }
//     return 0;
// }


// For triangular pattern

// int main(){
//     int m;
//     cout<<"Enter the rows : ";
//     cin>>m;
//     for(int i=1;i<=m;i++){
//         for(int j = 1;j<=i;j++){
//             cout<<"*";
//         }
//         cout<<endl; 
//     }
//     return 0;
// }



// Q4. Inverted Triangle pattern
// int main(){
//     int m;
//     cout<<"Enter the rows : ";
//     cin>>m;
//     for(int i=m;i>=1;i--){
//         for(int j = 1;j<=i;j++){
//             cout<<"*";
//         }
//         cout<<endl; 
//     }
//     return 0;
// }


// A centered triangle

// int main(){
//     int n;
//     cin>>n;

//     for(int i=1;i<=n;i++){
//         for(int j=1;j<=(n-i);j++){// this is for the spaces
//             cout<<" ";
//         }
//         for(int j = 1;j<=2*i-1;j++){// this is for the stars
//             cout<<"*";
//         }
//         cout<<endl;
//     }
//     return 0;
// }


// Numerical rectangle pattern

// int main(){
//     int n;
//     cin>>n;

//     for(int i=1;i<=n;i++){
//         for(int j=i;j<=n;j++){// this is for the spaces
//             cout<<j;
//         }
//         for(int j = 1;j<=(i-1);j++){// this is for the stars
//             cout<<j;
//         }
//         cout<<endl;
//     }
//     return 0;
// }

// Numerical same pattern printing
// int main(){
//     int n;
//     cin>>n;

//     for(int i=1;i<=n;i++){
//         for(int j=1;j<=n;j++){// this is for the spaces
//             cout<<j;
//         }
//         cout<<endl;
//     }
//     return 0;
// }

// Numerical hollow rectangle printing

// int main(){
//     int n;
//     cin>>n;

//     for(int i=1;i<=n;i++){
//         for(int j=1;j<=n;j++){// this is for the spaces
//             if(i==1 || i==n || j==1 || j==n){
//                 cout<<j;
//             }else{
//                 cout<<" ";
//             }
//         }
//         cout<<endl;
//     }
//     return 0;
// }

// Q9. Pattern Printing
int main(){
    int n;
    cin>>n;
    

    for(int i=1;i<=n;i++){
        for(int j=1;j<=(n-i);j++){// this is for the spaces
            cout<<" ";
        }
        for(int j=1;j<=i;j++){
            cout<<j;
        }
        for(int j=(i-1);j>=1;j--){
            cout<<j;
        }
        cout<<endl;
    }
    return 0;
}
