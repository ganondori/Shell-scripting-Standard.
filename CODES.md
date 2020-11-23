PowerShell script

#Variables del codigo.
[String]$Saludo = "Hola "
[String]$Vacio = ""
Write-Host "Escriba su nombre"
[String]$Nombre = Read-host
$Bienvenida = "Bienvenido " + $Nombre

#Main
if ($Nombre -eq ""){
Write-Host "Error code 100"
}

else{
Write-Host $Bienvenida
}

////////////////////////////////////////////////////////

Validator



\#include <stdio.h>



int main(void)

{

  int n;

  printf("Write a number\n");

  scanf("%d",&n);

  if(n <= 0)

  {

​    printf("Invalid imput " "< %d >",n);

  }

  else

  {

​    printf("Good one " "< %d >",n);

  }

}

////////////////////////////////////////////////////////

Name in C

\#include <stdio.h>



int main(void) {

  char Name[30];

  char invalid[7] = "Jose";

  printf("Escriba su nombre\n");

  scanf("%s",Name);



  if(Name == invalid)

  {

​    printf("Error code 100");

  }

  else

  {

​    printf("Welcome " "%s",Name);

  }

  return 0;

}



////////////////////////////////////////////////////////

Counter

\#include <stdio.h>



int main(void)

{

  int i = 0;

  int n;

  printf("Escribe un numero\n");

  scanf("%i",&n);

  printf("\n");

  while (i < n)

  {

​    printf("%i\n",i);

​    i++;

  }

  printf("\n");

  printf("$");



  return 0;

}

////////////////////////////////////////////////////////

Plus

\#include <stdio.h>



int main(void)

{

  int i;

  int value;

  int n;

  int plus = 0;



  printf("how many values would you like to introduce?\n");

  scanf("%i",&value);

  printf("\n");



  for (size_t i = value; i > 0; i--)

  {

​    printf("Write a number\n");

​    scanf("%i",&n);

​    plus = plus + n;

  }

  printf("\n");

  printf("%i", plus);



  return 0;

}

////////////////////////////////////////////////////////

Square



\#include <stdio.h>



int main(void) 

{

  int i;

  int value;

  int n;

  int plus = 0;



  printf("how many values would you like to introduce?\n");

  scanf("%i",&value);

  printf("\n");



  for (size_t i = value; i > 0; i--)

  {

​    printf("Write a number\n");

​    scanf("%i",&n);

​    plus = n * n;

​    printf("%i", plus);

​    printf("\n");

  }





  return 0;

}

////////////////////////////////////////////////////////

