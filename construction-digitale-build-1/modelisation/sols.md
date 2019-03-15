# Sols

![](../../.gitbook/assets/principe-de-mod.png)

{% tabs %}
{% tab title="LOD" %}
![LOG 200  /  LOI 200 : &#xC9;paisseur de base suppos&#xE9;e](../../.gitbook/assets/image%20%285%29.png)
{% endtab %}

{% tab title="Règles" %}
* Des types de dalles doivent être créées séparément pour chacun des matériaux, niveaux et épaisseurs différents
* Les sols finis doivent être associés aux niveaux courant sans décalage et les dalles structurelles doivent être associées au même niveau mais avec un décalage supérieur correspondant à l'épaisseur du sol fini adjacent.
* Les constructions horizontales et les joints de dilatation doivent être modélisés avec leurs côtes extérieures.
* Les recharges doivent être modélisées dans des familles de dalle différentes
{% endtab %}

{% tab title="Nommage du type" %}
"NATURE"\__"INT ou EXT"\__"Ep"

INT : si intérieur 

EXT : si extérieur 

EP : en mètre

Exemple : pour une dalle béton Extérieur de 20cm :

BETON\_EXT\_0,2
{% endtab %}
{% endtabs %}

![](../../.gitbook/assets/wallpaper_fnum_black.jpg)

