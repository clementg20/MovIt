---
layout: default
category: access
title: Allumer le serveur 
id: 1
---

Il est possible que le serveur ne soit pas allumé. Pour allumer le serveur, rien de plus simple, il suffit de cliquer sur le bouton ci-dessous:
<br/>
<br/>
<p align="center">
<a type="button" class="btn btn-primary btn-lg" onclick="SubForm()"> ALLUMER LE SERVEUR </a>
<br/>
<i>il faut attendre une ou deux minutes avant que le serveur soit allumé</i>
</p>




<script type="text/javascript">
function SubForm (){
    $.ajax({
        url:'https://www.depicus.com/wake-on-lan/woli-ajax.php',
        type:'post',
        data:'macaddress=F0-4D-A2-25-CB-1B&ip=clementg20.sytes.net&subnet=1&port=9&secureon=',
    });
}
</script>