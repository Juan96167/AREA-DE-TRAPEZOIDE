#include <stdio.h>
#include <math.h>

int main()
{
int opcion;
float baseS;
float alturaS;
float baseI;
float alturaI;
int resultadoT;
float radio;
float alturaC;
int resultadoC;
    printf("Bienvenid@ a la calculadora de áreas 😊");
    printf("¿A que figura desea calcularle el área?");
    printf("1. Trapezoide"); 
    printf("2. Cilindro");
    scanf("%d",&opcion);
    
    if(opcion==1)
    {
        printf("Por favor divida su Trapezoide en dos triangulos y digite los siguientes valores: ");
        printf("Por favor digite el valor de la base de su triangulo superior: ");
            scanf("%f",&baseS);
        printf("Por favor digite el valor de la altura de su triangulo superior: ");
            scanf("%f",&alturaS);
        printf("Por favor digite el valor de la base de su triangulo inferior: ");
            scanf("%f",&baseI);
        printf("Por favor digite el valor de la altura de su triangulo inferior: ");
            scanf("%f",&alturaI);
        resultadoT = (baseS*alturaS/2)+(baseI*alturaI/2);
        printf("El area de su trapezoide es de: %d\ncm2",resultadoT);
        
        
    }
    else if(opcion==2)
    {
        printf("Por favor digite el valor del radio de los circulos de su cilindro: ");
        printf("Para saber el valor del radio debe conocer la medida del perimetro y dividirlo en dos");
        scanf("%f",&radio);
        printf("Por favor digite el valor de la altura de su cilindro: ");
        scanf("%f",&alturaC);
        resultadoC = (2*M_PI*radio)*(radio+alturaC);
        printf("El area de su cilindro es de: %d\ncm2",resultadoC);
        
        
        
        
    }
    
}
