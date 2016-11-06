== Description de l'atelier ==
Les participant·e·s modifient le code HTML et CSS d'un projet existant. <br>
(Éventuellement le code Javascript selon le projet sélectionné.) <br>
<br>
'''Note :''' Il est conseillé de faire précéder cet atelier par l'atelier '''“Jeu de cubes HTML : initiation aux balises HTML”''', pendant lequel les participant·e·s auront pu se familiarisé·e·s avec les balises HTML, leurs significations et la structure de base d'une page HTML.

== Public, durée, matériel ==
Public débutant, alphabétisé, pas de prérequis technique. <br>
Jusqu'à 4 participant·e·s pour un·e organisateur·ice. <br>
1 à 2 participant·e·s par ordinateur. <br>
Durée : 1h à 1h30. <br>
Matériel : des ordinateurs (pour l'utilisation d'un navigateur web) et une connexion internet.

== Notions abordées ==
Qu'est qu'une balise HTML? <br>
Quelles sont les significations des balises HTML utilisées? <br>
La structure de base d'une page HTML. <br>
Qu'est-ce que le CSS? <br>
La signification de quelques propriétés CSS que les participant·e·s modifieront.

== Déroulement de l'atelier ==
'''Partie 1 : préparation et introduction'''
# Installer à l'avance l'Add-on [https://addons.mozilla.org/en-US/firefox/addon/web-developer/ Web Developer] sur l'ordinateur sur lequel vous faites les démonstrations.
# Se rendre sur un site internet que vous aurez choisi à l'avance selon votre public.
# Avec l'outil Web Developer : désactiver tous les styles CSS de la page et expliquer le rôle du CSS dans la présentation d'une page Web.

'''Partie 2 : jouer avec Mozilla Thimble'''
#'''Introduction'''
## Se rendre sur la page [https://thimble.mozilla.org/fr/ Mozilla Thimble].
## Choisir le projet “Keep Calm and Carry On”.
## Expliquer la présentation en 2 parties : à gauche le code et à droite la visualisation. Les modifications effectuées dans le code à gauche s'affichent en temps réel à droite.
## Expliquer la structure et les balises HTML, ainsi que la façon d'écrire des commentaires.
#'''Modifier le code HTML'''
## Effectuer l'exercice dans la colonne gauche “Éditeur”, sur la page '''“index.html”'''.
## Modifier le titre <code><nowiki>h1</nowiki></code> (lignes 18 à 22).
## Ajouter un paragraphe sous le titre : <code><nowiki><p></nowiki></code>Votre texte personnalisé entre ces balises<code><nowiki></p></nowiki></code>.
## Modifier éventuellement l'image : remplacer <code><nowiki>src="crown.svg"</nowiki></code> par <code><nowiki>src="l'url de votre choix”</nowiki></code> (ligne 15).
#'''Modifier le code CSS'''
## Dans la colonne gauche, se rendre sur la page '''“style.css”'''.
## Modifier quelques propriétés de l'élémént <code><nowiki>body</nowiki></code> :
##* la couleur de fond (ligne 2)
##* la couleur du texte (ligne 3)
##* éventuellement la famille de police (ligne 4)
##* l'alignement du texte (ligne 5)
##* éventuellement les marges internes <code><nowiki>padding</nowiki></code> (ligne 6)
## Modifier quelques propriétés de l'élémént <code><nowiki>wrapper</nowiki></code> : 
##* les marges, l'épaisseur et la couleur du cadre (lignes 9 à 14)
## Modifier quelques propriétés de l'élémént <code><nowiki>h1</nowiki></code> :
##* la taille du texte (ligne 17)
##* l'interlettrage (ligne 18)
##* la casse du titre : <code><nowiki>uppercase</nowiki></code> en <code><nowiki>lowercase</nowiki></code> (ligne 19)
##* la graisse du texte (ligne 20)
##* éventuellement les marges (ligne 21 et 22)

'''Partie 3 : modification du code CSS sur un site internet avec l'outil “Inspecteur d'élément”''' (Optionnel)
# Se rendre sur un site internet que vous aurez choisi à l'avance selon votre public.
# Au clic droit choisir “Inspect Element”.
# Sélectionner un fond de couleur avec la flèche “Pick an element from the page”.
# Dans la colonne de droite '''“Rules”''' repérer la propriété CSS <code><nowiki>background</nowiki></code> et modifier sa valeur.
# Annoncer aux participant·e·s qu'illes ont modifié la couleur du site! Puis expliquer pourquoi ce changement est seulement effectué en local sur leur ordinateur.

== Liens ==
[http://webmaker.org Mozilla Webmaker] <br/>
[https://thimble.mozilla.org/fr/ Mozilla Thimble] <br>
MDN – Mozilla Developer Network : [https://developer.mozilla.org/fr/docs/Web/HTML Tutoriels, références et documentation HTML]
