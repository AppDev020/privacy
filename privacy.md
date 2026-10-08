# VoiceCall Privacy Policy
Last updated: 8 October 2026

This policy explains what data the Android app VoiceCall (`com.voicecall`) uses and why.

**What the app does**

VoiceCall helps you call a person or business by voice or by tapping the icon. It searches your on-device contacts first. Only if that finds nothing, or for a business/category search, it queries Google Places.

**Data we process**

**Microphone**  
While the app is open and listening is on, the app listens offline (Vosk) for the wake word “VoiceCall”. That audio is not sent to our servers. For commands, confirmations and choices, the app uses the speech recognition service set as the default on your device, usually Google’s. That service may send the audio to its own servers and processes it under its own privacy policy. We do not receive it.

**Contacts**  
With permission, the app reads names, phone numbers and (if present) address fields to find a match. This happens only on your device. Contact data is not sent to us or to Google Places.

**Search text to Google Places**  
When the app searches for a business, it sends the search text (for example name and place) plus language and region preference to the Google Places API. The response may include a business name, address and phone number. Google processes that under their Maps/Places terms.

**Speech model (one-time)**  
For the offline wake word, the app may download a speech model of about 41 MB, after you agree. The download comes from https://voicecall-call.web.app (Firebase Hosting). If that fails, the app may fall back to the model maker’s source (alphacephei.com). The download is checked for size and SHA-256. The model stays on your device.

**Local preferences**  
On the device the app stores, among other things: language choice, whether listening is on, bar colour, and a short cache of earlier Places results (to limit repeat searches). There is no account and no sync to our servers.

**Calling**  
With permission, the app starts a call through your device’s phone app. Without that permission, it only opens the dialler.

**What we don't do**

- No accounts, no sign-in
- No ads
- No sale of personal data
- No backend of ours that stores your contacts or spoken commands

**Third parties**

- **Google:** on-device speech recognition; Places queries; possibly Firebase Hosting for the speech model
- **Alphacephei:** only as a fallback source for the Vosk model file

Their own privacy terms apply to what they receive.

**Permissions**

You can revoke microphone, contacts and phone permissions in Android settings. Without the microphone, voice does not work. Without contacts, the app searches via Places where possible. Without phone permission, the dialler opens instead of calling directly. You can turn listening off in the app (long-press the icon or use Settings).

**Retention**

We do not store personal data on our own servers. What is on the device stays there until you clear app data or uninstall the app.

**Children**

The app is not directed at children under 13.

**Changes**

If this policy changes, we update the date at the top. The current version is this page.

**Contact**

Privacy questions: appdev020@proton.me

---

# Privacybeleid VoiceCall
Laatst bijgewerkt: 8 oktober 2026

Dit beleid beschrijft welke gegevens de Android-app VoiceCall (`com.voicecall`) gebruikt en waarom.

**Wat de app doet**

VoiceCall helpt u iemand of een bedrijf te bellen via spraak of via het icoon. De app zoekt eerst in uw contacten op het toestel. Alleen als dat niets oplevert, of bij een bedrijf-/categoriezoekopdracht, zoekt de app verder via Google Places.

**Gegevens die we verwerken**

**Microfoon**  
Terwijl de app open is en meeluisteren aan staat, luistert de app offline (Vosk) naar het activeerwoord “VoiceCall”. Die audio gaat niet naar onze servers. Voor opdrachten, bevestigingen en keuzes gebruikt de app de spraakherkenningsdienst die op uw toestel als standaard is ingesteld, meestal die van Google. Die dienst kan de audio naar eigen servers sturen en verwerkt die volgens zijn eigen privacybeleid. Wij ontvangen die audio niet.

**Contacten**  
Met toestemming leest de app namen, telefoonnummers en (als aanwezig) adresgegevens om een match te vinden. Dat gebeurt alleen lokaal op uw toestel. Contactgegevens worden niet naar ons of naar Google Places gestuurd.

**Zoektekst naar Google Places**  
Als de app een bedrijf zoekt, stuurt zij de zoektekst (bijvoorbeeld naam en plaats) plus taal- en landvoorkeur naar de Google Places API. Het antwoord kan een bedrijfsnaam, adres en telefoonnummer bevatten. Google verwerkt dat volgens hun voorwaarden voor Maps/Places.

**Spraakmodel (eenmalig)**  
Voor het offline activeerwoord kan de app een spraakmodel van ongeveer 41 MB downloaden, na uw toestemming. De download komt van https://voicecall-call.web.app (Firebase Hosting). Als dat niet lukt, kan de app terugvallen op de bron van de modelmaker (alphacephei.com). De download wordt gecontroleerd op grootte en SHA-256. Het model blijft op uw toestel.

**Lokaal opgeslagen voorkeuren**  
Op het toestel bewaart de app onder meer: taalkeuze, of meeluisteren aan staat, balkkleur, en een korte cache van eerdere Places-zoekresultaten (om herhaalde zoekopdrachten te beperken). Er is geen account en geen synchronisatie met onze servers.

**Bellen**  
Met toestemming start de app een gesprek via de bel-app van het toestel. Zonder die toestemming opent de app alleen de belkiezer.

**Wat we niet doen**

- Geen accounts, geen inloggen
- Geen advertenties
- Geen verkoop van persoonsgegevens
- Geen eigen backend die uw contacten of gesproken opdrachten opslaat

**Derden**

- **Google:** spraakherkenning op het toestel; Places-zoekopdrachten; mogelijk Firebase Hosting voor het spraakmodel
- **Alphacephei:** alleen als terugvalbron voor het Vosk-modelbestand

Hun eigen privacyvoorwaarden gelden voor wat zij ontvangen.

**Toestemmingen**

U kunt microfoon-, contacten- en beltoestemming intrekken via de instellingen van Android. Zonder microfoon werkt spraak niet. Zonder contacten zoekt de app (waar mogelijk) via Places. Zonder beltoestemming opent de kiezer in plaats van direct te bellen. Meeluisteren kunt u in de app uitzetten (lang indrukken op het icoon of via Instellingen).

**Bewaartermijn**

Wij bewaren geen persoonsgegevens op eigen servers. Wat op het toestel staat, blijft daar tot u de app-gegevens wist of de app verwijdert.

**Kinderen**

De app is niet gericht op kinderen onder 13 jaar.

**Wijzigingen**

Als dit beleid wijzigt, passen we de datum bovenaan aan. De actuele versie staat op deze pagina.

**Contact**

Vragen over privacy: appdev020@proton.me
