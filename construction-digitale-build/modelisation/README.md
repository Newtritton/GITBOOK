# 2. Règles et paramétrages de la maquette numérique

![](../../.gitbook/assets/regles-mod.png)

{% hint style="danger" %}
**Tous les éléments sont modélisés tel que construit.** C’est-à-dire que dans la mesure des informations à notre disposition, pour un complexe de façade ou pour un sol par exemple, la couche béton fera l'objet d'un "objet" sol modélisé et la couche de finition fera l'objet d'un autre "objet" sol modélisé.
{% endhint %}

{% hint style="warning" %}
Un **matériau** doit être défini pour chaque élément de la maquette. Si ce matériau est connu, il portera comme nom, la nature de l'élément auquel il est rattaché \(exemple : bois, métal, alu…\). Si ce matériau n'est pas connu, son nom sera celui du type de l'élément auquel il est affecté, exemple : pour un cadre de fenêtre dont on ne sait pas si c'est du pvc, bois,..., le matériaux s'appellera : Z\_CADRE.
{% endhint %}

{% hint style="warning" %}
Le **nom d’un élément** doit désigner de manière générique l’objet qu’il représente \(exemple : FENETRE-IMPOSTE-HAUTE_\). Ce nom doit être en majuscule avec des « \__» en remplacement des espaces et précédé du suffixe "Z\_".Ce dernier permet de différencier les éléments revit de base, des éléments que nous avons ajouté dans la maquette.

Liste des éléments concernés :

* Matériaux
* Styles de lignes
* Familles
* Hachures/motifs
{% endhint %}

Pour ce qui est de la modélisation concrète de chaque élément, se référer à la partie suivante :

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

{% tab title="Liste des paramètres partagés" %}

{% endtab %}
{% endtabs %}

Unité de base

Purge du fichier

Nommage de la maquette

Sous-projet



![](../../.gitbook/assets/wallpaper_fnum_black.jpg)

