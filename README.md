###### Crestia RPG ~ a discord bot

Crestia ist ein Deutschsprachiger Chatbasierter RPG Bot für Discord.

Zur Zeit befindet sich dieser in der Entwicklung.


## Features:

# RPG
- [x] &nbsp;Serverübergreifende Datenbank für die Spieler
- [x] &nbsp;Levelingsystem
- [x] &nbsp;Spielerinventar
- [x] &nbsp;Itemshop
- [ ] &nbsp;Monster Raids
- [ ] &nbsp;Skillsystem
- [ ] &nbsp;Spieler Statsystem
- [x] &nbsp;Währungssystem
- [x] &nbsp;Gruppensystem

# Server
- [x] &nbsp;Reaction Role System
- [x] &nbsp;Custom Willkommnesnachrichten
- [x] &nbsp;Custom Bot Channel

# Bot
- [x] &nbsp;Ändern des Commandprefix


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
  </tr>
  <tr>
  <td>!inv</td>
  <td>Öffnet das Inventar</td>
    <td>!inv</td>
    <td></td>
    <td>Jeder</td>
  </tr>
  </tr>
  <tr>
  <td>!itemshop</td>
  <td>Öffnet den Itemshop</td>
    <td>!itemshop</td>
    <td></td>
    <td>Jeder</td>
  </tr>
  <tr>
  <td>!togglebotchannel</td>
  <td>Stellt ein ob der Bot nur in einem bestimmten Text Channel reagiert</td>
    <td>!togglebotchannel #channel<br/>!togglebotchannel</td>
    <td></td>
    <td>Ersteller</td>
  </tr>
  <tr>
  <td>!resetsettings</td>
  <td>Setzt die Einstellungen auf Standart zurück</td>
    <td>!resetsettings</td>
    <td></td>
    <td>Ersteller</td>
  </tr>
  <tr>
  <td>!rrnew</td>
  <td>Erstellt eine neue Reaction Role Liste</td>
    <td>!rrnew Name</td>
    <td></td>
    <td>Administrator</td>
  </tr>
  <tr>
  <td>!rrroleadd</td>
  <td>Fügt eine Rolle zu einer Reaction Role Liste hinzu</td>
    <td>!rrroleadd Listenname Rollenname</td>
    <td></td>
    <td>Administrator</td>
  </tr>
  <tr>
  <td>!rrroleremove</td>
  <td>Entfernt eine Rolle aus einer Reaction Role Liste</td>
    <td>!rrroleremove Listenname Rollenname</td>
    <td></td>
    <td>Administrator</td>
  </tr>
  <tr>
  <td>!rrset</td>
  <td>Setzt eine Reaction Role Liste in den Channel wo der Command ausgeführt wurde</td>
    <td>!rrset Listenname</td>
    <td></td>
    <td>Administrator</td>
  </tr>
</table>
