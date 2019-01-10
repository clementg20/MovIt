---
layout: default
category: access
title: Accès à l'interface Plex 
id: 2
---

**Plex** est une interface qui permet de lire les films présents sur le serveur. Plex gère également les sous-titres et permet d'adapter la qualité du film en fonction de l'écran. L'application Plex est aussi disponible sur Play Store, App Store, Microsoft Store.
<br/>
L'utilisation de Plex est très simple, une fois identifié il suffit de cliquer sur "**Films**" à gauche pour voir les films disponibles. Laissez-vous guider :)
<br/>

<br/>
Afin d'accéder à l'interface Plex, le compte associé au serveur est nécessaire. Voici les identifiants du compte:
<br/>
- nom d'utilisateur: <b>MovIt</b>
- mot de passe: <b>movieswow</b>
<br/>
<br/>
<br/>
<p align="center">
<input type="button" class="btn btn-primary btn-lg" value="Ouvrir PLEX" onclick=" relocate_home()">
</p>

<script>
function relocate_home()
{
	var win = window.open("https://app.plex.tv", '_blank');
	win.focus();
} 
</script>