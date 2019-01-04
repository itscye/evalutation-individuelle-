# Évaluation individuelle

## Programmation - Coaching

```
Nom : Eid
Prénom : Cynthia
URL de votre compte Github : https://github.com/itscye
```

## Déroulé et fonctionnement. 

L'évaluation est à faire sur [Typora](https://typora.io/). Les réponses sont à écrire dans les blocks de code. 
Pour la partie Ruby, testez votre code sur [repl.it](https://repl.it/) et copiez le dans les blocks de code prévu à cet effet. 
Une fois fini, pushez votre feuille sur Github, dans un nouveau repository que vous appelerez "evaluation-inseec".
L'évaluation est individuelle et durera 1h30. Elle intègre des notions d'HTML, CSS, Ruby et computer science. 

![alt](https://media.giphy.com/media/26xBBfd0ii1khakpy/giphy.gif)

## Quelques mises en garde.

Je connais très bien ce merveilleux site qu'est Wikipédia. Je vous saurais gré de ne pas me remplir certaines questions avec les définitions de Wikipédia. Accessoirement, je sais aussi faire une recherche Google. Si j'ai un doute, je n'hésiterais pas rechercher "Qu'est-ce qu'une API" et comparer les définitions en tête de recherche avec les votre. Si je trouve une similarité trop grande et que je doute de votre bonne foi, je n'hésiterais pas à mettre 0 à la question. 
Pareil pour la copie sur les voisins. Si c'est trop gros et que j'ai un doute trop prononcé... 🔫

![alt](https://media.giphy.com/media/BtedgmzGNCiuk/giphy.gif)



------

### 1. Avec vos mots, expliquez l'interaction client-serveur

```t
une serie d'information que le client echange pour aboutir a un but precis 
```



 ### 2. HTML est un langage côté... 	

```
client 
```



### 3. Donnez-moi la structure de base d'une feuille HTML

```html
<!DOCTYPE html>
<!-- Completez après cette ligne -->
<html>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```



### 4. Changez la couleur du texte "J'adore la programmation" en vert en utilisant du CSS.

```html
<div>
   <p>J'adore la programmation</p>
</div>

```

```css
/* Ecrire le code CSS sous cette ligne */
<p> style="color:green;"> Jadore la programmation </p> 
 
```



### 5. Qu'est-ce que Bootstrap ?

```
c'est un site sur lequel on trouve differents style sheets a nos plateformes. on y retrouve beaucoup d'outils et de packs pour gerer nos contenus. 
```



### 6. Reprenez votre code de la question 3 et ajoutez Bootstrap à votre feuille HTML, au bon endroit.

```html
<!DOCTYPE html>
<!-- Completez après cette ligne -->
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <!-- FONTS -->  <link href="https://fonts.googleapis.com/css?family=Ranga" rel="stylesheet">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
    <link rel="stylesheet" href="style.css">
</body>
</html>
```



### 7. Mettez ces trois divs sur le même plan horizontal avec trois colonnes de même taille.

```html
</div><div class="container">
  <div class="row">
    <div class="col">
      Google
    </div>
    <div class="col order-12">
      Microsoft
    </div>
    <div class="col order-1">
      Apple
    </div>
  </div>
</div>
```



### 8. Avec le même code, changez le texte par le logo de la marque en question

```html
<div class="row">
  <div class="column">
    <img src="img_Google.jpg" alt="Google" style="width:100%">
  </div>
  <div class="column">
    <img src="img_Microsoft.jpg" alt="Microsoft" style="width:100%">
  </div>
  <div class="column">
    <img src="img_Apple.jpg" alt="Apple" style="width:100%">
  </div>
</div>
```

 

### 9. Toujours sur le même bout de code, rendez les logos cliquables. Quand on clique sur le logo, on doit arriver sur le site officiel de la marque.

```html
<div class="row">
  <div class="column">
      <a href="default.asp">
    <img src="img_Google.jpg" alt="Google" style="width:100%">
  </div>
  <div class="column">
      <a href="default.asp">
    <img src="img_Microsoft.jpg" alt="Microsoft" style="width:100%">
  </div>
  <div class="column">
      <a href="default.asp">
    <img src="img_Apple.jpg" alt="Apple" style="width:100%">
  </div>
</div>
```

![Mon gars sûr !](https://media.giphy.com/media/l0K4mbH4lKBhAPFU4/giphy.gif)

### 10. Parlons Ruby. Ruby est un langage côté...

```
serveur 
```



### 11. Listez-moi tous les types de données que vous connaissez en donnant le nom et la syntaxe.

```
string = chaine de caractère 
boolean : true, false
Integer : chiffre entier positif ou négatif 
float : décimaux 
hash = {« … »: « … »,} (clés et valeurs )

```



### 12. Assignez à des variables votre prénom, nom et le lien de votre compte Github puis affichez chacune des variables. En 6 lignes.

```ruby
my_name = "cynthia"
my_famname = "eid" 
my_link = "https://github.com/itscye" 
puts my_name
puts my_famname
puts my_link
```



### 13. Assignez 674 et 311 à des variables `a` et `b` et stockez le résultat `a` modulo `b` dans une variable `c` et affichez la. 

```ruby
a = "674"
b = "371"
c = a%b 
puts c 

# Le résultat attendu est 52. 
```



### 14. Qu'est-ce qu'une gem ? 

```texte
est un fournisseur un format standard pour la distribution de programmes et de bibliothèques Ruby.
```



### 15. Qu'est-ce qu'une API et qu'est-ce qui nous permet de nous y connecter ?

```
API= APPLICATION PROGRAM INTERFCE. 
une API c'est des outils pour construir un software elle spécifie comment les composants logiciels doivent interagir
```



### 16. On va créer un script pour dire bonjour ou bonsoir, en fonction de l'heure de la journée. Votre script doit demander à l'utilisateur de rentrer son prénom. Si `hour` est inférieur à 12, lui dire `Bonjour Anthony` sinon `Bonsoir Anthony` (évidemment, le prénom doit être celui renseigné par l'utilisateur).

```Ruby
# <- Demander le prénom de l'utilisateur
puts = "what's your name"
puts = " "
prints = "Anthony"
hour = 15
x = 12
if x > 12 
   puts "Bonsoir Anthony"
elsif x <= 12 
   puts "Bonjour Anthony"
end
# Si hour est inférieur à 12
	# j'écris mon code permettant de dire Bonjour prénom

# sinon
	# j'écris mon code permettant de dire Bonsoir prénom

```



### 17. Itérer sur l'array contenant des noms de twitos un peu famous et follow chacun d'eux grâce à une méthode trouvée dans la [doc de la gem twitter](https://github.com/sferik/twitter). Pas besoin de lancer le code et de faire la partie authentification. Juste le bloc d'itération suffira. 

```ruby
handles = ["@richardbranson", "@jeffweiner", "@LinkedInQueen", "@ericschmidt", "@elonmusk", "@petecashmore", "@SteveForbesCEO", "@mtbarra"]

client.follow("@richardbranson", "@jeffweiner", "@LinkedInQueen", "@ericschmidt", "@elonmusk", "@petecashmore", "@SteveForbesCEO", "@mtbarra")
```



### 18. Félicitations, vous êtes arrivé·e à la fin, pushez cette feuille sur votre Github dans un repo appelé `evaluation-inseec`. N'oubliez pas de remplir le premier block avec votre identité tout en haut ! 

![alt](https://media.giphy.com/media/l0MYJnJQ4EiYLxvQ4/giphy.gif)

