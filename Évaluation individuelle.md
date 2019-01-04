# Évaluation individuelle

## Programmation - Coaching

```
Nom : NGUYEN
Prénom : Dieu Linh
URL de votre compte Github : https://github.com/dieulinh164
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
Le modèle client-serveur est un modèle bien connu dans les réseaux informatiques, qui est largement appliqué et constitue un modèle de chaque site Web existant. L'idée de ce modèle est que le client (agissant en tant que client) envoie une demande au serveur (agissant en tant que fournisseur de services), le serveur traitera et renverra les résultats au serveur.

Client dans l'interaction client / serveur, il est également défini spécifiquement pour un ordinateur client qui est un poste de travail utilisé par un seul utilisateur pour exprimer son indépendance. Les ordinateurs clients peuvent utiliser des systèmes d’exploitation normaux tels que Win9x, DOS, OS / 2, etc.

Le serveur est également défini comme un ordinateur multi-utilisateur. Etant donné qu'un serveur doit gérer plusieurs demandes provenant de clients réseaux, il fonctionne mieux si son système d'exploitation est multitâche, avec des fonctions d'exploitation indépendantes et parallèles, telles que les systèmes d'exploitation UNIX et WINDOWS. ...
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
    <head>
        <meta charset="utf-8" />
        <title>Bienvenue à mon pays</title>
    </head>
    
    <body>
        
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
p
{
    color: green;
}

```



### 5. Qu'est-ce que Bootstrap ?

```
Bootstrap est un framework qui permet à la conception du design des sites et applications Web responsive plus facilement et plus rapidement. Bootstrap est composé de modèles HTML, CSS et Javascript qui créent des modèles de base tels que la typographie, les formulaires, les boutons, les tableaux, la navigation, les modaux, les carrousels d'images, etc. Dans le bootstrap, il contient des plugins Javascript supplémentaires. 
```



### 6. Reprenez votre code de la question 3 et ajoutez Bootstrap à votre feuille HTML, au bon endroit.

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset=utf-8>
    <title>Bienvenue à mon pays 
    </title>
    <link rel="stylesheet" href="//netdna.bootstrapcdn.com/bootstrap/3.1.1/css/bootstrap.min.css">
    <link rel="stylesheet" href="//netdna.bootstrapcdn.com/bootstrap/3.1.1/css/bootstrap-theme.min.css">
    <script src="//netdna.bootstrapcdn.com/bootstrap/3.1.1/js/bootstrap.min.js"></script>
  </head>
  <body>
    <p>Bonjour à tous</p>
  </body>
</html>
```



### 7. Mettez ces trois divs sur le même plan horizontal avec trois colonnes de même taille.

```html
<div class="row">
  <div class="col-sm-4">Google</div>
  <div class="col-sm-4">Microsoft</div>
  <div class="col-sm-4">Apple</div>
</div>   
```



### 8. Avec le même code, changez le texte par le logo de la marque en question

```html
<!DOCTYPE html>
<html>
<head>
  <title></title>
   <link rel="stylesheet" href="//netdna.bootstrapcdn.com/bootstrap/3.1.1/css/bootstrap.min.css">
    <link rel="stylesheet" href="//netdna.bootstrapcdn.com/bootstrap/3.1.1/css/bootstrap-theme.min.css">
    <script src="//netdna.bootstrapcdn.com/bootstrap/3.1.1/js/bootstrap.min.js"></script>
</head>
<body>
  <div class="row">
  <div class="col-sm-4">
    <a href="https://www.google.com/webhp?hl=vi&sa=X&ved=0ahUKEwiqlbLojNTfAhVRat4KHRAHAxYQPAgH">
      <img height="100" width="200" src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/aa/Logo_Google_2013_Official.svg/1280px-Logo_Google_2013_Official.svg.png">
    </a>
  </div>
  <div class="col-sm-4">
    <a href="https://www.microsoft.com/vi-vn/">
      <img height="100" width="200" src="https://cdn.vox-cdn.com/thumbor/NeSo4JAqv-fFJCIhb5K5eBqvXG4=/7x0:633x417/1200x800/filters:focal(7x0:633x417)/cdn.vox-cdn.com/assets/1311169/mslogo.jpg">
    </a>
  </div>
  <div class="col-sm-4">
    <a href="https://www.apple.com/">
      <img height="100" width="200" src="https://as-images.apple.com/is/image/AppleInc/aos/published/images/o/g/og/default/og-default?wid=1200&hei=630&fmt=jpeg&qlt=95&op_usm=0.5,0.5&.v=1525370171638">
    </a>
  </div>
</div>


</body>
</html>
```

 

### 9. Toujours sur le même bout de code, rendez les logos cliquables. Quand on clique sur le logo, on doit arriver sur le site officiel de la marque.

```html
<div>
    Google
</div>

<div>
    Microsoft
</div>

<div>
    Apple
</div>
```

![Mon gars sûr !](https://media.giphy.com/media/l0K4mbH4lKBhAPFU4/giphy.gif)

### 10. Parlons Ruby. Ruby est un langage côté...

```
serveur 
```



### 11. Listez-moi tous les types de données que vous connaissez en donnant le nom et la syntaxe.

```
 # Ceci est un 
 
- Boolean: bool = [true, false]
- Symbol:  status = :pending
- Number:  number = 132
- String:  string = "Phuong"
- Array:   bonjour = [1, 2, 3, 4, 5]
- Hash:    hash = {"color" => "Green", "number" => 100, 0 => "Blue"}
- Range:   range = (1..5)
 
```



### 12. Assignez à des variables votre prénom, nom et le lien de votre compte Github puis affichez chacune des variables. En 6 lignes.

```ruby
accountgifthub = []
puts "Quel est votre prénom?"
accountgifthub[1]=gets.chomp.to_s
puts "Quel est votre nom?"
accountgifthub[2]=gets.chomp.to_s
puts "Quel est votre lien?"
accountgifthub[3]=gets.chomp.to_s
puts accountgifthub
```



### 13. Assignez 674 et 311 à des variables `a` et `b` et stockez le résultat `a` modulo `b` dans une variable `c` et affichez la. 

```ruby

# Le résultat attendu est 52. 
```



### 14. Qu'est-ce qu'une gem ? 

```texte
"Gem" signifie RubyGems. C'est un logiciel qui vous permet de télécharger facilement, installer et qui contient une application ou une bibliothèque Ruby.

"Gem" est utilisé pour développer ou modifier des fonctions dans une application ruby. Dans l’ensemble, nous utilisons «gem» pour réutiliser la fonction ou la partager avec d’autres rubylistes. Gem nous aide à travailler plus rapidement et plus efficacement.

Gems populaires comme: devise, cancancan, sidekiq, trombone ....
```



### 15. Qu'est-ce qu'une API et qu'est-ce qui nous permet de nous y connecter ?

```
API signifie Application Programming Interface, l’application qui permet à deux applications de communiquer entre elles. Chaque fois que vous utilisez des applications telles que Facebook, des applications de messagerie instantanée ou que vous consultez la météo sur votre téléphone, vous utilisez l'API.

Lors de l'utilisation de l'application sur un périphérique mobile, l'application se connecte à Internet et envoie des données au serveur. Le serveur récupère ensuite les données, interprète les données, effectue les actions nécessaires et renvoie les données à votre appareil. L'application explique les données et affiche les informations lisibles par vous. Et ça s'appelle API.
```



### 16. On va créer un script pour dire bonjour ou bonsoir, en fonction de l'heure de la journée. Votre script doit demander à l'utilisateur de rentrer son prénom. Si `hour` est inférieur à 12, lui dire `Bonjour Anthony` sinon `Bonsoir Anthony` (évidemment, le prénom doit être celui renseigné par l'utilisateur).

```Ruby
# <- Demander le prénom de l'utilisateur

hour = 15

# Si hour est inférieur à 12
	# j'écris mon code permettant de dire Bonjour prénom

# sinon
	# j'écris mon code permettant de dire Bonsoir prénom

puts "Quelle est votre nom ?"
nom = gets.chomp.to_s
puts "Quelle heure est il ?"
x = gets.chomp.to_i
if x < 12
print "Bonjour, #{nom}" 
else print "Bonsoir,#{nom}"
end

```



### 17. Itérer sur l'array contenant des noms de twitos un peu famous et follow chacun d'eux grâce à une méthode trouvée dans la [doc de la gem twitter](https://github.com/sferik/twitter). Pas besoin de lancer le code et de faire la partie authentification. Juste le bloc d'itération suffira. 

```ruby
handles = ["@richardbranson", "@jeffweiner", "@LinkedInQueen", "@ericschmidt", "@elonmusk", "@petecashmore", "@SteveForbesCEO", "@mtbarra"]


```



### 18. Félicitations, vous êtes arrivé·e à la fin, pushez cette feuille sur votre Github dans un repo appelé `evaluation-inseec`. N'oubliez pas de remplir le premier block avec votre identité tout en haut ! 

![alt](https://media.giphy.com/media/l0MYJnJQ4EiYLxvQ4/giphy.gif)

