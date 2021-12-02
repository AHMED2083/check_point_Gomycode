# check_point_Gomycode

/* Algoritms and its items */

#include <str ing >
using namespace s td ;
// Compte l e nombre de mots dans une phrase
in t nombre_de_mots ( const s tr ing& phrase )
{
in t i = 0 , mots = 0;
while ( i < phrase . siz e ( ) )
{
while ( phrase [ i ] == ’ ’ )
i ++;
mots++;
while ( i < phrase . siz e ( ) && phrase [ i ] != ’ ’ )
i ++;
}
return mots ;
}
  
/* fin du check point */
