---
layout: project
type: project
image: images/index.jpg
title: Early Programming Experience
permalink: projects/problemsolvinginc
# All dates must be YYYY-MM-DD format!
date: 2011-12-14
labels:
  - EE150
  - C Code
  - Calculus
summary: Early Programming Projects from EE150
---

  First real experience with programming as a problem solving medium was in EE150.
  The focus was to make basic programs to solve practical math based problems, extending
  into calculus II level math and using loops to approximate their solutions.  The final
  project was to use C code and run Gauss-Jordan elimination to solve x equations with 
  x unknowns.
  
The Main Algorithm that solves Gauss-Jordan, rest of the program was reading in the arrays
and printing the final output to the screen.
```C
for(k=0; k<m; k++)
    {
         pivot = a[k][k];
         for(t=0; t<m+1; t++)
         {
             a[k][t] = a[k][t]/pivot;
         }
         t=0;        
         for(j=0; j<m; j++)
         {
             hold = a[j][k];
             for(t=0; t<m+1; t++)
             {
                  if(j != k)
                  {
                      a[j][t] = a[j][t] - a[k][t]*hold;
                  }
             }
         }       
    }
    ```


