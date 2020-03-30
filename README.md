# Cours de Ruby
## Installation
- Télécharger et installer Ruby: https://rubyinstaller.org/downloads/
- Installer rails
````console
$ gem install rails
````

## IDE
Visual Studio Code, extensions :
- erb
- rails go to spec
- Ruby

## Familiarisation
- Langage simple à appréhender
- Utiliser l'application : Interactive Ruby

### Bases
````rb
puts "message" # affiche un message
# fonction qui renvoie "nil" -> équivalent à null
a = 3 ** 2 # 3 au carré
b = Math.sqrt(a)
````

### Fonctions
````rb
#déclaration d'une fonction
def h
puts "Hello"
end # fin de la fonction

h() # appel d'une fonction

# déclaration d'une fonction avec paramètre
def h(name) 
puts "Hello #{name}" # utilisation du paramètre d'entrée dans la chaine
end

# déclaration d'une fonction avec paramètre et valeur par défaut
def h(name = "World!") 
puts "Hello #{name}" # utilisation du paramètre d'entrée dans la chaine
end
````

### Tableaux
````rb
names = ["Alex","Flo","Max"]

# Récupère le 1er élément du tableau
names.first()

# Dernier élément
names.last()

# transformation en string avec séparateur
names.join(" . ")

# each (itérateur)
names.each do |name|
h(name)
end
# équivalents
names.each { |name| h(name) }


````

