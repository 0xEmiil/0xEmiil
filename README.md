[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=2500&color=4E3DF7&center=true&vCenter=true&multiline=true&random=false&width=435&lines=Software+Engineering+Student;Emiliano+Rios)](https://git.io/typing-svg)
```
#include <stdio.h>
#include <string.h>



namespace BackEndSkills
{
 char Lang[3][10] = 
 { 
 {""}, //como se empieza a contar desde 0, se usa un lugar blanco
 {"C"},
 {"C++"},
 };

 char WIP_Lang[5][10] = 
 { 
 {""}, //como se empieza a contar desde 0, se usa un lugar blanco
 {"C#"},
 {"PYTHON"},
 {"PHP"},
  {"SQL"}
 };
 }
 



int main()
{

 printf("Hey Mi Nombre es Emiliano Gonzalez Rios, y Me gusta la programacion, Actualmente estoy enfocado en el backend\n");
 printf("Aqui hay un demo e informacion sobre mi <3\n");
  
 

    printf("\nLenguajes en BackEnd: \n");
    for (int j = 1; j<(int)(sizeof(BackEndSkills::Lang) / sizeof(BackEndSkills::Lang[0])); j++)
    {
    		printf("%i.- %s\n", j, BackEndSkills::Lang[j]);
    }
       for (int i = 1; i<(int)(sizeof(BackEndSkills::WIP_Lang) / sizeof(BackEndSkills::WIP_Lang[0])); i++)
    {
    		printf("\n Lenguajes en processo = %i.- %s\n", i, BackEndSkills::WIP_Lang[i]);
    }
  
  printf("\nSimplemente soy un estudiante apasionado por la tecnologia\ny el mundo que envuelve en ella, este portafolio sirve para que me conocas un poquito y sepas\nun poco de lo que te puedo ayudar\n");
    
}
```
