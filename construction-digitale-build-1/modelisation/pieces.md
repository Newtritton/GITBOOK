# Pièces

![](../../.gitbook/assets/principe-de-mod.png)

{% tabs %}
{% tab title="LOD" %}
![LOG 300 / LOI 300 : Espaces individuels sch&#xE9;matis&#xE9;s](../../.gitbook/assets/image%20%281%29.png)
{% endtab %}

{% tab title="Règles" %}
Les pièces doivent être modélisées avec comme limites verticales le niveau de sol fini et le niveau de plafond fini.

* Les éléments suivants sont utilisés pour les limites des pièces et les calculs de volume dans Revit. Murs rideaux, standard, par face Toits \(rideaux, standard, par face\) Sols \(rideaux, standard, par face\) Plafonds \(rideaux, standard, par face\) Poutres \(architectural, structural avec matériau béton\) Systèmes rideaux par face Lignes de séparation de pièce Terre-pleins
* Attention aucune pièce ne doit avoir une hauteur sous plafond de moins d'1m80. SI c'est le cas, il faut faire une ligne de séparation de pièce pour retirer l'espace dont la hauteur est inférieur à 1m80.
{% endtab %}

{% tab title="Nommage du type" %}
<table>
  <thead>
    <tr>
      <th style="text-align:left">Nom des pi&#xE8;ces (attention ne pas mettre d&apos;accents dans les nom)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">Accueil</td>
    </tr>
    <tr>
      <td style="text-align:left">Atrium</td>
    </tr>
    <tr>
      <td style="text-align:left">Hall</td>
    </tr>
    <tr>
      <td style="text-align:left">Lobby</td>
    </tr>
    <tr>
      <td style="text-align:left">Auvent</td>
    </tr>
    <tr>
      <td style="text-align:left">Balcon</td>
    </tr>
    <tr>
      <td style="text-align:left">Cloison fixe</td>
    </tr>
    <tr>
      <td style="text-align:left">Cloison mobile</td>
    </tr>
    <tr>
      <td style="text-align:left">Comble amenageable</td>
    </tr>
    <tr>
      <td style="text-align:left">Comble non amenageable</td>
    </tr>
    <tr>
      <td style="text-align:left">Embrasures</td>
    </tr>
    <tr>
      <td style="text-align:left">Galerie non technique</td>
    </tr>
    <tr>
      <td style="text-align:left">Loggia</td>
    </tr>
    <tr>
      <td style="text-align:left">Murs exterieurs</td>
    </tr>
    <tr>
      <td style="text-align:left">Murs interieurs</td>
    </tr>
    <tr>
      <td style="text-align:left">Porche</td>
    </tr>
    <tr>
      <td style="text-align:left">Poteaux porteurs</td>
    </tr>
    <tr>
      <td style="text-align:left">Sous-sol non amenage</td>
    </tr>
    <tr>
      <td style="text-align:left">Tremie</td>
    </tr>
    <tr>
      <td style="text-align:left">Vide de construction</td>
    </tr>
    <tr>
      <td style="text-align:left">Vide sanitaire</td>
    </tr>
    <tr>
      <td style="text-align:left">Bureau</td>
    </tr>
    <tr>
      <td style="text-align:left">Bureau temporaire</td>
    </tr>
    <tr>
      <td style="text-align:left">Open space</td>
    </tr>
    <tr>
      <td style="text-align:left">Reprographie legere</td>
    </tr>
    <tr>
      <td style="text-align:left">Salle de commandement</td>
    </tr>
    <tr>
      <td style="text-align:left">Salle operationnelle</td>
    </tr>
    <tr>
      <td style="text-align:left">Surface de production</td>
    </tr>
    <tr>
      <td style="text-align:left">Coin cafe</td>
    </tr>
    <tr>
      <td style="text-align:left">Documentation</td>
    </tr>
    <tr>
      <td style="text-align:left">Espace photocopie</td>
    </tr>
    <tr>
      <td style="text-align:left">salle d&apos;attente</td>
    </tr>
    <tr>
      <td style="text-align:left">Ascenseur</td>
    </tr>
    <tr>
      <td style="text-align:left">Ascenseur plancher depart</td>
    </tr>
    <tr>
      <td style="text-align:left">Cabine ascenseur</td>
    </tr>
    <tr>
      <td style="text-align:left">Circulation</td>
    </tr>
    <tr>
      <td style="text-align:left">Circulation commune</td>
    </tr>
    <tr>
      <td style="text-align:left">Degagement</td>
    </tr>
    <tr>
      <td style="text-align:left">Escalier</td>
    </tr>
    <tr>
      <td style="text-align:left">Escalier plancher depart</td>
    </tr>
    <tr>
      <td style="text-align:left">Monte charge</td>
    </tr>
    <tr>
      <td style="text-align:left">Palier</td>
    </tr>
    <tr>
      <td style="text-align:left">Palier intermediaire</td>
    </tr>
    <tr>
      <td style="text-align:left">Rampe</td>
    </tr>
    <tr>
      <td style="text-align:left">Sas</td>
    </tr>
    <tr>
      <td style="text-align:left">Sas de securite</td>
    </tr>
    <tr>
      <td style="text-align:left">Bassins</td>
    </tr>
    <tr>
      <td style="text-align:left">Cour</td>
    </tr>
    <tr>
      <td style="text-align:left">Coursive</td>
    </tr>
    <tr>
      <td style="text-align:left">Entrepot</td>
    </tr>
    <tr>
      <td style="text-align:left">Espace couvert non ferme</td>
    </tr>
    <tr>
      <td style="text-align:left">Hangar</td>
    </tr>
    <tr>
      <td style="text-align:left">Ouvrage technique exterieur</td>
    </tr>
    <tr>
      <td style="text-align:left">Piscine</td>
    </tr>
    <tr>
      <td style="text-align:left">Station service</td>
    </tr>
    <tr>
      <td style="text-align:left">Stockage exterieur</td>
    </tr>
    <tr>
      <td style="text-align:left">Terrasse</td>
    </tr>
    <tr>
      <td style="text-align:left">Terrasse non accessible</td>
    </tr>
    <tr>
      <td style="text-align:left">Toiture terrasse</td>
    </tr>
    <tr>
      <td style="text-align:left">Veranda</td>
    </tr>
    <tr>
      <td style="text-align:left">Gaine technique</td>
    </tr>
    <tr>
      <td style="text-align:left">Casernement</td>
    </tr>
    <tr>
      <td style="text-align:left">Logement de fonction</td>
    </tr>
    <tr>
      <td style="text-align:left">Armurerie</td>
    </tr>
    <tr>
      <td style="text-align:left">Atelier</td>
    </tr>
    <tr>
      <td style="text-align:left">Atelier lourd</td>
    </tr>
    <tr>
      <td style="text-align:left">Cabinet medical</td>
    </tr>
    <tr>
      <td style="text-align:left">Creche</td>
    </tr>
    <tr>
      <td style="text-align:left">Espace pour animaux</td>
    </tr>
    <tr>
      <td style="text-align:left">Imprimerie</td>
    </tr>
    <tr>
      <td style="text-align:left">Infirmerie</td>
    </tr>
    <tr>
      <td style="text-align:left">Laboratoire</td>
    </tr>
    <tr>
      <td style="text-align:left">Local chauffeur</td>
    </tr>
    <tr>
      <td style="text-align:left">Local courrier</td>
    </tr>
    <tr>
      <td style="text-align:left">Local de garde &#xE0; vue</td>
    </tr>
    <tr>
      <td style="text-align:left">Local de retention</td>
    </tr>
    <tr>
      <td style="text-align:left">Local dechets</td>
    </tr>
    <tr>
      <td style="text-align:left">Local gardiennage</td>
    </tr>
    <tr>
      <td style="text-align:left">Local gestionnaire</td>
    </tr>
    <tr>
      <td style="text-align:left">Local informatique</td>
    </tr>
    <tr>
      <td style="text-align:left">Local menage</td>
    </tr>
    <tr>
      <td style="text-align:left">Local photo</td>
    </tr>
    <tr>
      <td style="text-align:left">Local poubelle</td>
    </tr>
    <tr>
      <td style="text-align:left">Local regie</td>
    </tr>
    <tr>
      <td style="text-align:left">Local stockage</td>
    </tr>
    <tr>
      <td style="text-align:left">Local stockage commun</td>
    </tr>
    <tr>
      <td style="text-align:left">Local syndical</td>
    </tr>
    <tr>
      <td style="text-align:left">Local VDI</td>
    </tr>
    <tr>
      <td style="text-align:left">Local velo</td>
    </tr>
    <tr>
      <td style="text-align:left">Office</td>
    </tr>
    <tr>
      <td style="text-align:left">Poste de garde</td>
    </tr>
    <tr>
      <td style="text-align:left">Poste de securite</td>
    </tr>
    <tr>
      <td style="text-align:left">Regie</td>
    </tr>
    <tr>
      <td style="text-align:left">Reprographie lourde</td>
    </tr>
    <tr>
      <td style="text-align:left">Salle aveugle</td>
    </tr>
    <tr>
      <td style="text-align:left">Salle blanche et grise</td>
    </tr>
    <tr>
      <td style="text-align:left">Salle de sport</td>
    </tr>
    <tr>
      <td style="text-align:left">Salle des coffres</td>
    </tr>
    <tr>
      <td style="text-align:left">Salle informatique</td>
    </tr>
    <tr>
      <td style="text-align:left">Salle serveurs</td>
    </tr>
    <tr>
      <td style="text-align:left">Services generaux</td>
    </tr>
    <tr>
      <td style="text-align:left">Stand de tir</td>
    </tr>
    <tr>
      <td style="text-align:left">Cuves</td>
    </tr>
    <tr>
      <td style="text-align:left">Local eau froide</td>
    </tr>
    <tr>
      <td style="text-align:left">Local eau glacee</td>
    </tr>
    <tr>
      <td style="text-align:left">Local electrique</td>
    </tr>
    <tr>
      <td style="text-align:left">Local FT</td>
    </tr>
    <tr>
      <td style="text-align:left">Local GSM</td>
    </tr>
    <tr>
      <td style="text-align:left">Local haute tension</td>
    </tr>
    <tr>
      <td style="text-align:left">Local technique</td>
    </tr>
    <tr>
      <td style="text-align:left">Local technique climespace</td>
    </tr>
    <tr>
      <td style="text-align:left">Local technique commun</td>
    </tr>
    <tr>
      <td style="text-align:left">Local technique CPCU</td>
    </tr>
    <tr>
      <td style="text-align:left">Local technique CTA</td>
    </tr>
    <tr>
      <td style="text-align:left">Local technique relevage</td>
    </tr>
    <tr>
      <td style="text-align:left">Local technique ventilation basse</td>
    </tr>
    <tr>
      <td style="text-align:left">Local technique ventilation haute</td>
    </tr>
    <tr>
      <td style="text-align:left">Local technique ventilation haute parking</td>
    </tr>
    <tr>
      <td style="text-align:left">Tableau divisionnaire</td>
    </tr>
    <tr>
      <td style="text-align:left">Aire de circulation v&#xE9;hicule exterieure</td>
    </tr>
    <tr>
      <td style="text-align:left">Aire de circulation v&#xE9;hicule interieure</td>
    </tr>
    <tr>
      <td style="text-align:left">Aire de man&#x153;uvre exterieure</td>
    </tr>
    <tr>
      <td style="text-align:left">Aire de man&#x153;uvre interieure</td>
    </tr>
    <tr>
      <td style="text-align:left">Box</td>
    </tr>
    <tr>
      <td style="text-align:left">Circulation vehicules</td>
    </tr>
    <tr>
      <td style="text-align:left">Garage</td>
    </tr>
    <tr>
      <td style="text-align:left">Hall livraisons</td>
    </tr>
    <tr>
      <td style="text-align:left">Parking exterieur</td>
    </tr>
    <tr>
      <td style="text-align:left">Parking interieur</td>
    </tr>
    <tr>
      <td style="text-align:left">Place de parking exterieure</td>
    </tr>
    <tr>
      <td style="text-align:left">Place de parking interieure</td>
    </tr>
    <tr>
      <td style="text-align:left">Quai de chargement</td>
    </tr>
    <tr>
      <td style="text-align:left">Rampe acces parking exterieure</td>
    </tr>
    <tr>
      <td style="text-align:left">Rampe acces parking interieure</td>
    </tr>
    <tr>
      <td style="text-align:left">Surface de stationnement exterieure</td>
    </tr>
    <tr>
      <td style="text-align:left">Surface de stationnement interieure</td>
    </tr>
    <tr>
      <td style="text-align:left">Cafeteria</td>
    </tr>
    <tr>
      <td style="text-align:left">Cuisine</td>
    </tr>
    <tr>
      <td style="text-align:left">Kitchenette</td>
    </tr>
    <tr>
      <td style="text-align:left">Refectoire</td>
    </tr>
    <tr>
      <td style="text-align:left">Repas</td>
    </tr>
    <tr>
      <td style="text-align:left">Restaurant</td>
    </tr>
    <tr>
      <td style="text-align:left">Reunion repas</td>
    </tr>
    <tr>
      <td style="text-align:left">Ampitheatre</td>
    </tr>
    <tr>
      <td style="text-align:left">Auditorium</td>
    </tr>
    <tr>
      <td style="text-align:left">Bar</td>
    </tr>
    <tr>
      <td style="text-align:left">Bibliotheque</td>
    </tr>
    <tr>
      <td style="text-align:left">Club</td>
    </tr>
    <tr>
      <td style="text-align:left">Digilab</td>
    </tr>
    <tr>
      <td style="text-align:left">Espace club</td>
    </tr>
    <tr>
      <td style="text-align:left">Espace de reception</td>
    </tr>
    <tr>
      <td style="text-align:left">Local activites culturelles</td>
    </tr>
    <tr>
      <td style="text-align:left">Lounge</td>
    </tr>
    <tr>
      <td style="text-align:left">Salle collective</td>
    </tr>
    <tr>
      <td style="text-align:left">salle d&apos;attente commune</td>
    </tr>
    <tr>
      <td style="text-align:left">Salle d&apos;audience</td>
    </tr>
    <tr>
      <td style="text-align:left">Salle de conf&#xE9;rence</td>
    </tr>
    <tr>
      <td style="text-align:left">Salle de cours</td>
    </tr>
    <tr>
      <td style="text-align:left">Salle de documentation</td>
    </tr>
    <tr>
      <td style="text-align:left">Salle de formation</td>
    </tr>
    <tr>
      <td style="text-align:left">Salle de levee de doute</td>
    </tr>
    <tr>
      <td style="text-align:left">Salle de projet</td>
    </tr>
    <tr>
      <td style="text-align:left">Salle de reception</td>
    </tr>
    <tr>
      <td style="text-align:left">Salle de repos</td>
    </tr>
    <tr>
      <td style="text-align:left">Salle de reunion</td>
    </tr>
    <tr>
      <td style="text-align:left">Salle de reunion COMEX</td>
    </tr>
    <tr>
      <td style="text-align:left">Salle de seminaire</td>
    </tr>
    <tr>
      <td style="text-align:left">Salle d&apos;equipe</td>
    </tr>
    <tr>
      <td style="text-align:left">Salle des pas perdus</td>
    </tr>
    <tr>
      <td style="text-align:left">Salle d&apos;exposition</td>
    </tr>
    <tr>
      <td style="text-align:left">Salle d&apos;orientation</td>
    </tr>
    <tr>
      <td style="text-align:left">Salon de reception</td>
    </tr>
    <tr>
      <td style="text-align:left">Archives</td>
    </tr>
    <tr>
      <td style="text-align:left">Cave</td>
    </tr>
    <tr>
      <td style="text-align:left">Cellier</td>
    </tr>
    <tr>
      <td style="text-align:left">Placard</td>
    </tr>
    <tr>
      <td style="text-align:left">Rangement</td>
    </tr>
    <tr>
      <td style="text-align:left">Reserve</td>
    </tr>
    <tr>
      <td style="text-align:left">Reserve froide</td>
    </tr>
    <tr>
      <td style="text-align:left">Douche</td>
    </tr>
    <tr>
      <td style="text-align:left">Sanitaire</td>
    </tr>
    <tr>
      <td style="text-align:left">Sanitaire commun</td>
    </tr>
    <tr>
      <td style="text-align:left">Sanitaire commun femme</td>
    </tr>
    <tr>
      <td style="text-align:left">Sanitaire commun homme</td>
    </tr>
    <tr>
      <td style="text-align:left">Sanitaire commun PMR</td>
    </tr>
    <tr>
      <td style="text-align:left">Sanitaire commun PMR femme</td>
    </tr>
    <tr>
      <td style="text-align:left">Sanitaire commun PMR homme</td>
    </tr>
    <tr>
      <td style="text-align:left">Sanitaire femme</td>
    </tr>
    <tr>
      <td style="text-align:left">Sanitaire homme</td>
    </tr>
    <tr>
      <td style="text-align:left">Sanitaire PMR</td>
    </tr>
    <tr>
      <td style="text-align:left">Sanitaire PMR femme</td>
    </tr>
    <tr>
      <td style="text-align:left">Sanitaire PMR homme</td>
    </tr>
    <tr>
      <td style="text-align:left">Vestiaire</td>
    </tr>
    <tr>
      <td style="text-align:left">Vestiaire femme</td>
    </tr>
    <tr>
      <td style="text-align:left">Vestiaire homme</td>
    </tr>
    <tr>
      <td style="text-align:left">Vestiaire PMR</td>
    </tr>
    <tr>
      <td style="text-align:left">WC</td>
    </tr>
    <tr>
      <td style="text-align:left">WC commun</td>
    </tr>
    <tr>
      <td style="text-align:left">WC commun femme</td>
    </tr>
    <tr>
      <td style="text-align:left">WC commun homme</td>
    </tr>
    <tr>
      <td style="text-align:left">WC commun PMR</td>
    </tr>
    <tr>
      <td style="text-align:left">WC commun PMR femme</td>
    </tr>
    <tr>
      <td style="text-align:left">WC commun PMR homme</td>
    </tr>
    <tr>
      <td style="text-align:left">WC femme</td>
    </tr>
    <tr>
      <td style="text-align:left">WC homme</td>
    </tr>
    <tr>
      <td style="text-align:left">WC PMR</td>
    </tr>
    <tr>
      <td style="text-align:left">WC PMR femme</td>
    </tr>
    <tr>
      <td style="text-align:left">WC PMR homme</td>
    </tr>
    <tr>
      <td style="text-align:left">Cabine essayage</td>
    </tr>
    <tr>
      <td style="text-align:left">Local commercial</td>
    </tr>
    <tr>
      <td style="text-align:left">Showroom</td>
    </tr>
    <tr>
      <td style="text-align:left">Surface de vente</td>
    </tr>
    <tr>
      <td style="text-align:left">Espace vert exterieur</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <p>Espace vert interieur</p>
        <p>
          <br />&lt;!--table
          <br />{mso-displayed-decimal-separator:&quot;\,&quot;;
          <br />mso-displayed-thousand-separator:&quot; &quot;;}
          <br />@page
          <br />{margin:.75in .7in .75in .7in;
          <br />mso-header-margin:.3in;
          <br />mso-footer-margin:.3in;}
          <br />tr
          <br />{mso-height-source:auto;}
          <br />col
          <br />{mso-width-source:auto;}
          <br />br
          <br />{mso-data-placement:same-cell;}
          <br />td
          <br />{padding-top:1px;
          <br />padding-right:1px;
          <br />padding-left:1px;
          <br />mso-ignore:padding;
          <br />color:black;
          <br />font-size:11.0pt;
          <br />font-weight:400;
          <br />font-style:normal;
          <br />text-decoration:none;
          <br />font-family:Calibri, sans-serif;
          <br />mso-font-charset:0;
          <br />mso-number-format:General;
          <br />text-align:general;
          <br />vertical-align:bottom;
          <br />border:none;
          <br />mso-background-source:auto;
          <br />mso-pattern:auto;
          <br />mso-protection:locked visible;
          <br />white-space:nowrap;
          <br />mso-rotate:0;}
          <br />.xl63
          <br />{white-space:normal;}
          <br />.xl64
          <br />{text-align:left;
          <br />vertical-align:middle;
          <br />white-space:normal;}
          <br />.xl65
          <br />{text-align:left;
          <br />white-space:normal;}
          <br />.xl66
          <br />{text-align:left;
          <br />vertical-align:top;
          <br />white-space:normal;}
          <br />.xl67
          <br />{color:windowtext;
          <br />white-space:normal;}
          <br />.xl68
          <br />{color:windowtext;
          <br />text-align:left;
          <br />vertical-align:top;
          <br />white-space:normal;}
          <br />.xl69
          <br />{color:red;
          <br />text-align:left;
          <br />vertical-align:top;
          <br />white-space:normal;}
          <br />--&gt;
          <br />
        </p>
      </td>
    </tr>
  </tbody>
</table>
{% endtab %}
{% endtabs %}

![](../../.gitbook/assets/wallpaper_fnum_black.jpg)

