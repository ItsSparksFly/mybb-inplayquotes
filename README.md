# Inplayquotes 3.0
Durch die Installation dieses Plugins können Mitglieder (die Berechtigungen können bei den Gruppeneinstellungen erteilt werden) Zitate von Inplay-Posts einsenden. Diese Zitate werden anschließend im Foren-Index zufällig ausgegeben und auf einer Übersichtsseite gesammelt.

# Funktionen
<ul>
  <li> Einsenden von Zitaten aus Foren-Beiträgen
  <li> Einstellung, aus welchen Foren zitiert werden darf, vorhanden
  <li> Markierte Passagen werden automatisch in das Einsendeformular eingetragen
  <li> Einsendung über PopUp direkt im Thread
  <li> Neue Seite misc.php?action=inplayquotes_overview, auf der alle Zitate sichtbar & filterbar sind
  <li> Darstellung eines zufälligen Zitat des Charakters im Profil
  <li> Darstellung eines zufälliegn Zitat aus dem Post über der Postbit
  <li> MyAlert an den Charakter, wenn ein Zitat eingetragen wurde
  <li> Integration mit "Charakter Folgen"-Plugin
</ul>

# Datenbankänderungen
Die Tabelle <b>inplayquotes</b> wird hinzugefügt.

# Neue Templates
<ul>
  <li>index_inplayquotes
  <li>inplayquotes_member_profile
  <li>inplayquotes_postbit
  <li>inplayquotes_postbit_js
  <li>inplayquotes_postbit_quoted
  <li>misc_inplayquotes_overview
  <li>misc_inplayquotes_overview_bit
  <li>misc_inplayquotes_overview_bit_delete
</ul>

# Template-Änderungen
<blockquote>
  {$post['inplayquotes']} // postbit, postbit_classic<br />
  ruft das Template inplayquotes_postbit auf (Button für das Eintragen von Zitaten)
  
  {$post['quoted']} // postbit, postbit_classic<br />
  ruft ein Random-Zitat aus dem Post auf
  
  {$inplayquotes} // index<br />
  ruft die Box mit einem zufällig ausgewählten Zitat auf dem Index auf
  
  {$inplayquotes_member_profile} // member_profile<br />
  ruft ein Random-Zitat im User-Profil auf
</blockquote>

# Empfohlene Plugins
<a href="https://github.com/MyBBStuff/MyAlerts">MyAlerts</a> von EuanT<br />
<a href="https://github.com/ItsSparksFly/mybb-follow">Charakteren folgen</a> von sparks fly

# Upgrade
Du bist von einer älteren Version des Plugins hier? Dann gehe bitte wiefolgt zum Update vor!

<ul>
  <li><b>Deaktiviere</b> (nicht deinstallieren!) das Plugin in der Version 2.0 (speichere dir vorher ggf. Template-Änderungen)
  <li>Überprüfe, ob alle Templates, die "inplayquotes" enthalten, gelöscht wurden
  <li>Lösche das alte Plugin vom Webspace, lade das neue hoch.
  <li><b>Aktiviere</b> das Plugin Inplayzitate (3.0)
  <li>Alle neuen Funktionen sollten aktiv sein.
</ul>

# Demo
<center>
<img src="https://snipboard.io/4WmFwY.jpg" />
<img src="https://snipboard.io/KTADOy.jpg" />
<img src="https://snipboard.io/Eihy3j.jpg" />
<img src="https://snipboard.io/n45FU7.jpg" />
