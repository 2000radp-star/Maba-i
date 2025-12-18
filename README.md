#include < iostream >
using namespace std ;
main ()
{
int number ; 
cout << " enter numbers ( enter o to stop ) : " << endl ;
while ( true ) 
{ cin >> number ; 
if  ( number== 0 ) {
}
if ( number % 3  ! = 0 ) {
cout << " result : " << number << " is not a multiple of 3 . " << endl ; 
}
}
cout << " program finished ." << encl ;
return ; 
}
