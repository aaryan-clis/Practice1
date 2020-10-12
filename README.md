# Practice for git and github
we have created this to work together and learn git in advance.
so we will be posting git commands and solution to solve merge querys.
#include<iostream.h>
#include<conio.h>
#include<iomanip.h>
const int N=10;
void main()
{
      clrscr ();
      int a[N],i,k;
      cout<<"Enter ten numbers:\n";
      for(i=0;i<N;i++)
            cin>>a[i];
      cout<<"\n The given list is :\n";
      for (i=0;i<N;i++)
         cout<<setw(4)<<a[i];
         for(i=0;i<N-1;i++)
         {
            for (k=0;k<N-1;k++)
            {
              if (a [k]>a[k+1])
              {
                 int t=a[k];
                 a[k]=a[k+1];
                 a[k+1]=t;
                 }
               }  
             }  
       cout<<"\n\n The list is in ascending order is:\n"
       for (i=0;i<N;i++)
       cout <<setw(4)<<a[i];
       getch();
