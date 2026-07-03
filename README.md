[Switch to English Version 🇬🇧](en.html)

# [SOCMINT] Profilage & Ingénierie Sociale : Comment j'ai retrouvé un compte Instagram "anonyme" grâce à la nostalgie sur LinkedIn

## Le défi
L'autre jour, j'ai lancé un défi à quelqu'un qui était persuadé d'avoir un compte Instagram totalement introuvable. Sa logique ? Pas de nom de famille sur son profil, pas de photo de lui, et un pseudo complètement random. 

Pourtant, ça m'a pris **beaucoup moins de 30 minutes** pour trouver son compte. Pour ça, pas besoin d'outils de hack compliqués. J'ai juste combiné du **SOCMINT** (le renseignement sur les réseaux sociaux) et un peu de psychologie alias ingénierie sociale. 

---

## Étape 1 : Bloqué sur la recherche directe
Au début, j'ai tenté le coup classique : chercher directement son prénom et son nom sur Insta, ou des variantes évidentes (genre `Prénom.Nom`). 

Évidemment, ça n'a rien donné. La séparation entre sa vie publique et sa vie privée était bien faite. Quand je vois que la technique pure bloque, c'est là que je prend une autre approche et que je m'intéresser à la psychologie de la cible.

---

## Étape 2 : Le réflexe LinkedIn et la carte de la nostalgie
Je suis donc allée faire un tour sur LinkedIn. C’est l’endroit parfait pour l'OSINT parce que tout le monde y déballe son parcours professionnel sans trop se méfier. En plus, le calcul est vite fait : avec plus de 30 millions d'utilisateurs en France, soit plus de la moitié de la population active, il y avait de très fortes chances que ma cible y soit.

En analysant son profil, j'ai volontairement zappé ses expériences récentes pour regarder ses anciennes écoles. En cybersécurité, on répète tout le temps que l’humain est la principale faille. Et pour le coup, j'ai misé sur un levier psychologique super puissant : la nostalgie. En effet, quand on a une bonne expérience avec son passé, on finit souvent par suivre des personnes ou des endroits avec lesquels on a eu un lien, en l'occurrence son ancienne école. 

Bingo ! En scrollant tout en bas de sa page, je suis tombée sur l'élément clé qu'il me fallait : le nom de son école primaire.

---

## Étape 3 : La technique de l'entonnoir
Avec cette info, je suis retournée sur Instagram pour filtrer les données :

1. **Trouver l'école :** J'ai cherché le compte officiel de son ancienne école primaire (qui avait une page active).
2. **Fouiller les abonnés :** En vrai, quel adulte suit encore son ancienne école primaire ? Très peu de monde, à part les nostalgiques. J'ai donc extrait la liste des abonnés du compte de l'école.
3. **Le recoupement :** Au milieu des profils, je repère un compte suspect : pas de photo, pas de nom. Par contre, le pseudo commençait exactement par le **début de son prénom**. 

En recoupant la ville, l'école et ce morceau de prénom, il n'y avait plus de doute. Le compte était identifié.

---

## 🧠 Le lien avec l'Ingénierie Sociale (Social Engineering)
On s'imagine souvent que l'ingénierie sociale consiste à manipuler quelqu'un au téléphone ou par mail. En réalité, le plus gros du travail se fait pendant cette phase passive de recherche.  

Trouver un compte Instagram privé, pour un attaquant, c'est une mine d'or :
* **Spear-Phishing ciblé :** En sachant dans quelle école la personne a étudié, un hacker peut créer un faux compte d'un ancien élève de l'époque pour engager la conversation, gagner sa confiance et lui envoyer un lien piégé.
* **Indices pour les mots de passe :** Même en compte privé, une bio ou des stories à la une peuvent laisser échapper des passions, des noms d'animaux ou des dates clés. Ce sont exactement les infos que les gens réutilisent pour leurs mots de passe ou leurs questions de sécurité.

---

## Conclusion
La leçon de cette petite enquête, c'est que la technique ne fait pas tout : la sécurité dépend énormément du facteur humain. Vous pouvez masquer votre nom et votre visage, votre sécurité s'effondrera si vous laissez traîner des indices sur vos centres d'intérêt ou votre passé.

On peut essayer de se cacher derrière tous les pseudos et les filtres techniques du monde, au final, ce sont toujours nos souvenirs qui nous trahissent. En OSINT, on comprend vite que la nostalgie de quelqu'un n'est pas un jardin secret... c'est juste sa plus grande faille de sécurité.
