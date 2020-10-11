## Bienvenue sur notre page Github 

You can use the [editor on GitHub](https://github.com/programming-liftoff/hello-world/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Vous pouvez retrouver tous les projets et code réalisé par notre département sur [CDMV on Github]().

Le thème de notre page Github n'est autre que [Jekyll](https://jekyllrb.com/). Un hyperlien permet d'en savoir plus sur ce qu'il est possible de faire avec Jekyll. 

Notre page Github sera dédié à la réalisation de différents exercices en Java. 

## L'apprentissage des boucles for 

Les exercices seront principalement basés sur l'apprentissage des boucles for avec différents exercices. Développez de nouvelles compétences en apprenant à les réaliser ! 

### Exercices 

Noter ici la formulation du prof sur les exercices

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

Exercices 2 

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

Exercices 3

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

Exercices 4 

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

# Exercice 1

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

# Exercice 2

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

# Exercice 3

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

# Exercice 4

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

Mettre un fichier zip avec les static en plus pour avoir tout 

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/programming-liftoff/hello-world/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support ou Contact

Vous avez des problèmes à créer une page Github? Vous ne comprenez pas la réalisation d'un exercice ? Allez voir notre [documentation](https://help.github.com/categories/github-pages-basics/) ou notre [contact support](https://github.com/contact) et nous vous aiderons à vous en sortir.
