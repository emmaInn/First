## Bienvenue sur notre page Github 

Vous pouvez retrouver tous les projets et code réalisé par notre département sur [Java by CM & VD on Github]().

Notre page Github sera dédié à la réalisation de différents exercices en Java. 

## L'apprentissage des boucles for 

Les exercices seront principalement basés sur l'apprentissage des boucles for avec différents exercices. Développez de nouvelles compétences en apprenant à les réaliser ! 

### Exercices 

Ecrivez un programme qui affiche un triangle d’étoiles en utilisant des boucles for imbriquées 

### Exercice 1

```markdown

*
**
***
****
*****
******
*******
********
*********
**********

```

### Exercice 2 

```markdown

**********
*********
********
*******
******
*****
****
***
**
*

```

### Exercice 3

```markdown

         *
        **
       ***
      ****
     *****
    ******
   *******
  ********
 *********
**********

```

### Exercice 4 

```markdown

**********
 *********
  ********
   *******
    ******
     *****
      ****
       ***
        **
         *
         
```

## Solutions

### Exercice 1

```markdown

public class Ex1 {
public static void main ( String [] args) {
final int MAX = 1 0;
for ( int row=1; row<=MAX; row++)
{
for ( int star =1; star<=row ; star++)
{
System.out.print(”∗”);
}
System.out.println( ) ;
}
}
}


```

### Exercice 2

```markdown

public class Ex2 {
public static void main (String [] args) {
final int MAX = 1 0;
for ( int row=1; row<=MAX; row++)
{
for ( int star=1; star<=MAX-row+1; star++)
{
System.out.print(”∗”);
}
System.out.println( ) ;
}
}
}

```

### Exercice 3

```markdown

public class Ex3 {
public static void main (String [] args) {
final int MAX = 10;
for ( int row=1; row<=MAX; row++)
{
for ( int space =1; space<=MAX−row ; space++)
{
System.out.print(” ”) ;
}
for ( int star=1; star<=row ; star++)
{
System.out.print(”∗”) ;
}
System.out.println( ) ;
}
}
}

```

### Exercice 4

```markdown

public class Ex4 {
public static void main (String [] args) {
final int MAX = 1 0;
for (int row=1; row<=MAX; row++)
{
for (int space=1; space<=row−1; space++)
{
System.out.print(” ”) ;
}
for ( int star=1; star<=MAX−row+1; star++)
{
System.out.print(”∗”) ;
}
System.out.println( ) ;
}
}
}

```

# Mettre un fichier zip avec les static en plus pour avoir tout 

### Support ou Contact

Vous avez des problèmes à créer une page Github? Vous ne comprenez pas la réalisation d'un exercice ? Allez voir notre [documentation](https://help.github.com/categories/github-pages-basics/) ou notre [contact support](https://github.com/contact) et nous vous aiderons à vous en sortir.
