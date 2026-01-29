#include <stdio.h>
int main()
{
    float tempc, tempF, tempk;
    printf("enter temperature in degree calcius:");
    scanf("%f", &tempc);
    tempF = (tempc * (9.0 / 5.0)) + 32;
    tempk = (tempc + 273.15);
    printf("\ntemp(in farenheit):%.2f\ntemp(kelvin):%f.2\n\n", tempF, tempk);
    return 0;
}