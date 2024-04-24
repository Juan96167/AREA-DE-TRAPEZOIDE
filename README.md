#include <stdio.h>

int main()
{
int opcion;
float baseS;
float alturaS;
float baseI;
float alturaI;
int resultado;
    printf("Bienvenid@ a la calculadora de áreas 😊");
    printf("¿A que figura desea calcularle el área?");
    printf("1. Trapezoide"); 
    printf("2. Cilindro");
    scanf("%d",&opcion);
    
    if(opcion==1)
    {
        printf("Por favor digite el valor de la base de su triangulo superior: ");
            
            scanf("%f",&baseS);
        printf("Por favor digite el valor de la altura de su triangulo superior: ");
            scanf("%f",&alturaS);
        printf("Por favor digite el valor de la base de su triangulo inferior: ");
            scanf("%f",&baseI);
        printf("Por favor digite el valor de la altura de su triangulo inferior: ");
            scanf("%f",&alturaI);
        resultado = (baseS*alturaS/2)+(baseI*alturaI/2);
        printf("El area de su trapezoide es de: %d\ncm2",resultado);
        
        
    }
    
    else if(opcion==2)
    {
        printf("Por favor digite el valor de ")
    }
    
    
}
