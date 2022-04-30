```
/*
* Dev: Emiliano Gonzalez Rios - Portafolio
*
* Como las mismas tecnologias, este codigo 
* se actualizara y mejorara en base a mis conocimientos
* Recordatorio * Exportar a VS
*
*/
#include <stdio.h>
#include <string.h>



namespace BackEndSkills
{
 int iNSkills = 5;
 char Lang[10][10] = 
 { 
 {""}, //como se empieza a contar desde 0, se usa un lugar blanco
 {"C"},
 {"C++"},
 {"C#"},
 {"PYTHON"}
 };

 }
 



int main()
{

 printf("Hey Mi Nombre es Emiliano Gonzalez Rios, y Me gusta la programacion, Actualmente estoy enfocado en el backend\n");
 printf("Aqui hay un demo e informacion sobre mi <3\n");
  
 

    printf("\nLenguajes en BackEnd: \n");
    for (int j = 1; j<BackEndSkills::iNSkills; j++)
    {
    		printf("%i.- %s\n", j, BackEndSkills::Lang[j]);
    }
    
  
  printf("\nSimplemente soy un estudiante apasionado por la tecnologia\ny el mundo que envuelve en ella, este portafolio sirve para que me conocas un poquito y sepas\nun poco de lo que te puedo ayudar\n");
    
}
```
