# BananaPi_HFU
Studentisches Projekt, SS17 - Thema: Router mit BananaPi R1

Ziel des Projektes ist ein System zur IT-Sicherheit zu bauen, das das Internet-Traffic mitschneidet
und archiviert. (Achtung! Beim produktiven Einsatz darf das Mitscheiden ausschließlich mit einem
schriftlichen Einverständnis der überwachten Benutzer erfolgen). Der Traffic soll getrennt auf den
4 LAN-Ports beobachtet werde. Die Teilnehmer in einem Subnetz (VLAN) sollen keine Möglichkeit
bekommen, sich mit Rechnern eines anderen Subnetzes zu verbinden. Usecases "alle haben
Internet-Zugang" und "nur dedizierte VLANs haben Internet Zugang" sollen implementiert werden.
Zur Archivierung der Daten soll auf dem Board eine NAS-Funktion implementiert werden.

Die verfügbaren Betriebssysteme sollen auf Umfang, Usability, Performance und Reliability
geprüft werden. Das Zielsystem soll mit mindestens 2 BS realisiert werden. Die mit den
getesteten BS gesammelten Erfahrungen sollen in einer übersichtlichen Dokumentation
beschrieben werden.

Das Board bietet viele Möglichkeiten zur Vertiefung der Materie. So kann z.B. eine WLAN-
Benutzerverwaltung implementiert werden - ein Vouchersystem, das für eine einstellbare Dauer
den registrierten Benutzern WLAN-Zugang ermöglicht. Eine weitere Möglichkeit wären die
Nutzung der GPIO-Pins für die Haus-Automation oder Ähnliches.
