# Ohmestead — hulp en privacy

Ohmestead is een Nederlandstalige iPhone-app voor je eigen Ohmestead-energieserver. Bekijk energiemetingen, volg stroomrichtingen in de topologie en beheer apparaten en energie-instellingen.

## Support

[**Stel een supportvraag**](https://github.com/daanhermans-jpg/ohmestead-support/issues/new)

Je hebt een gratis GitHub-account nodig om een vraag te plaatsen. Vragen en antwoorden zijn openbaar. Vermeld je appversie, iOS-versie, wat je probeerde en de foutmelding. Deel geen wachtwoorden, sleutels, privé-serveradressen, persoonlijke gegevens of onbewerkte logbestanden. Maak zulke gegevens onleesbaar in screenshots.

### Aan de slag

1. Installeer Ohmestead op je iPhone.
2. Kies **Probeer de demonstratie** om zonder account, hardware of netwerk de functies te bekijken. De metingen zijn fictief. Demo-wijzigingen beïnvloeden geen echte installatie.
3. Voor live gebruik vul je het HTTPS-adres van je eigen compatibele Ohmestead-server en je bestaande gebruikersnaam en wachtwoord in.
4. Zorg dat je iPhone de server kan bereiken. Afhankelijk van je eigen netwerk kan een VPN nodig zijn.

De app is gratis. Voor live gebruik zijn een eigen server en geschikte apparaten nodig. Er is geen centraal Ohmestead-account en geen accountregistratie in de iOS-app.

### Geen verbinding of ontbrekende waarden?

Controleer of je server actief is, het HTTPS-adres klopt en het certificaat geldig is. Controleer je netwerk of VPN en probeer de server in Safari te openen. De beschikbare metingen hangen af van de apparaten en serverconfiguratie. Ontbrekende metingen betekenen niet automatisch dat het verbruik nul is.

### Apparaten en instellingen wijzigen

Wijzigingen in de live modus worden naar je eigen server gestuurd en kunnen je installatie beïnvloeden. Controleer daarom de gekozen apparaten en waarden voordat je opslaat. De demonstratie slaat wijzigingen alleen tijdelijk op.

## Privacybeleid

**Van toepassing op:** de native Ohmestead iPhone-app. **Laatst bijgewerkt:** 5 November 2026. **Ontwikkelaar:** Daan Hermans.

### Gegevens in de app

De app stuurt geen gebruiksstatistieken, advertentiesignalen of energiemetingen naar een centrale dienst van de ontwikkelaar. Er zijn geen advertentie- of analyse-SDK's en de app gebruikt geen tracking.

Voor live gebruik communiceert de app via HTTPS met de server die je zelf instelt. Je inloggegevens gaan naar die server om je aan te melden. De app leest daar beschikbare energiemetingen, apparaten en instellingen. Wanneer je apparaten of instellingen wijzigt, stuurt de app deze wijzigingen naar die server. Door jou ingevoerde apparaatgegevens kunnen ook apparaatwachtwoorden bevatten.

The server address is stored locally on the iPhone. The login password is never retained. From version 1.1.0, only the existing, expiring server session is kept in the iPhone Keychain, accessible while unlocked and limited to this device and the exact HTTPS server address and port. It is not synchronized through iCloud or sent to the developer. Temporary network failures retain the session; sign-out and rejected authentication remove it. The server determines its validity. Retrieved installation data stays in app memory. The built-in demonstration uses fictional data without contacting a server.

### Je eigen server en andere diensten

De eigenaar of beheerder van je gekozen server bepaalt welke gegevens die server bewaart, hoe lang deze worden bewaard en welke externe apparaatdiensten ermee verbonden zijn. Neem voor inzage, verwijdering of vragen over servergegevens contact op met die beheerder. Een door jou gebruikte VPN of andere netwerkdienst heeft een eigen privacybeleid.

### Verwijderen en vragen

Use “Afmelden / andere server” in Settings to remove the saved session before uninstalling the app. Keychain items can survive an app reinstall; uninstalling alone must not be relied on to end a server session. Removing the app deletes its local preferences, but does not delete data on your server. Voor vragen over de app of dit privacybeleid kun je een [supportvraag](https://github.com/daanhermans-jpg/ohmestead-support/issues/new) plaatsen. Plaats hierin geen persoonlijke of vertrouwelijke gegevens.

### Deze supportpagina

Deze pagina en de openbare supportvragen worden gehost door GitHub. GitHub verwerkt websitebezoeken en accountgegevens volgens het [privacybeleid van GitHub](https://docs.github.com/site-policy/privacy-policies/github-privacy-statement). Informatie die je vrijwillig in een supportvraag plaatst, is openbaar en wordt gebruikt om je vraag te beantwoorden. Je kunt je vraag achteraf aanpassen of sluiten; openbare kopieën kunnen blijven bestaan.

### Wijzigingen

Bij wijzigingen in het gedrag van de app wordt dit beleid bijgewerkt. De datum hierboven geeft de laatste wijziging aan.
