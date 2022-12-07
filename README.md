# Loop
Loop bot discord FRENCH

Loop is a discord bot that can be used by no one for the moment.
This is a fully French bot so if you want an English version, you won't find anything, unless another user had made the translation of the dialogues.

Vous pouvez signaler à tout moment avec ce github quelque problème que vous rencontrez avec le bot.
Si vous rencontrez un problème avec le bot en lui-même ou que vous souhaitez suggérer un ajout ou une modification, je vous invite à aller sur le serveur discord pour nous en faire part en direct : [Invitation du serveur discord](https://discord.gg/MTyVQPy4PE)

Pour inviter le bot, il suffit simplement d'avoir un compte discord et de cliquer sur ce lien : [Inviter le bot ici](https://discord.com/api/oauth2/authorize?client_id=926885827714375701&permissions=8&scope=bot)

ATTENTION : le bot ne pourra pas être sur plus de 100 serveurs au moins avant le 28/11/2023 à 16:00

## Informations

Le bot est actuellement hébergé sur un rock64 sous Linux base Debian, précisément, un Armbian.
L'hébergement est équipé d'un processeur ARM32 et ne pourra donc pas fournir des performances spectaculairement fluides.

Le bot a été développé en python 3.7 à l'aide de la librairie `discord.py`.
Pour plus de détails sur cette librairie et comment l'installer, je vous conseille de consulter la documentation oficielle de la librairie : [API discord.py](https://discordpy.readthedocs.io/en/stable/intro.html)

Pour ceux qui le souhaitent, le code sera disponible en Open Source prochainement, pour que vous puissiez programmer vos bots.
Bien entendu, les fonctionnalités easter-egg ou propres au bot ne seront pas disponible en Open Source.

## Politique de confidentialité

Les développeurs du bot s'engagent à ne pas chercher ni divulguer quelque information que ce soit sur les messages anonymes envoyés via le bot.

Les données des messages sont stockés sur une base de données sécurisée stockée sur l'hébergement du bot, sous forme de chiffres.

À moins d'y accéder via le bot, il est impossible de récupérer les données des utilisateurs.

Le bot ne possède et ne possèdera aucune fonctionnalité permettant l'accès à ces données, que ce soit par les utilisateurs ou les développeurs.

Si il s'avérait qu'un développeur du bot ait divulgué une information ou ait eu accès à une information de la base de données à propos des messages anonymes, il serait la cause d'une rupture de contrat et pourra être poursuivi pénalement.

Il n'y a actuellement qu'un seul développeur travaillant sur le bot. Celui-ci s'engage à respecter ces termes et conditions.

### Collecte des données

Les données que le bot collecte sont :

* L'identifiant d'utilisateur, pour permettre l'automodération et la modération. Cette donnée ne sera pas visible par les autres utilisateur et ne sera envoyable à personne. Elle sera également stockée dans une base de données sécurisée à laquelle seul le bot aura accès.
* Le contenu des messages envoyés au bot, seulement lorsqu'ils sont précédés du préfixe du bot. Cette donnée ne sera stockée que temporairement, pour permettre le bon fonctionnement des messages anonymes. __Ce qui signifie que si vous envoyez des messages au bot en privé et sans préfixe, ceux-ci ne seront jamais collectés par le bot__
* Les identifiants des serveurs sur lesquels il se trouve.
* Les identifiants des propriétaires des serveurs sur lesquels il se trouve.
* Les identifiants des salons sur lesquels les utilisateurs peuvent envoyer des messages anonymes.
* Les identifiants des rôles autorisés à modifier les paramètre du bot, après définition de ceux-ci par un administrateur.

Il génère :

* Des identifients de serveur pour que les utilisateurs puissent facilement faire envoyer des messages au bot
* Des pseudonymes aléatoires pour les utilisateurs

Conformément à la politique de développement de Discord, l'utilisateur peut choisir la suppression de toutes ses données présentes sur la base de données du bot, et ce, via la commande `deldata` précédée du préfixe du bot. Cette action entraînera la suppression de l'entièreté des messages envoyés par l'utilisateur via le bot, mais également toutes les données concernant cet utilisateur dans la base de données des messages. L'utilisateur ne sera cependant plus en mesure d'utiliser le bot jusqu'à ce qu'il effectuel la commande `allowdata`.

## Conditions d'utilisation

En utilisant les services fournis par le bot, l'utilisateur s'engage à respecter les [ToS de Discord](https://discord.com/terms), à ne déclarer, ni accuser, ni impliquer quoi que ce soit d'illégal, que cela concerne des activités illégales ou du matériel dont la détention est illégale, à ne fournir via le bot les informations personnelles de personne, y compris lui-même, et à ne diffamer ni menacer, ni insulter qui que ce soit, à ne mentionner aucun contenu choquant à caractère obscène, sexuel ou hyper-violent dans quelque message que ce soit envoyé par le biais du bot.

Si ces conditions ne sont pas remplies, les développeurs et administrateurs du bot ne seraient pas responsables de quelque manière que ce soit de l'écart de comportement de l'utilisateur.

## Nous contacter

Vous pouvez nous contacter par mail [ici](loopofficielbotdiscord@gmail.com)

Et vous pouvez nous rapporter un problème [ici](https://github.com/KuroeC/KLoop/Issues)

# FAQ

## Mon serveur a été gban, comment faire annuler le gban ?

Si votre serveur a été gban, cela peut être pour les raisons suivantes :

* Votre serveur ne respecte pas les [ToS de Discord](https://discord.com/terms)
* Une majorité des membres de votre serveur vont à l'encontre des [ToS de Discord](https://discord.com/terms) ou de nos [conditions d'utilisation](https://github.com/KuroeC/KLoop#conditions-dutilisation)
* Le propriétaire du serveur a lui-même été gban

Cependant, il peut aussi s'agir d'une erreur (faute de frappe par exemple), si vous pensez que c'est le cas, vous pouvez vous rendre sur [notre serveur discord support](https://discord.gg/MTyVQPy4PE) et ouvrir un ticket.

## J'ai été gban en tant qu'utilisateur, comment faire annuler le gban ?

Si vous avez été gban, c'est sans doute pour les raisons suivantes :

* Insultes graves via message anonyme
* Menaces via message anonyme
* Diffamation via message anonyme
* Contenu illégal mentionné dans un message anonyme
* Contenu obscène mentionné dans un message anonyme
* Contenu hyper-violent mentionné dans un message anonyme
* Divulgation d'informations personnelles de quelqu'un

Dans le cas où vous pensez qu'il s'agirait d'une erreur, vous pouvez nous le signaler [ici](https://forms.gle/N4rWAQKiQz6jx35g8).

## Qu'est-ce que le Loo'premium ?

Le Loo'premium est une fonctionnalité premium. Pour l'instant, vous ne pouvez l'obtenir que via giveaway sur le [serveur discord officiel du bot](https://discord.gg/MTyVQPy4PE).

Dans le futur, il sera également possible de l'obtenir en payant un café aux développeurs.

## Quels sont les avantages du Loo'premium ?

Les avantages actuels sont :

* La possibilité de renommer un serveur si le propriétaire est premium

Il est prévu d'y avoir plus de fonctionnalités possibles avec le premium.

## Un de mes messages a été signalé, existe-t-il un risque pour mon identité ?

Les modérateurs et utilisateurs utiliseront votre pseudonyme pour vous signaler, et les développeurs l'utiliseront pour vous bannir.

Personne n'aura l'occasion de connaître votre identité.
