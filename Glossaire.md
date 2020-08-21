
# Gouvernance d'Internet

La gouvernance de l’Internet est l’élaboration et l’application par les Etats, le secteur privé et la société civile, chacun selon son rôle, de principes, normes, règles, procédures de prise de décision et programmes communs propres à modeler l’évolution et l’utilisation de l’Internet. (Sommet Mondial pour la Société de l'Information, Tunis 2005)



# Nom de domaine

Un nom de domaine est une chaîne de caractères qui sert d'identifiant à une adresse IP. *wikipedia.fr* ou *duckduckgo.com* sont des noms de domaine. Un nom de domaine sert donc à faciliter à l'humain l'accès à un site Internet en lui donnant une seconde adresse facilement lisible et mémorisable. L'enregistrement d'un nom de domaine et payant et se fait auprès d'un **registraire** (par exemple l'AFNIC pour le .fr), société qui enregistre le lien entre l'adresse IP de votre site et le nom de domaine que vous avez choisi. 

# Principe de bout-à-bout

Le principe de bout-à-bout (ou end-to-end principle) est un principe fondateur de l'Internet. Il professe que les traitements informatiques complexes doivent s'effectuer aux extrémités du réseau, et non en leur coeur, cela afin de garantir la simplicité du réseau (généralement basé sur les protocoles TCP/IP).

En général, cela signifie que le réseau doit se limiter au simple transport des flux de données, indépendamment de ce qu'ils contiennent et sans leur appliquer de traitement particulier. Par exemple pour le chiffrement de bout-en-bout, les opérations complexes (chiffrement au départ et déchiffrement à l'arrivée) se font respectivement en amont et en aval du transport du paquet chiffré par le réseau. 

# Paquet

Le paquet est l'unité fondamentale de transmission des données sur un réseau informatique. Un paquet se divise en deux parties :  

- le contenu du paquet, encapsulé par un protocole

- l'en-tête du paquet, sorte d'étiquette donnant l'expéditeur, le récepteur, et décrivant le contenu du paquet

Ainsi, lorsqu'Alice envoie un fichier F à Bob via un réseau informatique, le fichier F est préalablement découpé en paquets, qui sont transmis par le réseau, puis Bob réassemble les paquets (comme les pièces d'un puzzle qu'on aurait étiquetées) pour retrouver le fichier F initial. 

