# Online, Computer etc. 
Am Besten gehst du alle Accounts in deinem Passwortmanager durch und schaust, ob dort ein Name erfasst ist und änderst ihn. 
Falls du noch keinen Passwortmanager hast, ist dies die Gelegenheit, einen einzurichten ✨. (z.B: https://github.com/bitwarden, https://github.com/keepassxreboot/keepassxc, etc.)

In diesem Dokument sind einige Services aufgelistet, bei denen es nicht ganz offensichtlich oder nicht ganz unkompliziert ist, dies zu ändern.

## Computer
**Achtung**: Einige Applikationen haben einen "Cache" in dem der alte Name durch das Umbenennen des Kontos nicht automatisch geändert wird. Deshalb kann es vorkommen, dass diese nicht mehr wie erwartet funktionieren und nur ein manuelles Löschen des "Caches" das Problem lösen kann.

Um dies zu verhindern kannst du ein Skript benutzen um alle möglichen Caches auch gleich umzubenennen. Oft hilft auch eine Neuinstallation des Programms. 

Am einfachsten und 'ungefährlichsten' bleibt jedoch die folgende Variante:
1. Neues Benutzerkonto anzulegen
1. Alle wichtigen Dateien kopieren
1. Verifizieren das alles funktioniert
1. Altes Konto löschen 

### Linux
https://askubuntu.com/questions/34074/how-do-i-change-my-username

### macOS
https://support.apple.com/en-us/HT201548

### Windows
https://www.howtogeek.com/787936/how-to-change-your-user-name-on-windows-10-or-11/

## Online
### Nextcloud
Dies ist momentan nicht auf einfache Weise möglich, siehe dazu folgendes Issue: https://github.com/nextcloud/server/issues/5488

Eine ziemlich gute Alternative ist folgendes: 
In deinem Account kannst du eine Email setzen. Fortan kannst du dich damit einloggen.
Dein Username wird nirgends in deinem Account angezeigt. Jedoch werden die CalDav, CardDav, ... URLs weiterhin deinen Usernamen referenzieren.

Alternativ erstellst du einen neuen Account und kopierst alle Daten zum anderen Account.

### Airbnb
Es ist möglich die Reviews vom Support anpassen zu lassen, jedoch ist es nur möglich den Namen mit "[GUEST]" zu ersetzen.

**Beispiel**

**Vorher**
```
¨It was a pleasure to host Name and his friend :-) We hope to see you again soon.¨
```

**Nachher**
```
¨It was a pleasure to host [GUEST] and his friend :-) We hope to see you again soon.¨
```

<details>
<summary>Begründung von Airbnb</summary>
We are able to modify your reviews so that they no longer display the incorrect pronoun. Unfortunately, we aren't able to change the pronouns from him to her. Instead in these instances, we change the pronoun to [Guest]

This format is used in the same way "[URL HIDDEN]" is used, to indicate that a review has been edited by Airbnb. This helps maintain consistency and transparency throughout the review process.
</details>

Da dies eher komisch auf zukünftige Gastgeber wirken könnte, würde ich empfehlen den Account zu löschen und einen neuen Account zu erstellen. 

### Paypal
Du kannst über dein Profil den Namen anpassen lassen durch den Upload deiner neuen ID.

**Achtung** falls du dein Konto vor deinem 18ten Geburtstag eröffnet hast, hast du ihre Nutzungsbestimmungen verletzt und dein Konto wird nach dem Upload deiner ID gesperrt. Falls dies also der Fall sein sollte, löscht du am einfachsten dein jetziges Konto und eröffnest dann ein neues Konto.
