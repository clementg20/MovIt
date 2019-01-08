---
layout: default
category: access
title: Eteindre le serveur
id: 3
---
Il est nécessaire d'économiser l'énergie! Pour cette raison, le serveur s'éteint automatiquement **1 heure** après s'être allumé. Selon la durée du film choisi, il suffit de cliquer sur l'un des boutons suivants pour retarder l'extinction du serveur:
<br/>
<br/>
<p align="center">
<a type="button" class="btn btn-primary btn-lg" onclick="Shutdown(90)"> 1 HEURES 30 MINUTES </a>
&nbsp;&nbsp;&nbsp;
<a type="button" class="btn btn-primary btn-lg" onclick="Shutdown(120)"> 2 HEURES 00 MINUTES </a>
&nbsp;&nbsp;&nbsp;
<a type="button" class="btn btn-primary btn-lg" onclick="Shutdown(180)"> 3 HEURES 00 MINUTES </a>
</p>

<script type="text/javascript">
function Shutdown(x){
    $.ajax({
        url:'http://clementg20.sytes.net/shutdown/'+x.toString(),
        type:'get',
    });
}
</script>  