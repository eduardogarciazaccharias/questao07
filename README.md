# questao07
#include <stdio.h>
#include <stdlib.h>

int main()
{
    int mat[4] = {1,2,3,4};
    int *p, x;
    p = mat+1;
    printf("%d\n",*p);
    x = (*mat)++;
    printf("%d\n",x);

    return 0;
}
as outra opções não deram certo, pois são operadores de incremento, porem, em x=(*mat)++, o operador de incremento esta para a posição do conteudo na posição 0, logo, x=posição1.
