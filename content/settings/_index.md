---
title: "Wichtige Einstellungen"
date: 2020-07-03T13:22:13+02:00
draft: false
chapter: true
weight: 10
---

# Einstellungen nach dem ersten Login

## Aktivieren der Desktop-Benachrichtigungen

Ähnlich zu der Einrichtung der Schlüsselsicherung werden Sie nach der Anmeldung irgendwann dazu aufgefordert die Desktop-Benachrichtigungen zu aktivieren.
Dies kann später (unter Einstellungen -> Benachrichtigungen) geändert oder rückgängig gemacht werden. Insbesondere können die Benachrichtigungen für einzelne "Gespräche" (Räume) individuell eingestellt werden.

![Screenshot der Abfrage, Pushbenarchitigungen zu aktivieren](/images/06_Enable-Notifications_de.png)

## Öffnen der Einstellungen

Das **Einstellungsmenü** kann geöffnet werden indem auf das runde Anzeigebild oben Links und anschließend auf die Zeile "Alle Einstellungen" geklickt wird.

![Auswahl des Menüpunkts Einstellungen in dem Nutzer:innenmenü](/images/06_Settings_de.png)

## Anzeigename und Profilbild

In den Einstellungen können Sie im Reiter **Konto** bei Bedarf Ihren Anzeigenamen ändern (Standardmäßig "Nachname, Vorname") und ein Profilbild hochladen:
![Markierung des Feldes Anzeigenamen und des Profilbilds in den Einstellungen](/images/06_Settings-Names_de.png)

Das E-Mail-Adressfeld sollte nicht ausgefüllt werden, da über Ihren TUB-Login eine E-Mail-Adresse hinterlegt ist. Theoretisch können hier weitere Adressen hinzugefügt werden, beispielsweise um Benachrichtigungen über verpasste Nachrichten an eine weitere E-Mail-Adresse senden zu lassen.

## Sitzungen

Im Reiter **Sitzungen** können neue Geräte (per QR-Code) verknüpft werden, alle angemeldeten Sitzungen eingesehen, verifiziert und ausgeloggt werden.

Um nicht mehr benutzte Sitzungen zu entfernen, Markieren Sie die Sitzung mit einem Klick auf die quadratische Box und wählen Sie "Abmelden" aus.

![Übersicht der angemeldeten Sitzungen](/images/09_Delete-Sessions_de.png)

Die Geräte-Namen geben Ihnen auch Übersicht beim gegenseitigen Schlüsselvergleich zwischen Ihren Geräten.

Die hier vergebbaren öffentlichen Namen (durch Mausklick auf diese) Ihrer Geräte können auch von Gesprächspartner:innen eingesehen werden. Dies hilft, wenn diese einen Vergleich der kryptografischen Schlüssel Ihrer Geräte (bspw. Laptop + Handy) durchzuführen möchten und so leicht die Gerätenamen identifizieren können.

Die vielen kryptografischen Schlüssel werden auf dem jeweiligen Gerät gespeichert. Sollte dies bspw. ein Tab in einem Browser sein, besteht die Gefahr, dass dieser Tab einmal unbeabsichtigt geschlossen wird. Dann sind alle verschlüsselten Inhalte nicht mehr lesbar. Damit dies nicht geschieht, wird eine Schlüsselsicherung auf dem Heimserver der TU Berlin angeboten, auf der (mit einer Passphrase geschützt) alle kryptografischen Schlüssel verschlüsselt abgelegt sind. Es wird dringend empfohlen, diese Schlüsselsicherung zu nutzen!

## Erscheinungsbild

Auf dieser Seite kann das Design Thema aus Hell, Dunkel, Hochkontrast gewählt werden, oder an das Systemdesign angepasst werden. Auch können weitere Personalisierungen wie Nachrichtenlayou, Schriftgröße und Bildgröße im Nachrichtenverlauf vorgenommen werden.

## Benachrichtigungen

Im Reiter **Benachrichtigungen** können Sie E-Mail-Benachrichtigungen (um über verpasste Nachrichten informiert zu werden) sowie akustische Benachrichtigungen aktivieren und diese granular für einzelne "Gespräche" (Räume) einstellen. Mehr dazu auf der Seite [Benachrichtigungen]({{< relref "notifications" >}}).

![Screenshot der Benarchrichtigungeneinstellungen mit einer Makierung der ausgeschalteten E-Mail benachrichtigungen](/images/06_Settings-EMailNotify_de.png)

## Allgemeine Einstellungen

Im Reiter **Präferenzen** finden Sie eine Vielzahl verschiedener Optionen, um den Matrix Client an Ihre Bedürfnisse anzupassen. So kann die Sprache eingestellt, die Nachrichteneingabe angepasst werden, Lesebestätigungen von Nachrichten deaktiviert werden und noch vieles mehr.

## Tastatur 

Im Reiter **Tastatur** können Sie sich sämtliche Tastenkombinationen anzeigen lassen, die das Benutzen der Anwendung effizienter und einfacher gestalten können.

## Seitenleiste

Unter **Seitenleiste** können Sie auswählen, welche Spaces in der Seitenleiste angezeigt werden sollen. 

## Anrufe

Im Reiter **Anrufe** können Sie den Matrix-Client Element berechtigen Ihre Mediengeräte (Kamera + Mikrofon) zu nutzen sowie Sprach-/Videoanrufe mittels direkter Peer-to-Peer-Verbindungen erlauben:

![Screenshot des Einstellungsmenüs Sprache und Video](/images/06_Settings-Media_de.png)

Außerdem können erweiterte Einstellungen für Video und Sprachverarbeitung angepasst werden, sowie die Ein- und Ausgabegeräte für Sprach-/Videoanrufe ausgewählt werden.

Erfreulicherweise starten 1:1 Gespräche standardmäßig Ende-zu-Ende-verschlüsselt. Um dieser Verschlüsselung wirklich mit gutem Gefühl zu vertrauen, können Nutzer:innen den Schlüsselvergleich mit Gesprächspartner:innen durchführen. Damit dies dann auch für alle Geräte dieser Gesprächspartner:innen gilt, müssen Matrix-Nutzenden ihrerseits wiederum die Schlüssel all Ihrer Geräte untereinander verifizieren (Fachbegriff: Cross-Signing). Unter Beachtung der nachfolgenden Hinweise kann dies alles sehr bequem geschehen.

## Sicherheit

Im Reiter **Sicherheit** können Sie den Integrationsmanager (de-)aktivieren, Nachrichten suche verwalten und einen Identitätsserver festlegen. Der Integrationsmanager ist zwingend Nötig um [Erweiterungen]({{< relref "integrations" >}}) wie Jitsi und Etherpad benutzen zu können, weshalb empfohlen wir diesen aktiviert zu lassen. Die TU Berlin hat aktuell keinen eigenen Identitätsserver, weshalb auch hier empfohlen wird, die Standardeinstellung `https://vector.im` stehen zu lassen. Um diesen Identitätsserver zu verwenden müssen die Nutzungsbedingungen und Datenschutzrichtlinien akzeptiert werden. Diese sollten aufmerksam durchgelesen werden bevor sie akzeptiert werden.

Außerdem finden Sie hier Nutzer, die von Ihnen blockiert wurden.

## Verschlüsselung

Unter **Verschlüsselung** finden Sie alle informationen und Einstellungen zur [Schlüsselspeicherung]({{< relref "first-steps/#einrichtung-der-schlüsselsicherung" >}}). Sollten Sie nach der ersten Anmeldung nicht automatisch dazu aufgefordert worden sein die Schlüsselsicherung einzurichten, empfiehlt es sich die Schlüsselsicherung jetzt einzurichten.
