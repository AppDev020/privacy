VoiceCall Privacy Policy
Last updated: 14 October 2026

This policy explains what data the Android app VoiceCall (com.voicecall) uses and why.

What the app does

VoiceCall helps you call a person or business by voice or by tapping the icon. It searches your on-device contacts first. Searching for businesses and categories through Google Places is part of the paid subscription.

Free and subscription

Without a subscription, the app only searches your contacts. It then sends nothing to our servers, unless you turn on "Help improve speech recognition" and send a phrase yourself (see "Sending a phrase (optional)"). With a subscription, business and category searches go through our server, which is limited to a monthly number of searches per user.

In versions without business search, the app may ask whether you would want it. If you answer, the app sends your answer (yes, maybe or no), whether it was a name or a category search, and the app language to our server. It is counted per month, without an ID.

Data we process

Microphone
While the app is open and listening is on, the app listens offline (Vosk) for the wake word "VoiceCall". That audio is not sent to our servers. For commands, confirmations and choices, the app uses the speech recognition service set as the default on your device, usually Google's. That service may send the audio to its own servers and processes it under its own privacy policy. We do not receive it.

Contacts
With permission, the app reads names, phone numbers and (if present) address fields to find a match. This happens only on your device. Contact data is not sent to us or to Google Places. If you ask to call via Signal or to open a WhatsApp chat, the app also checks on your device which contacts have a Signal entry or a WhatsApp account. This is also only done on your device and is not sent to us. The app also uses the names in your contacts on your device to remove them from a phrase before you send it; the contacts themselves are not sent.

Business search (subscription)
When you use business search, the app sends the search text (for example name and place), your language and region preference and a random app ID to our server. The server forwards the search text, language and region to the Google Places API and returns the result: business name, address and phone number. We do not store the search text. Google Cloud, where our server runs (region Belgium), may keep standard technical logs. Google processes the Places request under its Maps/Places terms.

Random app ID
For the subscription, the app signs in anonymously with Firebase Authentication. This creates a random ID without name or e-mail address. The ID is removed when you uninstall the app. App Check (Play Integrity) lets Google check that the request comes from the real app on a genuine device. The same check is used when you send a phrase. Sending a phrase does not use the random app ID.

Subscription and payment
Payment runs through Google Play. We never see your card or bank details. RevenueCat processes your purchase on our behalf: it receives the random app ID and the status and dates of your subscription, so we can check whether your subscription is active.

Usage counters
Our server stores per random app ID how many business searches you did this month, and per day how many all users together did. This enforces the monthly limit and keeps costs under control. Counters are deleted after 60 days.

Sending a phrase (optional)
This is off by default. You turn it on in Settings under "Help improve speech recognition". When a command fails you can tap "Send this phrase". You then see exactly what will be sent, you can change it and add what you meant, and nothing leaves your phone until you tap Send. What is sent: the phrase as the app heard it (with your changes), what you meant if you fill it in, and the app language. Before sending, the app makes the phrase lower case, removes numbers, email addresses and links, and replaces names from your contacts with [naam]; this happens on your device. We do not receive a recording of your voice, your contacts, a user or device ID, your location or the time of day, only the date. The name replacement does not catch everything, for example a name that is not in your contacts, so please read the phrase before you send it. We use the phrases only to see which phrases the app does not understand and to improve recognition per language. For this we read them and may analyse them with software. We store one counter per day, language and phrase in Firebase (Google Cloud, region Belgium) and delete it automatically, at the latest 14 days after sending. Google Cloud may keep standard technical logs of the request, such as the IP address, for a limited time. We do not store those with the phrases. This only happens with your consent: you turn the setting on and you tap Send for each phrase. If you turn the setting off, the app sends nothing more.

Speech model (one-time)
For the offline wake word, the app may download a speech model of about 41 MB, after you agree. The download comes from https://voicecall-call.web.app (Firebase Hosting). If that fails, the app may fall back to the model maker's source (alphacephei.com). The download is checked for size and SHA-256. The model stays on your device.

Local preferences
On the device the app stores, among other things: language choice, whether listening is on, whether sending phrases is on, bar colour, and a short cache of earlier Places results (to limit repeat searches).

Calling
With permission, the app starts a call through your device's phone app. Without that permission, it only opens the dialler.

If you say "via Signal", the app asks Signal (or Molly) on your device to start a Signal call with that contact. If you say "via WhatsApp", the app opens a WhatsApp chat with the contact's phone number; WhatsApp does not allow another app to start a call, so you tap the call icon yourself. For this the app hands the contact entry (Signal) or the phone number (WhatsApp) to that app on your device. We do not receive it. Signal and WhatsApp process it under their own privacy policies.

What we don't do

No accounts with name or e-mail address
No ads
No sale of personal data
Our server does not store your contacts, spoken commands or search text, except a phrase you choose to send (see "Sending a phrase (optional)")
Third parties

Google: speech recognition (audio may be processed on Google's servers), see the Google Privacy Policy; Places searches, see the Google Maps Platform Terms; Firebase (anonymous sign-in, App Check, database for usage counters and for phrases you choose to send, hosting for the speech model), see Firebase privacy; Google Play (payment)
RevenueCat: subscription status, see the RevenueCat Privacy Policy
Alphacephei: only as a fallback source for the Vosk model file, see alphacephei.com/vosk
Signal (and Molly), WhatsApp: only when you ask to call or chat via them, see the Signal Privacy Policy and the WhatsApp Privacy Policy
Their own privacy terms apply to what they receive.

Permissions

You can revoke microphone, contacts and phone permissions in Android settings. Without the microphone, voice does not work. Without contacts, the app can search businesses only with a subscription. Without phone permission, the dialler opens instead of calling directly, and calls via Signal do not start. You can turn listening off in the app (long-press the icon or use Settings).

Retention

Data on your device stays there until you clear app data or uninstall the app. On our server we keep usage counters for 60 days. Phrases you choose to send are deleted automatically, at the latest 14 days after sending. Subscription data at RevenueCat and Google Play is kept under their own terms.

Your rights

If you live in the EU, you can ask us for access to, correction of or deletion of data about you, or object to its use. Because the app ID is random and we hold no name or e-mail address, we can only find your data if you give us that ID. A phrase you send contains no ID, so we cannot find it to correct or delete it. It disappears on its own within 14 days. You can also complain to the Dutch Data Protection Authority (Autoriteit Persoonsgegevens).

Children

The app is not directed at children under 13.

Changes

If this policy changes, we update the date at the top. The current version is on this page.

Contact

Privacy questions: appdev020@proton.me

Privacybeleid VoiceCall
Laatst bijgewerkt: 14 oktober 2026

Dit beleid beschrijft welke gegevens de Android-app VoiceCall (com.voicecall) gebruikt en waarom.

Wat de app doet

VoiceCall helpt u iemand of een bedrijf te bellen via spraak of via het icoon. De app zoekt eerst in uw contacten op het toestel. Bedrijven en categorieën zoeken via Google Places hoort bij het betaalde abonnement.

Gratis en abonnement

Zonder abonnement zoekt de app alleen in uw contacten. Er gaat dan niets naar onze servers, tenzij u "Help de spraakherkenning verbeteren" aanzet en zelf een zin opstuurt (zie "Zin opsturen (optioneel)"). Met een abonnement lopen bedrijfs- en categoriezoekopdrachten via onze server, die per gebruiker een maandelijks aantal zoekopdrachten toestaat.

In versies zonder bedrijven zoeken kan de app vragen of u dat zou willen. Als u antwoordt, stuurt de app uw antwoord (ja, misschien of nee), of het om een naam of categorie ging en de taal van de app naar onze server. Het wordt per maand geteld, zonder ID.

Gegevens die we verwerken

Microfoon
Terwijl de app open is en meeluisteren aan staat, luistert de app offline (Vosk) naar het activeerwoord "VoiceCall". Die audio gaat niet naar onze servers. Voor opdrachten, bevestigingen en keuzes gebruikt de app de spraakherkenningsdienst die op uw toestel als standaard is ingesteld, meestal die van Google. Die dienst kan de audio naar eigen servers sturen en verwerkt die volgens zijn eigen privacybeleid. Wij ontvangen die audio niet.

Contacten
Met toestemming leest de app namen, telefoonnummers en (als aanwezig) adresgegevens om een match te vinden. Dat gebeurt alleen lokaal op uw toestel. Contactgegevens worden niet naar ons of naar Google Places gestuurd. Vraagt u om te bellen via Signal of om een WhatsApp-chat te openen, dan controleert de app op uw toestel ook welke contacten een Signal-rij of een WhatsApp-account hebben. Ook dat gebeurt alleen op uw toestel en wordt niet naar ons gestuurd. De app gebruikt de namen in uw contacten ook op uw toestel om ze uit een zin te halen voordat u die opstuurt; de contacten zelf worden niet verstuurd.

Bedrijf zoeken (abonnement)
Als u een bedrijf zoekt, stuurt de app de zoektekst (bijvoorbeeld naam en plaats), uw taal- en landvoorkeur en een willekeurig app-ID naar onze server. De server stuurt de zoektekst, taal en land door naar de Google Places API en geeft het resultaat terug: bedrijfsnaam, adres en telefoonnummer. Wij bewaren de zoektekst niet. Google Cloud, waar onze server draait (regio België), kan standaard technische logs bewaren. Google verwerkt de Places-aanvraag volgens de voorwaarden voor Maps/Places.

Willekeurig app-ID
Voor het abonnement meldt de app zich anoniem aan bij Firebase Authentication. Dat levert een willekeurig ID op, zonder naam of e-mailadres. Het ID verdwijnt als u de app verwijdert. App Check (Play Integrity) laat Google controleren of de aanvraag van de echte app op een echt toestel komt. Dezelfde controle wordt gebruikt als u een zin opstuurt. Een zin opsturen gebruikt het willekeurige app-ID niet.

Abonnement en betaling
De betaling loopt via Google Play. Uw kaart- of bankgegevens zien wij nooit. RevenueCat verwerkt uw aankoop namens ons: het ontvangt het willekeurige app-ID en de status en data van uw abonnement, zodat wij kunnen nagaan of uw abonnement actief is.

Tellers voor gebruik
Onze server bewaart per willekeurig app-ID hoeveel bedrijfszoekopdrachten u deze maand deed, en per dag hoeveel alle gebruikers samen deden. Zo handhaven we de maandlimiet en houden we de kosten in de hand. Tellers worden na 60 dagen verwijderd.

Zin opsturen (optioneel)
Dit staat standaard uit. U zet het aan in Instellingen, onder "Help de spraakherkenning verbeteren". Als een opdracht niet lukt, kunt u op "Stuur deze zin op" tikken. U ziet dan precies wat er verstuurd wordt, u kunt het aanpassen en erbij zetten wat u bedoelde, en er gaat niets van uw toestel voordat u op Versturen tikt. Verstuurd wordt: de zin zoals de app die verstond (met uw aanpassingen), wat u bedoelde als u dat invult, en de taal van de app. Voor het versturen maakt de app de zin in kleine letters, haalt nummers, e-mailadressen en links weg en vervangt namen uit uw contacten door [naam]; dat gebeurt op uw toestel. Wij ontvangen geen opname van uw stem, geen contacten, geen gebruikers- of toestel-id, geen locatie en geen tijdstip, alleen de dag. De naamvervanging vangt niet alles, bijvoorbeeld een naam die niet in uw contacten staat. Lees de zin dus na voordat u verstuurt. We gebruiken de zinnen alleen om te zien welke zinnen de app niet begrijpt en om de herkenning per taal te verbeteren. Daarvoor lezen we ze en kunnen we ze met software analyseren. We bewaren per dag, taal en zin één teller in Firebase (Google Cloud, regio België) en verwijderen die automatisch, uiterlijk 14 dagen na het versturen. Google Cloud kan standaard technische logs van het verzoek bewaren, zoals het IP-adres, voor beperkte tijd. Wij bewaren die niet bij de zinnen. Dit gebeurt alleen met uw toestemming: u zet de instelling aan en u tikt per zin op Versturen. Zet u de instelling uit, dan verstuurt de app niets meer.

Spraakmodel (eenmalig)
Voor het offline activeerwoord kan de app een spraakmodel van ongeveer 41 MB downloaden, na uw toestemming. De download komt van https://voicecall-call.web.app (Firebase Hosting). Als dat niet lukt, kan de app terugvallen op de bron van de modelmaker (alphacephei.com). De download wordt gecontroleerd op grootte en SHA-256. Het model blijft op uw toestel.

Lokaal opgeslagen voorkeuren
Op het toestel bewaart de app onder meer: taalkeuze, of meeluisteren aan staat, of zinnen opsturen aan staat, balkkleur, en een korte cache van eerdere Places-zoekresultaten (om herhaalde zoekopdrachten te beperken).

Bellen
Met toestemming start de app een gesprek via de bel-app van het toestel. Zonder die toestemming opent de app alleen de belkiezer.

Zegt u "via Signal", dan vraagt de app Signal (of Molly) op uw toestel om een Signal-gesprek met dat contact te starten. Zegt u "via WhatsApp", dan opent de app een WhatsApp-chat met het telefoonnummer van het contact; WhatsApp laat een andere app geen gesprek starten, dus op het belicoon tikt u zelf. Hiervoor geeft de app het contact (Signal) of het telefoonnummer (WhatsApp) door aan die app op uw toestel. Wij ontvangen dat niet. Signal en WhatsApp verwerken het volgens hun eigen privacybeleid.

Wat we niet doen

Geen accounts met naam of e-mailadres
Geen advertenties
Geen verkoop van persoonsgegevens
Onze server bewaart uw contacten, gesproken opdrachten of zoektekst niet, behalve een zin die u zelf opstuurt (zie "Zin opsturen (optioneel)")
Derden

Google: spraakherkenning (audio kan op de servers van Google worden verwerkt), zie het privacybeleid van Google; Places-zoekopdrachten, zie de voorwaarden van Google Maps Platform; Firebase (anoniem aanmelden, App Check, database voor de tellers en voor zinnen die u opstuurt, hosting van het spraakmodel), zie privacy bij Firebase; Google Play (betaling)
RevenueCat: abonnementsstatus, zie het privacybeleid van RevenueCat
Alphacephei: alleen als terugvalbron voor het Vosk-modelbestand, zie alphacephei.com/vosk
Signal (en Molly), WhatsApp: alleen als u vraagt om via hen te bellen of te chatten, zie het privacybeleid van Signal en het privacybeleid van WhatsApp
Hun eigen privacyvoorwaarden gelden voor wat zij ontvangen.

Toestemmingen

U kunt microfoon-, contacten- en beltoestemming intrekken via de instellingen van Android. Zonder microfoon werkt spraak niet. Zonder contacten kan de app alleen met een abonnement bedrijven zoeken. Zonder beltoestemming opent de kiezer in plaats van direct te bellen, en starten gesprekken via Signal niet. Meeluisteren kunt u in de app uitzetten (lang indrukken op het icoon of via Instellingen).

Bewaartermijn

Wat op uw toestel staat, blijft daar tot u de app-gegevens wist of de app verwijdert. Op onze server bewaren we de tellers 60 dagen. Zinnen die u opstuurt worden automatisch verwijderd, uiterlijk 14 dagen na het versturen. Abonnementsgegevens bij RevenueCat en Google Play worden bewaard volgens hun eigen voorwaarden.

Uw rechten

Woont u in de EU, dan kunt u ons vragen om inzage in, correctie of verwijdering van gegevens over u, of bezwaar maken tegen het gebruik ervan. Omdat het app-ID willekeurig is en wij geen naam of e-mailadres hebben, kunnen we uw gegevens alleen vinden als u dat ID opgeeft. Een zin die u opstuurt bevat geen ID, dus we kunnen die niet terugvinden om te corrigeren of te verwijderen. Hij verdwijnt binnen 14 dagen vanzelf. U kunt ook klagen bij de Autoriteit Persoonsgegevens.

Kinderen

De app is niet gericht op kinderen onder 13 jaar.

Wijzigingen

Als dit beleid wijzigt, passen we de datum bovenaan aan. De actuele versie staat op deze pagina.

Contact

Vragen over privacy: appdev020@proton.me
