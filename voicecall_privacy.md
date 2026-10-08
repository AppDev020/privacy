# VoiceCall Privacy Policy
Last updated: 8 October 2026

This policy explains what data the Android app VoiceCall (`com.voicecall`) uses and why.

**What the app does**

VoiceCall helps you call a person or business by voice or by tapping the icon. It searches your on-device contacts first. Searching for businesses and categories through Google Places is part of the paid subscription.

**Free and subscription**

Without a subscription, the app only searches your contacts. It then sends nothing to our servers. With a subscription, business and category searches go through our server, which is limited to a monthly number of searches per user.

**Data we process**

**Microphone**  
While the app is open and listening is on, the app listens offline (Vosk) for the wake word "VoiceCall". That audio is not sent to our servers. For commands, confirmations and choices, the app uses the speech recognition service set as the default on your device, usually Google's. That service may send the audio to its own servers and processes it under its own privacy policy. We do not receive it.

**Contacts**  
With permission, the app reads names, phone numbers and (if present) address fields to find a match. This happens only on your device. Contact data is not sent to us or to Google Places.

**Business search (subscription)**  
When you use business search, the app sends the search text (for example name and place), your language and region preference and a random app ID to our server. The server forwards the search text, language and region to the Google Places API and returns the result: business name, address and phone number. We do not store the search text. Google Cloud, where our server runs (region Belgium), may keep standard technical logs. Google processes the Places request under its Maps/Places terms.

**Random app ID**  
For the subscription, the app signs in anonymously with Firebase Authentication. This creates a random ID without name or e-mail address. The ID is removed when you uninstall the app. App Check (Play Integrity) lets Google check that the request comes from the real app on a genuine device.

**Subscription and payment**  
Payment runs through Google Play. We never see your card or bank details. RevenueCat processes your purchase on our behalf: it receives the random app ID and the status and dates of your subscription, so we can check whether your subscription is active.

**Usage counters**  
Our server stores per random app ID how many business searches you did this month, and per day how many all users together did. This enforces the monthly limit and keeps costs under control. Counters are deleted after 12 months.

**Speech model (one-time)**  
For the offline wake word, the app may download a speech model of about 41 MB, after you agree. The download comes from https://voicecall-call.web.app (Firebase Hosting). If that fails, the app may fall back to the model maker's source (alphacephei.com). The download is checked for size and SHA-256. The model stays on your device.

**Local preferences**  
On the device the app stores, among other things: language choice, whether listening is on, bar colour, and a short cache of earlier Places results (to limit repeat searches).

**Calling**  
With permission, the app starts a call through your device's phone app. Without that permission, it only opens the dialler.

**What we don't do**

- No accounts with name or e-mail address
- No ads
- No sale of personal data
- Our server does not store your contacts, spoken commands or search text

**Third parties**

- **Google:** speech recognition (audio may be processed on Google's servers), see the [Google Privacy Policy](https://policies.google.com/privacy); Places searches, see the [Google Maps Platform Terms](https://cloud.google.com/maps-platform/terms); Firebase (anonymous sign-in, App Check, database for usage counters, hosting for the speech model), see [Firebase privacy](https://firebase.google.com/support/privacy); Google Play (payment)
- **RevenueCat:** subscription status, see the [RevenueCat Privacy Policy](https://www.revenuecat.com/privacy)
- **Alphacephei:** only as a fallback source for the Vosk model file, see [alphacephei.com/vosk](https://alphacephei.com/vosk/)

Their own privacy terms apply to what they receive.

**Permissions**

You can revoke microphone, contacts and phone permissions in Android settings. Without the microphone, voice does not work. Without contacts, the app can search businesses only with a subscription. Without phone permission, the dialler opens instead of calling directly. You can turn listening off in the app (long-press the icon or use Settings).

**Retention**

Data on your device stays there until you clear app data or uninstall the app. On our server we keep usage counters for 12 months. Subscription data at RevenueCat and Google Play is kept under their own terms.

**Your rights**

If you live in the EU, you can ask us for access to, correction of or deletion of data about you, or object to its use. Because the app ID is random and we hold no name or e-mail address, we can only find your data if you give us that ID. You can also complain to the Dutch Data Protection Authority (Autoriteit Persoonsgegevens).

**Children**

The app is not directed at children under 13.

**Changes**

If this policy changes, we update the date at the top. The current version is on this page.

**Contact**

Privacy questions: appdev020@proton.me

-------------------------------------------------------------------------------------------------------------------------------------------

# Privacybeleid VoiceCall
Laatst bijgewerkt: 8 oktober 2026

Dit beleid beschrijft welke gegevens de Android-app VoiceCall (`com.voicecall`) gebruikt en waarom.

**Wat de app doet**

VoiceCall helpt u iemand of een bedrijf te bellen via spraak of via het icoon. De app zoekt eerst in uw contacten op het toestel. Bedrijven en categorieën zoeken via Google Places hoort bij het betaalde abonnement.

**Gratis en abonnement**

Zonder abonnement zoekt de app alleen in uw contacten. Er gaat dan niets naar onze servers. Met een abonnement lopen bedrijf- en categoriezoekopdrachten via onze server, die per gebruiker een maandelijks aantal zoekopdrachten toestaat.

**Gegevens die we verwerken**

**Microfoon**  
Terwijl de app open is en meeluisteren aan staat, luistert de app offline (Vosk) naar het activeerwoord "VoiceCall". Die audio gaat niet naar onze servers. Voor opdrachten, bevestigingen en keuzes gebruikt de app de spraakherkenningsdienst die op uw toestel als standaard is ingesteld, meestal die van Google. Die dienst kan de audio naar eigen servers sturen en verwerkt die volgens zijn eigen privacybeleid. Wij ontvangen die audio niet.

**Contacten**  
Met toestemming leest de app namen, telefoonnummers en (als aanwezig) adresgegevens om een match te vinden. Dat gebeurt alleen lokaal op uw toestel. Contactgegevens worden niet naar ons of naar Google Places gestuurd.

**Bedrijf zoeken (abonnement)**  
Als u een bedrijf zoekt, stuurt de app de zoektekst (bijvoorbeeld naam en plaats), uw taal- en landvoorkeur en een willekeurig app-ID naar onze server. De server stuurt de zoektekst, taal en land door naar de Google Places API en geeft het resultaat terug: bedrijfsnaam, adres en telefoonnummer. Wij bewaren de zoektekst niet. Google Cloud, waar onze server draait (regio België), kan standaard technische logs bewaren. Google verwerkt de Places-aanvraag volgens de voorwaarden voor Maps/Places.

**Willekeurig app-ID**  
Voor het abonnement meldt de app zich anoniem aan bij Firebase Authentication. Dat levert een willekeurig ID op, zonder naam of e-mailadres. Het ID verdwijnt als u de app verwijdert. App Check (Play Integrity) laat Google controleren of de aanvraag van de echte app op een echt toestel komt.

**Abonnement en betaling**  
De betaling loopt via Google Play. Uw kaart- of bankgegevens zien wij nooit. RevenueCat verwerkt uw aankoop namens ons: het ontvangt het willekeurige app-ID en de status en data van uw abonnement, zodat wij kunnen nagaan of uw abonnement actief is.

**Gebruikstellers**  
Onze server bewaart per willekeurig app-ID hoeveel bedrijfzoekopdrachten u deze maand deed, en per dag hoeveel alle gebruikers samen deden. Zo handhaven we de maandlimiet en houden we de kosten in de hand. Tellers worden na 12 maanden verwijderd.

**Spraakmodel (eenmalig)**  
Voor het offline activeerwoord kan de app een spraakmodel van ongeveer 41 MB downloaden, na uw toestemming. De download komt van https://voicecall-call.web.app (Firebase Hosting). Als dat niet lukt, kan de app terugvallen op de bron van de modelmaker (alphacephei.com). De download wordt gecontroleerd op grootte en SHA-256. Het model blijft op uw toestel.

**Lokaal opgeslagen voorkeuren**  
Op het toestel bewaart de app onder meer: taalkeuze, of meeluisteren aan staat, balkkleur, en een korte cache van eerdere Places-zoekresultaten (om herhaalde zoekopdrachten te beperken).

**Bellen**  
Met toestemming start de app een gesprek via de bel-app van het toestel. Zonder die toestemming opent de app alleen de belkiezer.

**Wat we niet doen**

- Geen accounts met naam of e-mailadres
- Geen advertenties
- Geen verkoop van persoonsgegevens
- Onze server bewaart uw contacten, gesproken opdrachten of zoektekst niet

**Derden**

- **Google:** spraakherkenning (audio kan op de servers van Google worden verwerkt), zie het [privacybeleid van Google](https://policies.google.com/privacy); Places-zoekopdrachten, zie de [voorwaarden van Google Maps Platform](https://cloud.google.com/maps-platform/terms); Firebase (anoniem aanmelden, App Check, database voor gebruikstellers, hosting van het spraakmodel), zie [privacy bij Firebase](https://firebase.google.com/support/privacy); Google Play (betaling)
- **RevenueCat:** abonnementsstatus, zie het [privacybeleid van RevenueCat](https://www.revenuecat.com/privacy)
- **Alphacephei:** alleen als terugvalbron voor het Vosk-modelbestand, zie [alphacephei.com/vosk](https://alphacephei.com/vosk/)

Hun eigen privacyvoorwaarden gelden voor wat zij ontvangen.

**Toestemmingen**

U kunt microfoon-, contacten- en beltoestemming intrekken via de instellingen van Android. Zonder microfoon werkt spraak niet. Zonder contacten kan de app alleen met een abonnement bedrijven zoeken. Zonder beltoestemming opent de kiezer in plaats van direct te bellen. Meeluisteren kunt u in de app uitzetten (lang indrukken op het icoon of via Instellingen).

**Bewaartermijn**

Wat op uw toestel staat, blijft daar tot u de app-gegevens wist of de app verwijdert. Op onze server bewaren we gebruikstellers 12 maanden. Abonnementsgegevens bij RevenueCat en Google Play worden bewaard volgens hun eigen voorwaarden.

**Uw rechten**

Woont u in de EU, dan kunt u ons vragen om inzage in, correctie of verwijdering van gegevens over u, of bezwaar maken tegen het gebruik ervan. Omdat het app-ID willekeurig is en wij geen naam of e-mailadres hebben, kunnen we uw gegevens alleen vinden als u dat ID opgeeft. U kunt ook klagen bij de Autoriteit Persoonsgegevens.

**Kinderen**

De app is niet gericht op kinderen onder 13 jaar.

**Wijzigingen**

Als dit beleid wijzigt, passen we de datum bovenaan aan. De actuele versie staat op deze pagina.

**Contact**

Vragen over privacy: appdev020@proton.me

