# mein git lernjournal
## Grundlagen
- Ein Commit speichert drei Dinge. Was sind sie?
-Wer:wer hat die Änderung gemacht?
-was:was wurde geändert
-warum:warum wurde es geändert

- Was ist der "Stamm" (trunk) des Baumes in der Terminologie der Versionskontrolle?
Der Stamm ist der Hauptbranch eines Projekts,der die stabile Version enthält
Antwort auf zweite Frage ergänzt
## Architektur

- _Frage:_ Was ist in einem zentralisierten System (wie einer Bibliothek) der "Single Point of Failure"?
in einem zentralisiererten Sytem ist der zentrale Server der "single Point of Failure".Wenn er ausfällt,können alle ncht mehr arbeiten.
- _Frage:_ Wo wird in einem verteilten System (wie Git) die vollständige Projekthistorie gespeichert?
In einem verteileten System ist die vollständige Projekthistorie in jedem lokalen Repository gespeichert.

## Der Workflow
- _Frage:_ Was entspricht in der "Supermarkt-Analogie" dem **Einkaufswagen**?
Der "Einkaufswagen" entspricht der Staging Area (Index),in die Änderungen für den nächsten commit gelegt werden.
- _Frage:_ Welcher Befehl wird verwendet, um einen Schnappschuss des Einkaufswagens zu machen?
Der Befehl git commit erstellt einen Schnappschuss des Einkaufswagens.