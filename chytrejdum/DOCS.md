# Chytrej dům

**Česky** · [English below](#english)

## Co to je

Tvůj parťák pro chytrou domácnost. Napíšeš mu obyčejnou češtinou, co chceš – třeba
„rozsviť v noci tlumeně chodbu, když se otevřou dveře“ – a on to v domácím systému nastaví: automatizace,
místnosti, ovládací panely, kamery, Zigbee i doplňky. Nemusíš znát YAML ani názvy entit.

V panelu **Chytrej dům** najdeš navíc přehled domu, zařízení, Historii změn (každá změna je zapsaná a jde
vrátit) a stav zabezpečení.

## Základní parťák a placená AI

- **Zdarma:** odpovídá vestavěný parťák domácího systému. Zvládne jednoduché ovládání („zhasni v kuchyni“),
  ale ne složitější nastavení a úlohy.
- **Placená AI:** na každý úkol si vybere vhodný model, nastaví automatizace i ovládací panely a pamatuje si,
  co máš rád. Platí se AI kredity – 1 000 měsíčně v balíčku PRO, nebo jednorázově – na
  [moje.chytrejdum.cz](https://moje.chytrejdum.cz) v sekci Balíčky.

Na Přehledu pod chatem vždy vidíš, která verze ti odpovídá.

## Co dál parťák umí (placená AI)

- **Ovládá dům hned:** „rozsviť v obýváku na 30 %“, „nastav topení na 21“, „zamkni“, „pusť scénu Večer“,
  „zavři žaluzie“ – udělá to rovnou a jde to vrátit v Historii změn. Odemknutí, vypnutí alarmu a otevření vrat
  nebo brány vždy potvrzuješ.
- **Ví, co se dělo:** „kdy se naposledy otevřely dveře?“, „kdo rozsvítil v garáži?“, „jak bylo v noci v ložnici?“
  – odpovídá z deníku a historie domácího systému. „Kolik jsme spotřebovali minulý měsíc?“, „kolik vyrobily panely
  tento týden?“ – z dlouhodobých statistik. „Kdo byl u branky?“ – z událostí kamer, se snímkem.
- **Zkontroluje celý systém:** „je všechno v pořádku?“ – aktualizace, nedostupná zařízení, slabé baterie,
  nefunkční integrace, chyby v protokolu, zálohy a místo na disku; k nalezeným potížím nabídne opravu.
- **Zná tvůj dům:** mapu místností a zařízení dostává s každou zprávou, takže odpovídá rychleji a nemusí se
  pokaždé ptát, co kde máš. Přezdívky zařízení („ta lampa“) si zapamatuje.
- **Scény:** „ulož obývák, jak je teď, jako scénu Večer“, „udělej scénu Kino: lampa na 20 %, televize zapnout“
  – scénu pak spustíš slovem, tlačítkem v domácím systému nebo z automatizace. Umí ji i upravit a smazat.
- **Denní hlášení:** každé ráno po osmé sám řekne, co dům potřebuje (nedostupné zařízení, slabá baterie,
  čekající aktualizace, stará záloha, plný disk) – oznámením v domácím systému a nové věci i na telefon.
  Vypíná se na stránce Stav domu.
- **Energie a fotovoltaika:** poradí s připojením střídače (Fronius, GoodWe, SMA, SolaX, Growatt, Huawei,
  Victron, Deye, Solinteg), nastaví spotřebič na přebytek, v levných hodinách podle spotu (OTE) nebo v nízkém
  tarifu (HDO) a řídí nabíjení baterie. Nastaví panel Energie (síť se spotovou nebo pevnou cenou, FVE, baterie,
  spotřebiče) a spočítá, kolik ušetří spotřebič v nejlevnějších hodinách.
- **Větrání a rekuperace:** Luftator a běžné rekuperace – výkon, režimy, klapky zón, větrání podle CO₂ nebo
  vlhkosti, režimy jako scény.
- **Vrata a brána na jedno relé:** z relé, které střídá otevřít–stop–zavřít, udělá pořádná vrata se stavem.
- **MQTT a vlastní zařízení:** zprávy MQTT v automatizacích. **Vlastní zařízení na ESP32** (meteostanice, CO₂,
  hlídač vody, relé, teploměr, hladina v nádrži, čtečka elektroměru a vodoměru, radar přítomnosti): hotové
  nastavení rovnou v ESPHome, obrázek zapojení a návod krok za krokem na stránce **Přidat zařízení → Vlastní
  zařízení ESP**.
- **Povaha:** vedle jména a rodu (ona, on, ono) si vybereš i povahu parťáka (milý, stručný, hravý, klidný).
- **Jedna automatizace pro víc situací:** „když se otevřou dveře a spínač byl 15 minut vypnutý, zapni…; když
  někdo spínač vypne, zhasni“ – parťák to zapíše jako jednu automatizaci s větvením, ne jako tři.
- **Ovládací panely:** dlaždice s náhledem rozložení, kdo má který panel jako výchozí a na kterých tabletech
  se používá; úpravu popíšeš slovy a parťák ji udělá přímo v panelu (přidá skupinu nahoru, odebere zařízení,
  přesune záložku) – nevytváří kopii.
- **Připomínky, které nevyšumí:** u úkolu zaškrtni „připomínat dál, dokud to neodškrtneš“ – oznámení chodí každé
  3 hodiny (8–21 h) s tlačítkem Hotovo, které úkol rovnou odškrtne.
- **Tip od AI:** na Přehledu si zapneš tipy. Jednou denně ti parťák podle tvých zařízení navrhne vylepšení,
  které by tě nenapadlo (světlo jen při pohybu, spotřebič při přebytku energie, zabezpečení). Tlačítko
  **Udělat to** návrh vloží do chatu. Stojí pár kreditů denně.
- **Výběr zařízení:** „Jaké čidlo okna koupit do 500 Kč?“ nebo „chci hlídat vodu v kotelně“ – parťák doporučí
  konkrétní druh zařízení, kolik kusů a kam je dát, ověřené modely a dnešní ceny v českých obchodech.
- **Kamery:** „kdo byl dnes u branky?“ – snímek ukáže přímo v odpovědi. Zóny (kde detekce platí, třeba jen
  osoby u branky) a místa, kde se pohyb nepočítá (strom, silnice), nakreslíš myší na snímku kamery.
- **Paměť:** v jednom rozhovoru ví všechno, co jste si napsali. **Nový rozhovor** začneš tlačítkem v hlavičce
  chatu; sám začne i po 6 hodinách bez zprávy a po restartu doplňku (kratší historie = levnější zprávy).
  Trvalá paměť (placená AI) jsou krátké poznámky o tom, co máš rád – platí ve všech rozhovorech, až 40, dokud je
  nesmažeš („zapamatuj si…“ / „zapomeň…“; vidíš a mažeš je na portálu v Nastavení → Paměť parťáka). V cloudu se
  podrobnosti o krocích parťáka drží 30 dní, celý rozhovor 90 dní od poslední zprávy.
- **Co smí parťák:** v **Zabezpečení** si po oblastech vybereš Smí sám / Jen s potvrzením / Nesmí. Hlídá to
  doplněk sám, parťák to obejít nemůže.
- **Vlastní jméno:** parťáka si pojmenuješ jako člena rodiny (Pojmenuj mě v hlavičce rozhovoru) a vybereš
  Ona / On – mluví pak ve správném rodě.
- **Potvrzení v rozhovoru:** změny, které potřebují tvůj souhlas, potvrdíš tlačítkem přímo pod odpovědí.
- **Zařízení po místnostech:** místnosti z domácího systému jako dlaždice, Nezařazené a Objeveno v okolí; po
  rozkliknutí seznam se stavem online/offline, výrobcem, hledáním, přejmenováním, přesunem i odebráním a s
  automatizacemi, které zařízení používají.
- **Hlasové ovládání (PRO):** v chatu mikrofon a čtení odpovědí nahlas.
- **Fotky v chatu:** pošli parťákovi fotku štítku, zapojení nebo chybové hlášky – poradí podle ní.
- **Úpravy automatizací:** upraví i existující automatizaci – přidá podmínku („světla jsou 15 minut zhasnutá“),
  práh teploty, tmu, scénu, termostat, žaluzie nebo oznámení na telefon.

## První spuštění

1. U doplňku zapni **Zobrazit na postranním panelu** (nebo klikni na **Otevřít webové rozhraní**).
2. V panelu **Chytrej dům → Účet** spáruj dům se svým účtem na [moje.chytrejdum.cz](https://moje.chytrejdum.cz).
3. Pro plnou funkčnost aktivuj na portálu placenou AI.

## Co doplněk smí

- číst a měnit nastavení domácího systému (automatizace, místnosti, ovládací panely, zálohy, aktualizace),
- spravovat doplňky, zálohy, aktualizace, počítač a jeho síť přes Supervisor (role admin),
- číst a měnit soubory domácího systému a ostatních doplňků (konfigurace, sdílené soubory, média, zálohy),
- používat USB a sériová zařízení (Zigbee a Thread adaptéry),
- hledat kamery a zařízení v domácí síti; kamery přidá do doplňku Frigate a napojí ho na MQTT broker domu (čidla „osoba“).

Kamery z jakékoli integrace domácího systému (ONVIF, Reolink, UniFi Protect…) doplněk vidí na stránce Kamery i bez
Frigate. Když Frigate běží jinde než jako doplněk (vlastní kontejner, jiný počítač), zadej jeho adresu na stránce Kamery
(nebo v nastavení doplňku `frigate_url`, třeba `http://192.168.1.50:5000`) – pak jde přes doplněk nastavovat i záznam a hlídání osob.

Rizikové změny (instalace doplňku, aktualizace, smazání, spínání zásuvek) se provedou až po tvém potvrzení
v Historii změn. Sám od sebe doplněk nastavení systému nemění.

## Nastavení

- **Adresa cloudu** – měň jen na pokyn podpory.

Podpora: info@chytrejdum.cz

---

## English

### What it is

Your smart home buddy. Tell it in plain words what you want – for example
"dim the hallway lights at night when the door opens" – and it sets it up in your home system: automations,
rooms, dashboards, cameras, Zigbee and add-ons. No YAML or entity names needed.

The **Chytrej dům** panel also gives you a home overview, devices, Change history (every change is recorded and
can be undone) and a security overview. The app follows your browser language (Czech or English).

### Basic buddy and paid AI

- **Free:** the built-in buddy of your home system answers. It handles simple control ("turn off the kitchen
  lights"), but not more complex setup and tasks.
- **Paid AI:** picks the right model for each task, sets up automations and dashboards, and remembers what you
  like. It's paid with AI credits – 1,000 a month with the PRO plan, or one-off credits – at
  [moje.chytrejdum.cz](https://moje.chytrejdum.cz) under Plans.

The Overview page always shows under the chat which version is answering.

### More with paid AI

- **Controls the home right away:** "turn the living room lights on at 30 %", "set the heating to 21", "lock up",
  "run the Evening scene", "close the blinds" – done at once and revertible in Change history. Unlocking,
  disarming the alarm and opening a garage or gate always need your OK.
- **Knows what happened:** "when did the door last open?", "who turned the garage light on?", "how warm was the
  bedroom at night?" – answered from the home system's logbook and history. "How much did we use last month?",
  "how much did the panels make this week?" – from long-term statistics. "Who was at the gate?" – from camera
  events, with a snapshot.
- **Checks the whole system:** "is everything OK?" – updates, unavailable devices, low batteries, failing
  integrations, errors in the log, backups and disk space; it offers to fix what it finds.
- **Scenes:** "save the living room as it is now as scene Evening", "make a scene Cinema: lamp at 20 %, TV on"
  – run it later by asking, from the home system or from an automation. It can also edit and delete scenes.
- **Daily report:** every morning after eight it tells you on its own what the home needs (an unavailable
  device, a low battery, a pending update, an old backup, a full disk) – as a notification in the home system,
  new items also on your phone. Switch it off on the Home status page.
- **Energy and photovoltaics:** helps connect the inverter (Fronius, GoodWe, SMA, SolaX, Growatt, Huawei,
  Victron, Deye, Solinteg), runs appliances on solar surplus, in cheap spot-price hours or in the low tariff,
  and manages battery charging. Sets up the Energy panel (grid with spot or fixed price, solar, battery,
  appliances) and calculates what an appliance saves in the cheapest hours.
- **Ventilation and recuperation:** Luftator and common HRV units – power, modes, zone dampers, ventilation
  by CO₂ or humidity, modes as scenes.
- **Garage door or gate on one relay:** turns a relay that cycles open–stop–close into a proper cover with a state.
- **MQTT and your own devices:** MQTT messages in automations. **DIY ESP32 devices** (weather station, CO₂, water
  leak, relay, thermometer, tank level, electricity and water meter reader, presence radar): ready configuration
  straight in ESPHome, a wiring picture and step-by-step guide under **Add device → DIY ESP devices**.
- **Personality:** besides a name and gender (she, he, it) you choose the buddy's character (kind, brief,
  playful, calm).
- **One automation for several situations:** "when the door opens and the switch was off for 15 minutes, turn
  on…; when someone turns the switch off, lights off" – written as one branching automation, not three.
- **Dashboards:** tiles with a layout preview, which dashboard is the default and on which tablets it is used;
  describe a change in words and the buddy makes it in place (adds a group on top, removes a device, moves a
  tab) – no copies.
- **Reminders that do not fade:** tick "keep reminding until ticked off" on a task – the notification repeats
  every 3 hours (8–21) with a Done button that ticks the task off.
- **Knows your home:** it gets a map of rooms and devices with every message, so it answers faster and does not
  ask where things are. It remembers device nicknames ("the lamp").
- **AI tip:** turn on tips on the Overview. Once a day the buddy suggests an improvement based on your devices
  (lights only on motion, an appliance on solar surplus, security). **Do it** puts the suggestion into the chat.
  It costs a few credits a day.
- **Choosing devices:** "Which window sensor should I buy for under 500 CZK?" or "I want to watch for water in the
  boiler room" – the buddy recommends the kind of device, how many and where, verified models and today's
  prices in Czech shops.
- **Cameras:** "who was at the gate today?" – the snapshot shows right in the reply. Draw zones (where detections
  count, e.g. only people at the gate) and areas where motion is ignored (tree, road) on the camera picture.
- **Memory:** within one conversation it knows everything you wrote. Start a **New conversation** with the button
  in the chat header; a new one also starts after 6 hours without a message and after an add-on restart (shorter
  history = cheaper messages). Long-term memory (paid AI) is short notes about what you like – used in every
  conversation, up to 40, until you delete them ("remember…" / "forget…"; see and delete them in the portal under
  Settings → Buddy memory). In the cloud the details of the buddy's steps are kept for 30 days, a whole
  conversation for 90 days after the last message.
- **What the buddy may do:** in **Security** you choose per area On its own / Only with my OK / Not allowed.
  The add-on enforces it – the buddy can't get around it.
- **Its own name:** name the buddy like a family member (Name me in the chat header) and pick She / He.
- **Confirm in the chat:** changes that need your OK are confirmed with a button right under the reply.
- **Devices by room:** rooms from the home system as tiles, Not in a room and Found nearby; open a room for a
  list with online/offline, maker, search, rename, move, remove and the automations that use each device.
- **Voice control (PRO):** a microphone and read-aloud in the chat.
- **Photos in the chat:** send the buddy a photo of a label, wiring or an error message – it advises from it.
- **Editing automations:** it changes existing automations too – adds a condition ("lights off for 15 minutes"),
  a temperature threshold, darkness, a scene, a thermostat, covers or a phone notification.

### First start

1. Turn on **Show in sidebar** for the add-on (or click **Open web UI**).
2. In **Chytrej dům → Account**, link your home to your account at [moje.chytrejdum.cz](https://moje.chytrejdum.cz).
3. For full functionality, activate paid AI in the portal.

### What the add-on can access

- read and change your home system's configuration (automations, rooms, dashboards, backups, updates),
- manage add-ons, backups, updates, the host and its network through the Supervisor (admin role),
- read and change files of the home system and other add-ons (configuration, share, media, backups),
- use USB and serial devices (Zigbee and Thread adapters),
- discover cameras and devices on your home network; it adds cameras to the Frigate add-on and connects it to
  the home MQTT broker ("person" sensors).

Cameras from any integration of the home system (ONVIF, Reolink, UniFi Protect…) show up on the Cameras page even
without Frigate. When Frigate runs somewhere else than as an add-on (own container, another machine), enter its
address in the add-on settings (`frigate_url`, e.g. `http://192.168.1.50:5000`) – recording and person detection
can then be set up through the add-on too.

Risky changes (installing an add-on, updates, deleting, switching sockets) only happen after you confirm them
in Change history. The add-on never changes your system on its own.

### Options

- **Cloud address** – change only when support tells you to.

Support: info@chytrejdum.cz
