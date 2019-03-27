# Règles et paramétrages de la maquette numérique

## GÉNÉRALITÉS

![](../../.gitbook/assets/regles-majeures.png)

### Unité du projet

| Type | Unité | Précision | Symbole |
| :--- | :--- | :--- | :--- |
| Longueur | Mètres | 0.00 | M |
| Surface | Mètres carrés | 0.00 | M² |
| Volume | Mètres cubes | 0.00 | M³ |
| Inclinaison | Degrés décimaux | 0.00 | ° |
| Pente | Pourcentage | 0.00 | % |

### Nommage de la maquette :

**NomProjet**\_**NomBat**\_**PHASE**\_**EMETTEUR**\_**TYPE**

**NomProjet :** Nom simplifié du projet \(transmis par le BIM Manager\)

**PHASE :** EXP

**EMETTEUR :** LFN ou autre trigramme propre à l'entreprise

| TYPE | Description |
| :--- | :--- |
| ARC | Architecture |
| CVC | Chauffage/Ventilation/Climatisation |
| PBL | Plomberie |
| STR | Structure |
| ELE | Electricité |
| SITE | Environnement |
| GHOST | Fichier conteneur DWG |
| URS | Fichier de base quadrillage/Niveau et compil des maquettes |

### Matériaux

{% hint style="warning" %}
Un **matériau** doit être défini pour chaque élément de la maquette. Si ce matériau est connu, il portera comme nom, la nature de l'élément auquel il est rattaché \(exemple : bois, métal, alu…\). Si ce matériau n'est pas connu, son nom sera celui du type de l'élément auquel il est affecté, exemple : pour un cadre de fenêtre dont on ne sait pas si c'est du pvc, bois,..., le matériaux s'appellera : Z\_CADRE.
{% endhint %}

### Nommage des éléments

{% hint style="warning" %}
Le **nom d’un élément** doit désigner de manière générique l’objet qu’il représente \(exemple : FENETRE-IMPOSTE-HAUTE_\). Ce nom doit être en majuscule avec des « -_» en remplacement des espaces et précédé d'un suffixe :

* A\_ : Si l'architecte est détenteur de l'élément
* S\_ : Si le BE Structure est détenteur de l'élément
* C\_ : Si il s'agit d'un élément du BE CVC
* P\_ : Si il s'agit d'un élément du BE Plomberie
* E\_ : Si il s'agit d'un élément du BE Electricité
* F\_ : Si il s'agit d'un élément du BE Charpente

Ce dernier permet de différencier les éléments revit de base, des éléments ajouté par chaque intervenant dans la maquette.

Exemple : A\_FENETRE-IMPOSTE-HAUTE

Liste des éléments concernés :

* Matériaux
* Styles de lignes
* Familles
* Hachures/motifs
{% endhint %}

### Nommage des systèmes MEP

### Création des sous projets



### Classification de l'arborescence



### Les paramètres partagés

•         Création des paramètres : tous les nouveaux paramètres créés par les émetteurs seront des paramètres partagés dans le cas d’une extraction des données par nomenclature.

## RÈGLES DE MODÉLISATION

![](../../.gitbook/assets/principe-de-mod.png)

### Les essentiels

{% hint style="danger" %}
**Modélisation par étage :** les éléments du bâtiment doivent être modélisés séparément pour chaque étage**.**

**Tous les éléments sont modélisés tel que construit.** C’est-à-dire que dans la mesure des informations à notre disposition, pour un complexe de façade ou pour un sol par exemple, la couche béton fera l'objet d'un "objet" sol modélisé et la couche de finition fera l'objet d'un autre "objet" sol modélisé.

**Les éléments composant le bâtiment doivent être modélisés par les outils et objets adéquats.** Il ne faut pas détourner l’usage d’un outil en modélisant par exemple un poteau avec l’outil mur ou une fenêtre avec l’outil « mur rideau ».

**Purge de la maquette** : a chaque remise de maquette, cette dernière doit être purgé.
{% endhint %}

### Modélisation spécifique

{% tabs %}
{% tab title="ARCHITECTURE & STRUCTURE" %}
{% page-ref page="6-8.md" %}

{% page-ref page="covea-pkl.md" %}

{% page-ref page="charpente-metal.md" %}

{% page-ref page="poutres.md" %}

{% page-ref page="sols.md" %}

{% page-ref page="plafonds.md" %}

{% page-ref page="toits.md" %}

{% page-ref page="portes.md" %}

{% page-ref page="fenetres.md" %}

{% page-ref page="escaliers.md" %}

{% page-ref page="rampes.md" %}

{% page-ref page="mobiliers.md" %}

{% page-ref page="modeles-generiques.md" %}

{% page-ref page="garde-corps.md" %}

{% page-ref page="pieces.md" %}
{% endtab %}

{% tab title="MEP" %}

{% endtab %}
{% endtabs %}











![](../../.gitbook/assets/wallpaper_fnum_black.jpg)

