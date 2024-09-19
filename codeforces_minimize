#include <stdio.h>
#include <stdlib.h>
int main()
{
    int i,j,t,k,a,b,c;
    scanf("%d", &t);

    for (i = 0; i < t; i++)
    {
        int tab[2];
        int count[1];

        scanf("%d", &tab[0]);
        scanf("%d", &tab[1]);

        a = tab[0];
        b = tab[1];
        c = b;

        j = (c - a) + (b - c);

        while (c > a)
        {

            c--;
            k = (c - a) + (b - c);
            if (k < j)
            {
                j = k;
            }
        }
        count[0] = j;


            printf("%d ", count[0]);

       printf("\n");
     }

    return 0;
}
