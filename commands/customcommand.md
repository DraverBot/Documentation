## Commande customcommand
Permet de gérer les commandes personnalisées du serveur.

## Catégorie
[Utiles](../categories/misc.md)

## Permissions
`Gérer le serveur`

## Cooldown
**5** secondes

## Alias
`cc`

## Exécution
N'est exécutable que dans un serveur.

## Arguments
1. Sous commande

## Sous-commandes
La commande customcommand a **3** sous-commandes :

* [list](#list)
* [delete](#delete)
* [set](#set)

### list
Affiche la liste des sous-commandes du serveur.

![Syntaxe](https://media.discordapp.net/attachments/976356791451529236/977629017073123469/unknown.png)

![Résultat](https://media.discordapp.net/attachments/976356791451529236/977628919484264518/unknown.png)

### delete
Supprime une commande personnalisée.

#### Arguments
* nom de la commande ( [texte](../others/texte.md) )

![syntaxe](https://media.discordapp.net/attachments/976356791451529236/977629500760281088/unknown.png)

![Résultat](https://media.discordapp.net/attachments/976356791451529236/977629500252782652/unknown.png)

### set

Configure une commande.

#### Arguments
1. Nom de la commande (un un mot) ( [texte](../others/texte.md) )
2. Réponse ( [texte](../others/texte.md) )

##### Valeurs
Vous pouvez utiliser ces chaines de caractère pour mettre une valeur dans votre réponse

###### Nom d'utilisateur
`{user.name}`

###### Tag
`{user.tag}`

###### Mention
`{user.mention}`

###### Identifiant
`{user.id}`

###### Supprimer le message de la commande
`{del}`

###### Mettre les arguments
`{args}`

###### Nom du serveur
`{guild.name}`

###### Nombre de membres du serveur
`{guild.count}`

###### Envoyer la réponse en privé
`{mp}`

###### Répondre au message
`{reply}`

![Syntaxe](https://media.discordapp.net/attachments/976356791451529236/977629499892068482/unknown.png)

![Résultat](https://media.discordapp.net/attachments/976356791451529236/977629499518771230/unknown.png)