# contador1
The following exercise combines the use of IF with the While loop to set the value of a counter when a variable reaches a specified value after being incremented.
#include <stdio.h>
#include <stdlib.h>

int main(int argc, char *argv[])
{   
    int contador = 0;  /*Inicializa la condicion*/

    while(contador < 5) /*condicion de prueba*/
    {
      contador++;      /*cuerpo de bucle*/
      printf(" Contador: %d \n", contador);
    }
   printf(" Terminado. Contador: %d \n", contador);
  system("PAUSE");	
  return 0;
}
