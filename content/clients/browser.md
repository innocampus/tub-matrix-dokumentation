---
title: "Element Web (Browser)"
date: 2020-07-15T16:46:07+02:00
draft: false
chapter: true
weight: 5
---

# Element Web

Am einfachsten kann Matrix durch die vorkonfigurierte Element-Web-Anwendung unter [chat.tu-berlin.de](https://chat.tu-berlin.de) genutzt werden. Dadurch entfällt beispielsweise die Eingabe der Homeserver-URL beim Login und bestimmte Features sind aktiviert (z.B. Latex-Formatierung in Nachrichten) beziehungsweise deaktiviert.

![Startseite von Element Webclient mit Anmeldebutton](/images/01_Welcome_de.png)

Um Matrix zu nutzen ist keine Registrierung notwendig. Der Dienst kann sofort durch das Klicken auf „Anmelden“ auf der Startseite [chat.tu-berlin.de](https://chat.tu-berlin.de) genutzt werden.

![Loginfenster mit Aufforderung Benutzernamen und Passwort einzugeben](/images/02_Login1_de.png)

Anschließend müssen Benutzername und Passwort des TUB-Accounts angegeben werden. Als Nutzername muss der TUB-Login **vollständig in Kleinbuchstaben** verwendet werden (keine E-Mail-Adresse). Nach dem ersten Login folgt keine Bestätigungsmail.

{{% notice warning %}}
Sollten Sie anstatt mit der Element-Web-App sofort mit einem [Matrix Client]({{< relref "../clients" >}}) starten wollen, ist es wichtig den Heimserver `matrix.tu-berlin.de` der TU Berlin einzustellen (siehe [Erste Schritte]({{< relref "../first-steps" >}})).
{{% /notice %}}

## Browsereinstellungen

### Browserwahl

Empfehlenswert sind die Browser [Firefox](https://www.mozilla.org/de/firefox/new/), [Chromium](https://www.chromium.org/getting-involved/download-chromium), neuere Versionen von Microsoft Edge (basierend auf Chromium). Ältere oder ungeeignete Browser zeigen unter Umständen nur eine weiße Seite an.

### NoScript

Sollten Sie Browser-Plugins (z.B. Skript-Blocker) nutzen, um sich vor [Tracking](https://tu-dresden.de/tu-dresden/newsportal/news/datenschutz-beim-website-tracking) und Schadsoftware im Browser zu schützen, beispielsweise mit dem Addon [NoScript](https://addons.mozilla.org/de/firefox/addon/noscript/). Hier sind folgende Einstellungen durchzuführen (für den Integrationsmanager, z.B. Jitsi/Etherpad)

![Einstellungen des Browserplugins NoScript mit tu-dresden.de und vector.im als vertrauenswürdige Skriptquellen ausgewählt](/images/10_Sicherheit2_de.png)

### Cookies

Erlauben Sie auch Cookies von

- tu-berlin.de
- vector.im (für den Integrationsmanager)
