---
title: "BAM (Biodiversity Around Me)"
subtitle: Open biodiversity data easily accessible to everyone, everywhere!
authors:
    - Camille MONCHICOURT
categories:
    - Article
comments: true
date: 2025-12-11
description: "A new biodiversity widget to display the species observed around a location."
icon: "material/bee-flower"
image: "https://geonature.fr/documents/autres/BAM/BAM-widget-thumb.png"
license: cc4_by-sa
robots: index, follow
tags:
    - Biodiversity
    - OpenSource
    - Widget
---

# BAM (Biodiversity Around Me), open biodiversity data easily accessible to everyone, everywhere!

:calendar: Date de publication initiale : {{ page.meta.date | date_localized }}

![BAM widget](https://geonature.fr/documents/autres/BAM/BAM-logo.png "BAM widget"){: .img-thumbnail-left }

**Un nouveau widget de biodiversité, libre, développé par les parcs nationaux français et reconnu internationalement, pour afficher les espèces observées autour d'un lieu.**

Et si, en quelques clics, vous pouviez afficher et intégrer la liste des espèces observées autour de vous, d’un gîte, d’un sentier, d'un événement ou même de votre école ?

C’est désormais possible grâce à [BAM – Biodiversité Autour de Moi](https://si.ecrins-parcnational.com/blog/2025-08-BAM-widget.html), un nouvel outil libre développé
par les parcs nationaux des Écrins et des Cévennes !

[Commenter cet article :fontawesome-solid-comments:](#__comments "Aller aux commentaires"){: .md-button }
{: align=middle }

## Un accès simple à la biodiversité, partout et pour tous !

Depuis plusieurs années, les données sur la biodiversité se multiplient grâce aux programmes participatifs internationaux
([iNaturalist](https://www.inaturalist.org/), [Pl@ntNet](https://plantnet.org/), [eBird](https://ebird.org/)…), aux naturalistes professionnels ou amateurs,
et aux plateformes nationales comme l'[INPN](https://inpn.mnhn.fr/).

Mais une question restait en suspens : comment rendre toutes ces informations accessibles au plus grand nombre ?

C’est pour répondre à ce défi que plusieurs parcs nationaux français, coordonnés par Amandine Sahl (Parc national des Cévennes), Jacques Fize et Camille Monchicourt (Parc national des Écrins),
ont imaginé et développé un outil très simple d’usage : un petit widget capable d’afficher automatiquement toutes les espèces observées autour d’un lieu.

![BAM screenshot](https://github.com/user-attachments/assets/39ae6276-c95e-469d-8247-5ba781f76159)

## Comment fonctionne BAM ?

BAM se présente comme un widget— prêt à être intégré sur une page web ou une application.

Il suffit d’y indiquer un lieu ou une zone de recherche pour que le widget affiche :

- le nom des espèces observées,
- leur dernière date d’observation,
- une photo,
- parfois même un enregistrement sonore.

Toutes ces informations viennent directement de grandes bases de données mondiales et ouvertes comme le [GBIF](https://www.gbif.org/fr/)  ou [Wikidata](https://www.wikidata.org/).
Elles peuvent également provenir de sources plus locales via [GeoNature](https://geonature.fr/).

![Architecture BAM](https://github.com/user-attachments/assets/0adf126e-0219-49de-a8c0-7ef6c9b9e8c7)

L'outil n'a besoin d’aucune installation, ni de serveur ni de base de données : il interroge dynamiquement des API pour récupérer les observations collectées à jour.
Il fonctionne partout dans le monde, et est multilingue (Français 🇫🇷, Anglais 🇬🇧, Espagnol 🇪🇸, Italien 🇮🇹, Allemand 🇩🇪, Tchèque 🇨🇿)

BAM peut ainsi être utilisé pour :

- Illustrer les résultats d’un programme de recherche ou d’un inventaire
- Accompagner un observatoire ou un atlas local de biodiversité
- Partager des connaissances avec les élus, techniciens ou usagers d’un territoire
- Contribuer à la visibilité des données ouvertes de biodiversité et encourager leur publication
- Valoriser la biodiversité autour de sentiers, refuges, villages ou sites naturels
- Proposer des outils éducatifs pour les enseignants, classes nature et formations

Des parcs naturels et sentiers aux écoles, refuges de montagne, sites d'escalade, événements ou hébergements, nous espérons voir le widget BAM intégré dans un large éventail de sites,
éveillant curiosité et sensibilisation à la nature auprès de nouveaux publics.

Voici un exemple d'intégration du widget BAM, avec les espèces observées autour de l'école forestière dans le Parc national du Banco à Abidjan (rayon 200m) :

<iframe
        title="BAM"
        width="100%" height="640" allow="geolocation"
        src="https://pnx-si.github.io/BAM-widget/#/?widgetType=mapList&nbTaxonPerLine=4&primaryColor=009485&switchModeAvailable=true&showFilters=true&lang=fr&buffer=200&x=-4.05224&y=5.38471"></iframe>

Un [configurateur du widget](https://pnx-si.github.io/BAM-widget/#/config) est disponible pour faciliter le paramétrage du widget et son intégration, en définissant son mode d'affichage et ses options (carte et liste ou liste uniquement, mode galerie ou détaillé, nombre de résultats par ligne, affichage des filtres ou non, zone de recherche, source de données, couleur...).

BAM peut aussi être utilisé comme un explorateur de données de biodiversité autonome, adapté à un usage mobile et installable sous forme de PWA,
en se rendant directement sur <https://pnx-si.github.io/BAM-widget/>.

## Une reconnaissance internationale

Le 24 octobre 2025, à Bogotá (Colombie), BAM a reçu un prix lors du [défi international Ebbe Nielsen](https://www.gbif.org/fr/news/2LugQxJfG2kCzjiJocXzVZ/des-laureats-de-norvege-et-daustralie-partagent-la-premiere-place-du-defi-ebbe-nielsen-2025),
organisé par le GBIF, qui récompense chaque année les meilleures applications utilisant les données ouvertes sur la biodiversité.

![L'équipe des parcs nationaux à l'origine et la réalisation du projet BAM](https://github.com/user-attachments/assets/caf93b35-e20b-4174-9448-2b072b062bae)

Une belle reconnaissance pour ce projet porté par les équipes des parcs nationaux des Cévennes et des Écrins, déjà lauréates de ce défi en 2019 pour l’outil GeoNature-atlas.

Avec ce nouveau projet, les 2 parcs nationaux continuent leur démarche commune de développement d’outils libres pour répondre à des besoins locaux et spécifiques de manière générique et globale,
initiée depuis un peu plus de 10 ans avec les projets mutualisés Geotrek et GeoNature.

## Pour aller plus loin

- [Tester l’outil BAM](https://pnx-si.github.io/BAM-widget/)
- [Accéder au configurateur de widget BAM](https://pnx-si.github.io/BAM-widget/#/config)
- [Documentation complète de BAM](https://pnx-si.github.io/BAM-widget/docs/#/)
- [Présentation générale de BAM](https://si.ecrins-parcnational.com/blog/2025-08-BAM-widget.html)
- [Code source de BAM](https://github.com/PnX-SI/BAM-widget)
- [Résultats du défi Ebbe Nielsen 2025](https://www.gbif.org/fr/news/2LugQxJfG2kCzjiJocXzVZ/des-laureats-de-norvege-et-daustralie-partagent-la-premiere-place-du-defi-ebbe-nielsen-2025)

----

<!-- geotribu:authors-block -->

{% include "licenses/cc4_by-sa.md" %}
