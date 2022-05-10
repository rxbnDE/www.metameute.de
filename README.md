# MetaMeute Webseite

## Inhalte auf der Website erstellen

Jedes Mitglied der MetaMeute ist grundsätzlich aufgerufen Inhalte auf der Website zu schaffen, zu pflegen und zu verbessern. Wer sich unsicher ist kann diejenigen, die es bereits aktiv betreiben fragen. Einen formellen Freigabeprozess gibt es nicht. Benötigt wird bloß ein Zugang zum Git-Repository der Webseite.

Der Master-Branch wird automatisch gebaut und deployed.

## Auf deinem Rechner an der Website arbeiten

Wenn du an der Webseite arbeitest, solltest du sie lokal testen. Dafür musst du zuerst den Inhalt dieses git-repositories auf deinen Rechner klonen.

Wenn du unsicher bist, wie du mit git arbeitest, gibt es dazu verschiedene Ressourcen, am besten einfach mal in deiner Suchmaschine suchen.

### Website lokal starten

Die Website wird mit [Hugo][hugo] betrieben, das muss man also erst mal installieren. Das Tutorial dazu findet man [hier][hugo_install].

Der folgende Befehl sollte ausreichen, um die Webseite zu kompilieren und zu starten. Weitere Informationen werden dann angezeigt.
```sh
hugo server
```

## Einen Blogpost schreiben

Worauf muss man achten, wenn man einen neuen Blogpost für die MetaMeute Webseite verfassen möchte?

Eine detaillierte Anleitung zum Anlegen eines Posts findest du [hier][createPost].

## Bilder und Galerien

Worauf muss man achten, wenn man neue Bilder in die MetaMeute Webseite einfügen möchte?

Eine detaillierte Anleitung findest du [hier][addImage].

## Projekte veröffentlichen

Du möchtest dein neues (unvollständiges) Projekt veröffentlichen, ein Status-Update geben oder sogar einen Zeitplan setzen?

Dann findest du eine detaillierte Anleitung dazu [hier][addProject].

## Werkstatt und Werkzeug

Auf der Webseite gibt es eine Auflistung von Werkzeugen über welche wir verfügen. Auch diese wird über dieses Repository erstellt.

Eine detaillierte Anleitung findest du [hier][modifyWorkshop].

## Fork der Chaotikum Webseite

Diese Webseite stellt einen strukturellen Fork der [Chaotikum-Webseite][chaotikum_git_web] dar.

Über die enge Zusammenarbeit mit dem [Chaotikum][chaotikum] sind wir sehr dankbar.

[//]: # (Interne)
[createPost]: ./wiki/createPost.md
[addImage]: ./wiki/addImage.md
[addProject]: ./wiki/addProject.md
[addProject]: ./wiki/modifyWorkshop.md

[//]: # (Externe Verweise)
[chaotikum]: https://www.chaotikum.org
[chaotikum_git_web]: https://git.chaotikum.org/chaotikum/website
[hugo]: https://gohugo.io/
[hugo_install]: https://gohugo.io/getting-started/quick-start/
