###### Crestia RPG ~ a discord bot

Crestia ist ein Deutschsprachiger Chatbasierter RPG Bot für Discord.

Zur Zeit befindet sich dieser in der Entwicklung.


## Features:

# RPG
- [x] &nbsp;Serverübergreifende Datenbank für die Spieler
- [x] &nbsp;Levelingsystem
- [ ] &nbsp;Spielerinventar
- [ ] &nbsp;Itemshop
- [ ] &nbsp;Monster Raids
- [ ] &nbsp;Skillsystem
- [ ] &nbsp;Spieler Statsystem
- [x] &nbsp;Währungssystem
- ...mehr kommt noch

# Server
- [x] &nbsp;Reaction Role System
- [x] &nbsp;Custom Willkommnesnachrichten
- ...mehr kommt noch

# Bot
- [x] &nbsp;Ändern des Commandprefix


Dies sind die momentanen Grundfeatures die zum jetzigen Zeitpunkt (03.08.2020) enthalten sind.

## Commands:
Bitte beachte das es sich hier um den Standartprefix (**!**) für Commands vom Bot handelt welcher Optional gewechselt werden kann.<br/>
"<" und ">" sind nur Platzhalter um einen Parameter eines Commands zu zeigen. Diese werden im Command nicht genutzt (siehe Benutzung).<br/>
Die Parameter bei "Parameter" sind Optional!<br/><br/>

<table>
  <tr>
  <th>
    Command & Alias
  </th>
  <th>
    Beschreibung
    </th>
    <th>
    Benutzung
    </th>
    <th>
    Parameter
    </th>
    <th>
    Berechtigung
    </th>
  </tr>
  <tr>
  <td>!play</td>
  <td>Erstellt einen Account/Charakter für den Nutzer</td>
    <td>!play</td>
    <td></td>
    <td>Jeder</td>
  </tr>
  <tr>
  <td>!profile <br/>!p</td>
  <td>Zeigt die eigene Statistik oder die von anderen</td>
    <td>!profile <br/>!profile @user</td>
    <td></td>
    <td>Jeder</td>
  </tr>
  <tr>
  <td>!give</td>
  <td>Gebe dein Gold an wen anderes weiter</td>
    <td>!give @user 500</td>
    <td></td>
    <td>Jeder</td>
  </tr>
  <tr>
  <td>!setprefix <br/>!prefix</td>
  <td>Ändert den Commandprefix</td>
    <td>!setprefix &</td>
    <td></td>
    <td>Ersteller</td>
  </tr>
  <tr>
  <td>!togglejoinmsg</td>
  <td>Schaltet Willkommensnachrichten ein/aus</td>
    <td>!togglejoinmsg</td>
    <td></td>
    <td>Ersteller</td>
  </tr>
  <tr>
  <td>!editjoinmsg</td>
  <td>Ändert die Willkommensnachricht</td>
    <td>!editjoinmsg Willkommen {1} auf {0}!</td>
    <td>{0} = Servername<br/>{1} = Username</td>
    <td>Ersteller</td>
  </tr>
</table>
