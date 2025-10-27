# abdoh
khffliugfk
#include <stdio.h>
#include <stdlib.h>

int main() {
    int  a, b, reste;                      //declaration les variable

    printf("Entrez les deux nombres :\n ");// donner a l'utilisateur d'entre deux nombres
    scanf("%d %d", &a, &b);
    int x = a;
    int y = b;

    while (y != 0) {
        reste = x % y;                     //calcule le reste
        x = y;                            //donner la valeure de (y) a (x)
        y = reste;                       // donner la valeure de (reste) a (y)
    }

    printf("Le plus grand commun diviseur entre (%d et %d) est : %d\n", a, b, x);//affichier le resultat

    return 0;
}
