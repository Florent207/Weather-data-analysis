# Weather-data-analysis

<h1 style="background-color:darkblue;color:white;padding:10px;text-align:left;font-size:45px;border-bottom:5px solid white;">
EVOLUTION DES CYCLES METEROLOGIQUES<br>
</h1>
<p style="font-size:15px">Florent Beausseron</p>
<p style="font-size:15px">Juin 2022</p><br>

<h1 style="color:#0b3fcd;font-size:33px">1. Résumé</h1>
<h2 style="color:#2c91ff;font-size:25px">1.1 But du projet</h2>

Mon projet consiste à évaluer l'évolution des températures et des précipitations sur le canton de Neuchâtel depuis 1900 jusqu'à nos jours.
Ceci afin de mettre en image la vitesse de ces évolutions, leurs tendances (négatives ou positives) et de repérer les répétitions des éventuels cycles chauds/froids pour savoir si ces derniers sont réguliers ou non.

<h2 style="color:#2c91ff;font-size:25px">1.2 Aperçu des résultats</h2>
J'ai travaillé sur deux données principales, les températures et les précipitations moyennes enregistrées dans les stations de Chaumont, de La Chaux-de-Fonds et de Neuchâtel. Avec ces bases, nous avons pu générer des moyennes des températures sur tout le canton, par station et par cycle été / hiver.
Pour plus de détails et de compréhension des résultats obtenus, j'ai aussi isolé ces évolutions par cycle générationnel (20 ans) afin de repérer les hausses significatives.<br>
<br>
> Températures moyennes du canton de Neuchâtel :

![image.png](img/1_tempNE.png)

<h1 style="color:#0b3fcd;font-size:33px">2. Les données</h1>
<h2 style="color:#2c91ff;font-size:25px">2.1 Récupération des données</h2>

Les données ont été récupérées sous format .txt depuis le site de la confédération dédié. Voici le lien : https://www.meteosuisse.admin.ch/home/climat/le-climat-suisse-en-detail/donnees-homogeneisees-depuis-1864.html
