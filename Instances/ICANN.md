<!-- MarkdownTOC -->

- Rôle
- Acteurs
- Enjeux et dossiers centraux
	- Enjeux généraux
	- La bataille du .org
	- Le système WHOIS
	- L'expansion des generic Top-Level Domain \(gTLD\)
- Gouvernance
	- Remarques générales
	- Statut juridique
	- Organisation générale
	- Processus de gouvernance et comitologie
	- Organisations de soutien et comités consultatifs importants
		- Le GAC \(Governmental Advisory Commitee\)
		- Le gNSO \(generic Names Supporting Organization\)
	- Dissensions internes
		- Rôle des États-Unis
		- Une instance seulement technique ou aussi politique ?
- Positions françaises et personnes mobilisées

<!-- /MarkdownTOC -->


# Rôle

L'**Internet Corporation for Assigned Names and Numbers** (ICANN) est une instance centrale de la gouvernance d'Internet. Elle a pour rôle d'**élaborer, d'appliquer et d'assurer la résilience des règles relatives aux [noms de domaines](../Glossaire.md#nom-de-domaine) et adresses IP**, en relation directe avec les registraires (sociétés chargées de la gestion d'un domaine particulier comme l'AFNIC pour le .fr) qui sont liés par contrat.

# Acteurs

Tous les types d'acteurs sont présents au sein de l'ICANN, depuis le simple citoyen jusqu'aux États et organisations internationales en passant par les entreprises privées et les ONG. Il est difficile de donner une importance relative à chacun de ces acteurs puisque le véritable décisionnaire est le [Conseil d'Administration](#organisation-generale). La transparence des processus de l'ICANN permet en tout cas à chaque type d'acteur d'avoir voix au chapitre, et la technicité de certains dossiers peut donner une véritable influence à des acteurs autrement peu influent. 
# Enjeux et dossiers centraux

## Enjeux généraux 

Si l'ICANN ne se limite qu'à un rôle technique dans le seul champ de l'adressage IP et DNS, son importance vient surtout de la portée mondiale de son action. En effet, les experts techniques de l'ICANN sont au coeur de l'infrastructure d'Internet et possèdent théoriquement la capacité de mettre hors-service l'immense majorité de la face visible d'Internet en cas de coupure du système DNS.


De plus, la gestion des noms de domaine a un impact plus grand qu'on ne le pense sur la société en général. 

Économiquement tout d'abord, car certains domaines sont plus attractifs que d'autres (un site en .com sera plus susceptible d'être visité qu'un site en .info par exemple) et que la gestion de ceux-ci peut devenir très profitable (voir par exemple [la bataille du .org](#la-bataille-du-org)). 

Juridiquement ensuite, avec des enjeux de confidentialité (voir par exemple le [système WhoIs](#le-systeme-whois)), de respect des droits nationaux et de respect de la propriété intellectuelle : comment réagir face à un nom de domaine pointant vers un site de films piratés ? Vers un site terroriste ? Vers un site pornographique ?

Sécuritaire enfin, puisque les infrastructures DNS ne sont pas exemptes de toute faille, et que des attaques comme le DNS hijacking (détournement de l'adressage) peuvent être utilisé aussi bien par des pirates isolés pour hameçonner les internautes, des FAI (Fournisseurs d'Accès à Internet) pour bloquer des sites illégaux que des États pour censurer des contenus. 

## La bataille du .org

Le nom de domaine générique de premier niveau **.org**, traditionnellement utilisé par des organisations à but non lucratif (par exemple Wikipédia), est géré depuis 2003 par un registraire lui aussi à but non lucratif, le PIR (Public Interest Registry) placé sous l'autorité de l'ISOC (Internet Society). En novembre 2019, PIR a annoncé vouloir être racheté par Ethos Capital, société de capital-risque américaine fondée par l'ex-directeur général de l'ICANN.

Les dangers de ce rachat auraient été une gestion opaque du domaine par un acteur privé dont le but aurait été la recherche de profit, ce qui aurait pu mettre à mal à la fois la situation financières de ces près de 10 millions d'organisations pas toujours très riches mais aussi la crédibilité du domaine .org. De plus, les organisations et sites utilisant ce domaine n'auraient pas pu participer à sa gouvernance.

En Avril 2020, après une bataille de plusieurs mois et un positionnement français résolumment contre ce rachat, l'ICANN a annoncé retirer son consentement au rachat, ce qui s'apparente à une fin de non-recevoir pour le PIR.

## Le système WHOIS 

Le système WHOIS (Who is) est un service de recherche d'informations personnelles (noms, adresse, mail, téléphone...) sur les détenteurs des noms de domaine. Ces données personnelles sont fournies par les détenteurs eux-mêmes puisqu'elles sont nécessairement données aux registraires lors de l'achat du nom de domaine.

Les données du système WHOIS étaient au départ rendues entièrement publiques, ce qui a conduit à des réutilisations parfois discutables. Ainsi, la base était régulièrement parcourue par des cyber-délinquants à la recherche de personnes à hameçonnner. À l'inverse, des services de sécurité, notamment américains, se sont énormément reposés sur cette base pour enquêter sur des sites frauduleux. L'industrie française du luxe, à commencer par LVMH, a pu utiliser WHOIS pour remonter les filières de contrefaçon. WHOIS a aussi été utilisé par des journalistes indépendants comme source d'informations.

La non-conformité de WHOIS au RGPD a créé une crise profonde dans un système déjà vieillissant. Le Conseil d'Administration de l'ICANN a alors fait le choix soudain et radical de masquer la presque totalité des informations personnelles, ce qui a conduit les services de renseignement et policiers, tout particulièrement américains, à protester vigoureusement, de même que les journalistes. Il est prévu que le système soit rénové, un Processus de Développement des Politiques est actuellement à l'oeuvre et rendra ses recommandations fin septembre 2020. 

Les options envisagées sont actuellement de créer un système de demande d'accès aux données personnelles des détenteurs de noms de domaine, et un accès privilégié pour d'autres personnes (comme les services de renseignement, mais pas forcément les journalistes). 

## L'expansion des generic Top-Level Domain (gTLD)

Un domaine de premier niveau correspond à la dernière partie du nom de domaine (pour github.com ce sera .com). 

Les domaines de premier niveau génériques (gTLD) se distinguent des ccTLD (domaines de premier niveau géographiques comme .fr) et rTLD (domaines de premier niveau réservé comme .localhost). 

Le nombre de gTLD est passé d'une vingtaine à plus de 1200 suite à la décision de l'ICANN en 2012 d'ouvrir un cycle de négociations afin d'intégrer de nouveaux domaines. 

Un nouveau cycle d'intégration est prévu pour les prochaines années et les négociations sont en cours.

L'ajout de nouveaux gTLD est un sujet important pour plusieurs raisons. 

- D'abord, économiquement, l'ICANN invoque la libre concurrence pour justifier de l'expansion des gTLD, ce qui permettrait à de nouvelles entreprises de disposer de leur domaine. Le choix de ces entreprises peut donc avoir un impact économique non négligeable.

- Ensuite, sur le plan de la sécurité les détracteurs de l'expansion dénoncent la multiplication des sites doublons et frauduleux qui en résultera. 

- Juridiquement se posera aussi la question des règles d'attribution pour chaque nom de domaine. Si le nom de domaine .bordeaux est ajouté, est-ce qu'importateur chinois de vin français pourra utiliser ce domaine ? 


# Gouvernance

## Remarques générales

L'ICANN est une instance très lente [A PRECISER].

## Statut juridique

L'ICANN est une société à but non lucratif basée en Californie. 

## Organisation générale

L'ICANN possède trois grands organes.

- Le **Conseil d'Administration** (CA) est l'organe exécutif de l'ICANN et est constitué de diverses parties prenantes de la gouvernance d'Internet en général. Il doit approuver tout ou partie des **Processus de Développement des Politiques**, propositions construites par les groupes de travail de l'ICANN. Il lui est souvent reproché son opacité dans la prise de décision, en totale opposition avec le reste des processus de l'instance, très transparents et ouverts à la société civile.

- L'**ICANN.org** est une entreprise de 400 employés chargée d'organiser la bonne tenue des groupes de travail et de communiquer sur leurs résultats. [NOM ET NOMBRE D'EMPLOYES A VERIFIER]

- La **communauté de l'ICANN** forme l'organe législatif de l'ICANN. Il est constitué de deux types de sous-structures, les **Organisations de soutien** et les **Comités consultatifs**. La différence entre les deux est mince : les Comités consultatifs peuvent apostropher directement le CA, qui doit rendre un avis sur la question posée, tandis que les Organisations de soutien ont pour prérogative la gestion du calendrier des PDP (i.e. le processus de création normative). 

## Processus de gouvernance et comitologie

Les politiques de l'ICANN se font au cours de **Processus de Développement des Politiques** (PDP). Le processus est long et complexe, il fonctionne au consensus pour l'ensemble du processus à part pour la décision finale du CA. Il se schématise de la manière suivante :

- Une Organisation de Soutien demande à créer un GT (groupe de travail) en rédigeant de manière transparente une charte sujette à des commentaires publics (i.e. tout acteur peut donner son avis sur le document). La charte doit ensuite être approuvée par le conseil de l'Organisation de Soutien.

- Le GT se forme :
	- Un rapport initial sujet à commentaires publics est rédigée sur une période d'un mois et demi environ
	- S'ensuivent les travaux à proprement parler sur une durée de quelques mois
	- Un rapport final est produit et est sujet lui aussi à commentaires publics.

- L'Organisation de Soutien approuve tout ou partie du rapport final et renvoie au CA.

- Le CA approuve tout ou partie du rapport final.

La rédaction dans le GT est le moment où l'essentiel de la valeur normative du PDP est produit. 

Les commentaires publics peuvent avoir un vrai impact, d'autant plus si le dossier est technique (c'est moins le cas pour les dossiers plus politiques). 

## Organisations de soutien et comités consultatifs importants

### Le GAC (Governmental Advisory Commitee)

Le GAC réunit les États et les Organisations Internationales. Il se réunit trois fois l'an.

[INCOMPLET]

### Le gNSO (generic Names Supporting Organization)

Le gNSO est une organisation de soutien en charge des  qui englobe énormément de problématiques de l'ICANN. Cette organisation est d'une très grande complexité, avec de très nombreuses sous-structures ce qui la rend assez paralysée.

Elle est chargée de dossiers comme [l'expansion des gTLD](#lexpansion-des-generic-top-level-domain-gtld).

## Dissensions internes

### Rôle des États-Unis

Le rôle des États-Unis a toujours été créateur de tensions au sein de l'ICANN, qui, rappelons-le, est basée en Californie et répond du droit californien. 

Ces tensions se sont affaiblies depuis 2014 avec le non renouvellement du contrat mettant l'ICANN sous la tutelle du département du Commerce américain.

### Une instance seulement technique ou aussi politique ?

L'ICANN a toujours officiellement affiché sa volonté de se limiter à la seule gestion technique des noms de domaines, indépendemment de la régulation des contenus publiés sur Internet. Elle s'est toujours montrée réticente à se prononcer sur le caractère néfaste ou illégal de certains sites Web. 

Néanmoins, des voix s'élèvent pour demander à l'ICANN de perdre sa neutralité sur certains contenus sensibles (terroristes, pornographiques...). Le seul précédent concerne actuellement la crise du coronavirus, durant laquelle l'ICANN a pris position sur des sites de fausses nouvelles relatives au COVID-19 en retirant l'attribution des noms de domaine associés. 

Il faut aussi mettre en perspective cette réticence à réguler avec le modèle économique de l'ICANN, qui touche une part de la vente de chaque nom de domaine.

Un groupe de travail rendra fin septembre ses conclusions sur la définition officielle par l'ICANN d'**abus de DNS**, présumément nécessaire pour une action répressive.

# Positions françaises et personnes mobilisées

L'ICANN est suivie par 