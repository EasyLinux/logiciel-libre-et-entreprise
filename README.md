% Logiciel libre et entreprise
% Ophir LOJKINE
% Février 2017

# Introduction
## Introduction

### Logiciel libre
On appelle *logiciel libre* une grande famille de logiciels souvent gratuits,
mal connus, et qui ont parfois la réputation d'être à l'opposé du monde l'entreprise.

### Qu'en est-il vraiment ?

Nous allons essayer ici de comprendre ce qu'ils sont, quel est leur usage réel en
entreprise aujourd'hui, et quels sont les coûts, les risques, et les opportunités
apportés par leur adoption.

# Définitions
## Logiciel libre

Un logiciel libre doit donc être open-source, mais cela ne suffit pas.

Il [est défini](https://www.gnu.org/philosophy/free-sw.html)
par quatre libertés fondamentales:

 0. liberté d'**utiliser** le logiciel, pour n'importe quel usage,
 0. liberté d'**étudier** le logiciel (code source disponible),
 0. liberté de **redistribuer** (gratuitement ou non),
 0. liberté de **modifier** et de publier ses modifications.

## Licence libre

On appelle *licence libre* toute licence logicielle qui garantit les libertés sus-mentionnées.

Deux grands types de licence libre existent :

 - *copyleft* : obligation de rendre libre toute modification, toute nouvelle version du logiciel.
 - *permissive* : possibilité de créer une version dérivée non-libre.

## Conséquences directes pour l'entreprise éditrice

Pour une entreprise, créer et diffuser un logiciel libre implique:

 - Difficile de vendre plusieurs fois le même logiciel libre:
**le premier utilisateur peut redistribuer lui-même le logiciel**, y-compris le revendre.
 - Intégrer un petit morceau de code *copyleft* dans un produit plus
grand **oblige à publier l'ensemble** du produit sous une licence *copyleft*.
 - Impossible de tirer de l'argent de ses **brevets logiciels**
 - **Limitation des revenus** que l'on peut tirer de ses utilisateurs:
abonnement obligatoire, publicité dans le logiciel, etc. ne sont plus viables. 
 - **Concurrence** accrue (barrière d'entrée dans le marché abaissée)

-------------

Les licences de type copyleft ont inspiré à Steve Ballmer la déclaration suivante: 


>  Linux is a cancer that attaches itself in an intellectual property sense
to everything it touches. That's the way that the license works.

> **Steve Ballmer**, CEO, Microsoft (1er juin 2001)

## Conséquences directes pour l'entreprise utilisatrice

Les libertés garanties sont faites pour protéger l'utilisateur du logiciel,
et donc bénéficient directement aux entreprises qui utilisent des logiciels libres.

Cependant:


 - Certains **standards fermés** (formats de fichiers, protocoles de communication)
ne sont bien supportés que par les logiciels propriétaires des sociétés qui les créent.
L'exemple le plus connu est certainement le format *DOCX* de Microsoft.
 - Parfois, il est plus difficile d'obtenir du **support** pour un logiciel libre.
 - Pour les plus petits logiciels libre, **aucune garantie de pérennité** n'est donnée.

*Source: [CIO magazine](http://www.cio.com/article/2378859/open-source-tools/7-reasons-not-to-use-open-source-software.html)*

# État des lieux
## Logiciels libres en entreprise

Après les constatations précédentes, on pourrait s'attendre à ce que les
entreprises fuient le logiciel libre. **Ce n'est pas ce que l'on observe.**

## Mais que s'est-il passé ?

![Satya Nadella, CEO de Microsoft, lors d’une conférence en 2015. Photographie de Richard Morgenstein — Microsoft](https://fortunedotcom.files.wordpress.com/2015/09/satyanadellalinux.jpg?w=300&quality=95)

## Qui publie et utilise des logiciels libres ?

Toutes les entreprises suivantes **éditent** un nombre
significatif de logiciels libres, et **affichent publiquement** leur attachement à
l'open source:

 - [**Google**](https://developers.google.com/open-source/): *Recognizing the vital role that open source software plays at Google, […]*
 - [**Apple**](https://opensource.apple.com/) : *Apple continues to both lead and make significant contributions to many Open Source projects*
 - [**Facebook**](https://code.facebook.com/projects/) : *open source has been a huge part of our engineering philosophy*
 - [**Twitter**](https://twitter.github.io/): *Twitter is built on open source software.*
 - [**Microsoft**](https://opensource.microsoft.com/resources) (depuis moins longtemps):
*Microsoft engineers release, contribute to and use open source every day to do great things.*
 - [**Oracle**](http://www.oracle.com/us/technologies/open-source/overview/index.html) : *Oracle is clearly embracing and offering leading open source solutions as a viable choice*
 - [**Intel**](https://software.intel.com/en-us/open-source) : *Intel Drives the Open Source Spirit Forward*

---

Tous les GAFAM, et de nombreux acteurs importants de l'informatique
professionnelle contribuent.

De nombreuses entreprises plus petites, et notamment beaucoup des startups
du domaine de la technologie partagent la même vision du libre.

## Comment l'expliquer ?

Les grosses entreprises de l'informatique voient souvent de l'intérêt à publier un logiciel
sous licence libre

 * Cela améliore l'image de marque auprès des développeurs et des chercheurs.
 * Cela permet d'imposer plus facilement et plus rapidement une nouvelle technologie ou une nouvelle approche dans un domaine.
 * Cela évite la fragmentation d'un marché, les entreprises et les développeurs indépendants préférant
contribuer au logiciel libre et le proposer également à leurs clients que de créer un équivalent.

## État des lieux pour les entreprises utilisatrices

### Les entreprises citées précédemment sont toutes dans le domaine de l'informatique.

Qu'en est-il de l'utilisation de logiciel libre par libre par les entreprises d'autres domaines ?

## Loin derrière dans certains domaines

Dans certains domaines de l'informatique cruciaux pour les entreprises,
quelques logiciels propriétaires dominent leur marché.

On peut citer

 - Les systèmes d'exploitation de bureau. Windows est ultra-majoritaire en entreprise,
linux n'est que très rarement utilisé sur les postes de travail en dehors des entreprises
de développement logiciel.
 - La bureautique, avec la suite Office de Microsoft. LibreOffice arrive loin derrière
en termes de parts de marché, en particulier chez les entreprises.
 - Les progiciels de gestion. SAP, SAGE, Microsoft et Oracle dominent le marché,
et toutes leurs solutions sont propriétaires. Odoo, ERPNext et Dolibarr
sont destinés aux plus petites entreprises, et moins utilisés.
 - La gestion de document. Sharepoint de Microsoft est très utilisé en entreprise.

## En position dominante dans d'autres

Dans d'autres domaines, aussi cruciaux pour les entreprises,
ce sont des logiciels libres qui forment les standards
*de facto*.

Parfois, ils ne dominent pas le marché mais sont en forte progression.

---

### Bases de données
![trois des cinq systèmes de base de données les plus populaires sont libres. Les bases orientées Big-Data sont libres et en forte progression. Source: db-engines.com](databases.png)

---

### Systèmes d'exploitation pour serveur

Selon W3Cook, qui mesure régulièrement les parts de marché des systèmes
d'exploitations utilisés sur les serveurs accessibles depuis internet,
en mai 2015

 - **96,6 %** des serveurs les plus populaires sont sous Linux (système *copyleft*)
 - **1,7 %** sont sous FreeBSD (système libre sous une licence *permissive*)
 - **1,7** sont sous Windows (propriétaire).

---

### Analyse de données

Les systèmes de sauvegarde et analyse de grosses quantités de données
sont de plus en plus demandés par les entreprises avec le développement de
la récolte de données
et la baisse des coûts du matériel.

Dans le domaine de l'analyse de données, *R* et *Python* (avec *SciPy*), tous deux
libres, font office de référence.

Pour la sauvegarde et le traitement *Hadoop*, *Spark*, et les *bases de données NoSQL*
libres sont devant leurs concurrents propriétaires.
 
## Comment l'expliquer

On voit que pour ce qui est de l'utilisation de logiciels,
les décisions sont faites de manières très pragmatiques.

Certains logiciels libres proposent un très bon rapport qualité-prix,
et sont produits par de grosses entreprises ou fondations, qui ont les moyens
d'assurer leur support

 * Les logiciels libres sont très présents dans certains domaines depuis très longtemps.
 * Ils sont très populaires dans le domaine de la recherche.
 * Ils sont plus utilisés dans le domaine du web et de la gestion de données que dans les applications métier.

# Transition vers le logiciel libre

## Raisons

Certaines entreprises ou collectivités souhaitent **migrer du logiciel propriétaire
vers le logiciel libre**.

Le plus souvent, pour des raisons économiques, pour **économiser le prix des licences**
de logiciels propriétaires, mais aussi souvent pour **s'affranchir de la dépendance** à
un éditeur de logiciel particulier, et parfois pour des raisons **éthiques** (migrations
au sein d'administrations, de communes, de gouvernement).

Cela peut aussi être pour des raisons de **sécurité**, un système libre pouvant être entièrement
audité en interne.

On peut citer par exemple la [migration de la gendarmerie nationale vers linux](http://www.lapresse.ca/le-soleil/z/archives/vu-dailleurs/201409/27/01-4804250-france-linux-chez-les-gendarmes.php).

## Coûts

Le calcul le plus simple à faire est celui du prix des licences économisées.

Cependant, il faut prendre en compte

  * les **coûts de formation**
  * les différences de **coût de maintenance**
  * les différences de **coût de support**

## Risques

Il convient de prendre en compte les risques liés à tout changement important
dans un système d'information.

 * Baisse de productivité et mécontentement des utilisateurs habitués à une ancienne
solution.

 * Risques d'incompatibilités avec les autres systèmes de l'entreprise.

Et pour le logiciel libre en particulier

 * Risques liés à la pérennité du logiciel si sa communauté est réduite et ses développeurs bénévoles.

# Conclusion

## Le logiciel libre est un défi pour les entreprises

Le logiciel libre est aujourd'hui un défi pour les entreprises.

Il impose de nombreuses contraintes à l'entreprise qui les publie
(le modèle de distribution classique devient non-viable),
et certaines à celle qui les utilise (selon le logiciel, manque de garantie).

Cependant, il constitue une manière innovante d'approcher l'industrie logicielle,
adaptée par de nombreux grands acteurs, car il permet une **évolution rapide**,
une **mutualisation des coûts de développement**,
une **baisse des coûts d'acquisition**,
et
une meilleure **image de marque**.

C'est certainement pour ces raisons
[qu'une étude du cabinet PAC](http://www.open-source-guide.com/Actualites/L-open-source-un-marche-a-6-milliards-d-euros-en-france-d-ici-2020)
a estimé que le marché de l'open source en France atteindrait **6 milliards d'euros
en France en 2020**, alors qu'il était de 4,1 milliards en 2015.

## Notes

 - Cette présentation est elle-même libre, sous licence
[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

 - La source est disponible en ligne sur Github:
[github.com/lovasoa/logiciel-libre-et-entreprise](https://github.com/lovasoa/logiciel-libre-et-entreprise)

