# Chytrej dům

**Česky** · [English below](#english)

## Co to je

Tvůj parťák pro chytrou domácnost. Napíšeš mu obyčejnou češtinou, co chceš – třeba
„rozsviť v noci tlumeně chodbu, když se otevřou dveře“ – a on to v domácím systému nastaví: automatizace,
místnosti, ovládací panely, kamery, Zigbee i doplňky. Nemusíš znát YAML ani názvy entit.

K tomu dostaneš aplikaci v postranním panelu, kde je celý dům přehledně na pár stránkách – a každá změna je
zapsaná a jde vrátit.

## Co najdeš v panelu Chytrej dům

- **Parťák** (první položka, nese jeho jméno) – rozhovor, stav domu, co tě čeká a denní tipy.
- **Zařízení** – místnosti jako dlaždice, přidání zařízení krok za krokem (Zigbee, Wi-Fi, Matter, ESP),
  hromadné přesuny, **Hlídač baterií**, **Hlídač odpojených zařízení** a **Úklid** (co v domě už nežije).
- **Kamery** – hledání kamer v síti, silná hesla místo výchozích, záznam a rozpoznávání osob, aut a zvířat ve
  Frigate, zóny a masky kreslené myší, rozpoznávání obličejů.
- **Automatizace** – seznam s vysvětlením, co která dělá, průvodce a úpravy slovy přes parťáka.
- **Ovládací panely** – nový panel s parťákem, kdo má který panel výchozí, a **centrální tablet** na zdi
  (Fully Kiosk): co ukazuje, jas, zhasínání, probuzení pohybem, hlasitost.
- **Správce domu** – **Doklady** a **Smlouvy a revize**: vyfotíš účtenku, smlouvu nebo revizní zprávu, parťák
  z ní vyčte cenu, datum a záruku a **Hlídač** termín sám připomene. **Nákup a zásoby**: položky z účtenek
  z obchodu se přičtou do zásob a co dochází, jde na nákupní seznam. **Svoz odpadu**: nejbližší svozy po dnech
  s připomínkou večer předem. Filtry a poplatky.
- **Uživatelé** – **Osoby v domácnosti** (správce nebo uživatel, telefon s polohou a upozorněními, výchozí panel,
  fotka i pro rozpoznávání obličejů) a **účty pro zařízení** (tablet, telefon, auto – kde a kdy se používají).
- **Upozornění** – jak a kam upozorňovat (problémy domu, kamery, výpadek internetu) a historie posledních
  upozornění s možností je blokovat.
- **Historie změn** – jeden řádek za každou změnu od parťáka a každou aktualizaci, s tlačítkem **Vrátit** nebo
  **Obnovit ze zálohy**.
- **Hesla a soukromí** – šifrovaný **Trezor hesel** (kamery, zařízení, router, účty; klíč je jen v domě),
  přehled **Kam odcházejí tvá data** a posuvníky **Co smí parťák**.
- **Síť** – Správce sítě pro router MikroTik (Wi-Fi, zařízení v síti, doporučený firewall; každá změna jde
  vrátit) a průvodce nastavením pro routery jiných značek.
- **Systém** – počítač a virtuální stroje, aktualizace, zálohy se šifrováním a obnovou, externí úložiště
  (USB, NAS, Google Drive, OneDrive), údržba, Zigbee a UPS.
- **Účet a doplňky** – spárování s účtem, balíček a AI kredity, přístup na dálku, dvoufázové ověření, hlasové
  ovládání, vzhled a jazyk.

Aplikace mluví česky nebo anglicky podle prohlížeče.

## Základní parťák a placená AI

- **Zdarma:** odpovídá vestavěný parťák domácího systému. Zvládne jednoduché ovládání („zhasni v kuchyni“),
  ale ne složitější nastavení a úlohy. Všechny stránky aplikace fungují bez placení.
- **Placená AI:** na každý úkol si vybere vhodný model, nastaví automatizace i ovládací panely, čte fotky
  a doklady a pamatuje si, co máš rád. Platí se AI kredity – 1 000 měsíčně v balíčku PRO, nebo jednorázově
  (nepropadají) – na [moje.chytrejdum.cz](https://moje.chytrejdum.cz) v sekci Balíčky.

Kolik kreditů zbývá, vidíš pořád dole v menu.

## Co parťák umí (placená AI)

- **Ovládá dům hned:** „rozsviť v obýváku na 30 %“, „nastav topení na 21“, „zamkni“, „pusť scénu Večer“,
  „zavři žaluzie“ – udělá to rovnou a jde to vrátit v Historii změn.
- **Ví, co se dělo:** „kdy se naposledy otevřely dveře?“, „kdo rozsvítil v garáži?“, „jak bylo v noci v ložnici?“
  – z deníku a historie domácího systému. „Kolik jsme spotřebovali minulý měsíc?“ – z dlouhodobých statistik.
- **Zkontroluje celý systém:** „je všechno v pořádku?“ – aktualizace, nedostupná zařízení, slabé baterie,
  nefunkční integrace, chyby v protokolu, zálohy a místo na disku; k nalezeným potížím nabídne opravu.
- **Automatizace a scény:** vytvoří i upraví („přidej podmínku, že světla jsou 15 minut zhasnutá“), víc situací
  zapíše jako jednu automatizaci s větvením. „Ulož obývák, jak je teď, jako scénu Večer.“
- **Ovládací panely:** úpravu popíšeš slovy a parťák ji udělá přímo v panelu – nevytváří kopii. Umí i ručně
  dělané karty a karty doplňků (button-card, Bubble Card, Mushroom): změní jméno, ikonu, akci nebo vzhled, přidá
  další tlačítko ve stejném stylu. Kartu s vlastním kódem vždy potvrzuješ.
- **Kamery:** „kdo byl dnes u branky?“ ukáže snímek z události. „Je otevřená brána?“ – vezme si aktuální snímek
  kamery a odpoví podle něj.
- **Doklady a Správce domu:** z fotky nebo PDF vyčte údaje dokladu, smlouvy či revize; „připomeň mi za rok revizi
  kotle“, „přidej na nákupní seznam mléko“, „co máme v zásobách?“.
- **Energie a fotovoltaika:** poradí s připojením střídače (Fronius, GoodWe, SMA, SolaX, Growatt, Huawei,
  Victron, Deye, Solinteg), nastaví spotřebič na přebytek, v levných hodinách podle spotu (OTE) nebo v nízkém
  tarifu (HDO), nastaví panel Energie a spočítá úsporu.
- **Větrání a rekuperace:** výkon, režimy, klapky zón, větrání podle CO₂ nebo vlhkosti.
- **Vrata a brána na jedno relé:** z relé, které střídá otevřít–stop–zavřít, udělá pořádná vrata se stavem.
- **Vlastní zařízení na ESP32:** meteostanice, CO₂, hlídač vody, relé, teploměr, čtečka elektroměru a vodoměru…
  – hotové nastavení v ESPHome, obrázek zapojení a návod (**Přidat zařízení → Vlastní zařízení ESP**).
  Zavlažování: řídicí jednotka ventilů a rozvrh, který počká, když má pršet.
- **Výběr zařízení:** „chci hlídat vodu v kotelně, co koupit?“ – druh zařízení, kolik kusů, kam je dát
  a dnešní ceny v českých obchodech.
- **Virtuální stroje (Proxmox):** „restartuj Frigate“, „zazálohuj domácí systém“, „přidej mu paměť“.
- **Denní hlášení a tipy:** každé ráno sám řekne, co dům potřebuje; jednou denně navrhne vylepšení podle tvých
  zařízení (tlačítko **Udělat to**).
- **Fotky a diktování:** tlačítkem **+** přiložíš až tři fotky (štítek, zapojení, chybová hláška, snímek
  obrazovky). Tlačítkem **Mluvit** zprávu nadiktuješ – řeč na text převádí tvůj prohlížeč nebo telefon.
  Čtení odpovědí přirozeným hlasem připravujeme.
- **Jméno, rod a povaha:** parťáka si pojmenuješ jako člena rodiny (ona, on, ono) a vybereš povahu.
- **Paměť:** v jednom rozhovoru ví všechno, co jste si napsali; **Nový rozhovor** začneš tlačítkem v hlavičce
  (sám začne i po 6 hodinách bez zprávy a po restartu doplňku). Trvalá paměť jsou krátké poznámky o tom, co máš
  rád – až 40, dokud je nesmažeš („zapamatuj si…“ / „zapomeň…“; vidíš a mažeš je na portálu v Nastavení →
  Paměť parťáka). V cloudu se podrobnosti o krocích parťáka drží 30 dní, celý rozhovor 90 dní od poslední zprávy.

## Co smí parťák a soukromí

- **Co smí parťák:** v **Hesla a soukromí** si pro každou oblast (ovládání zařízení, automatizace, panely,
  zařízení, kamery, síť, energie, systém, Proxmox, Správce domu) vybereš **Smí sám** / **Jen s potvrzením** /
  **Nesmí**. Hlídá to doplněk sám, parťák to obejít nemůže.
  - *Smí sám* = změnu udělá bez ptaní, i riskantní (třeba odemknout nebo otevřít vrata) – vždy po záloze,
    zapíše ji do Historie změn a jde vrátit.
  - Ve výchozím nastavení mají síť, systém a Proxmox *Jen s potvrzením*, ostatní *Smí sám*.
  - Změnu připojení k internetu, názvu nebo hesla Wi-Fi, návrat ke starší záloze, odebrání integrace a vypnutí
    nebo restart virtuálního stroje potvrzuješ **vždy**.
- **Potvrzení v rozhovoru:** co čeká na tvůj souhlas, potvrdíš tlačítkem přímo pod odpovědí (nebo v Historii
  změn v části Čeká na tebe). Návrh platí 30 minut.
- **Co jde do cloudu:** tvoje zpráva a to, co parťák k úkolu potřebuje (názvy zařízení, stavy). Fotky v chatu,
  fotky dokladů a aktuální snímek kamery, na který se zeptáš, se v cloudu jen přečtou pro tu odpověď a do
  rozhovoru se neukládají. Doklady, smlouvy, zásoby a hesla zůstávají jen v domě; hesla ani obsah Trezoru
  parťák nevidí. Záznamy z kamer zůstávají doma.

## První spuštění

1. U doplňku zapni **Zobrazit na postranním panelu** (nebo klikni na **Otevřít webové rozhraní**).
2. V panelu **Chytrej dům → Účet a doplňky** spáruj dům se svým účtem na
   [moje.chytrejdum.cz](https://moje.chytrejdum.cz).
3. Pro plnou funkčnost aktivuj na portálu placenou AI.

## Co doplněk smí

- číst a měnit nastavení domácího systému (automatizace, místnosti, ovládací panely, zálohy, aktualizace),
- spravovat doplňky, zálohy, aktualizace, počítač a jeho síť přes Supervisor (role admin),
- číst a měnit soubory domácího systému a ostatních doplňků (konfigurace, sdílené soubory, média, zálohy);
  ze souborů s účty čte jen popisné údaje (které zařízení se kdy přihlásilo), nikdy přihlašovací klíče,
- používat USB a sériová zařízení (Zigbee a Thread adaptéry),
- hledat kamery a zařízení v domácí síti; kamery přidá do doplňku Frigate a napojí ho na MQTT broker domu
  (čidla „osoba“).

**Proxmox:** běží-li domácí systém na Proxmoxu, propoj ho v **Systém → Počítač a stroje** (adresa + API token;
jen pro čtení stačí role PVEAuditor). Doplněk pak ukáže vytížení počítače, všechny stroje a kontejnery a jejich
zálohy, nehlásí „zálohy vypnuté“, když zálohuje Proxmox, doporučí kopii mimo počítač a najde Frigate
v kontejneru. S rolemi PVEVMAdmin a PVEDatastoreUser tam stroje zapneš, vypneš, restartuješ, zazálohuješ,
uděláš snapshot nebo změníš procesory a paměť (Historie změn, vrácení). Pro pokročilé je tam i odkaz na terminál
a web Proxmoxu.

Kamery z jakékoli integrace domácího systému (ONVIF, Reolink, UniFi Protect…) doplněk vidí na stránce Kamery
i bez Frigate. Když Frigate běží jinde než jako doplněk (vlastní kontejner, jiný počítač), zadej jeho adresu na
stránce Kamery (nebo v nastavení doplňku `frigate_url`, třeba `http://192.168.1.50:5000`) – pak jde přes doplněk
nastavovat i záznam a hlídání osob.

Sám od sebe doplněk nastavení systému nemění – jen na tvůj pokyn nebo pokyn parťáka v mezích, které mu nastavíš.

## Nastavení

- **Adresa cloudu** – měň jen na pokyn podpory.
- **Adresa Frigate** a **RTSP adresa Frigate** – jen když Frigate neběží jako doplněk.

Návody: [chytrejdum.cz/napoveda](https://www.chytrejdum.cz/napoveda/) · Podpora: info@chytrejdum.cz

---

## English

### What it is

Your smart home buddy. Tell it in plain words what you want – for example
"dim the hallway lights at night when the door opens" – and it sets it up in your home system: automations,
rooms, dashboards, cameras, Zigbee and add-ons. No YAML or entity names needed.

You also get an app in the sidebar that shows the whole home on a few clear pages – and every change is
recorded and can be undone.

### What's in the Chytrej dům panel

- **Buddy** (the first item, under its name) – the chat, home status, what's coming up and daily tips.
- **Devices** – rooms as tiles, step-by-step adding (Zigbee, Wi-Fi, Matter, ESP), bulk moves, the **Battery
  watch**, the **Disconnected devices watch** and **Clean-up** (what no longer lives in the home).
- **Cameras** – finding cameras on the network, strong passwords instead of defaults, recording and detection
  of people, cars and animals in Frigate, zones and masks drawn with the mouse, face recognition.
- **Automations** – a list explaining what each one does, a wizard, and edits in plain words via the buddy.
- **Dashboards** – a new dashboard with the buddy, who has which default, and the **central wall tablet**
  (Fully Kiosk): what it shows, brightness, screen-off, wake on motion, volume.
- **House manager** – **Documents** and **Contracts and inspections**: take a photo of a receipt, contract or
  inspection report, the buddy reads the price, date and warranty and the **Watcher** reminds you in time.
  **Shopping and pantry**: items from shop receipts go into the pantry and what runs low goes on the shopping
  list. **Bin collection**: the next collections day by day with a reminder the evening before. Filters and fees.
- **Users** – **People in the household** (admin or user, phone with location and notifications, default
  dashboard, a photo also used for face recognition) and **accounts for devices** (tablet, phone, car – where and
  when they are used).
- **Alerts** – how and where to notify (home problems, cameras, internet outage) and a history of recent alerts
  with a block button.
- **Change history** – one line per change made by the buddy and per update, with **Revert** or **Restore from
  backup**.
- **Passwords and privacy** – the encrypted **Password vault** (cameras, devices, router, accounts; the key stays
  at home), the **Where your data goes** overview and the **What the buddy may do** sliders.
- **Network** – the network manager for a MikroTik router (Wi-Fi, devices on the network, recommended firewall;
  every change can be undone) and a setup guide for routers of other brands.
- **System** – the computer and virtual machines, updates, backups with encryption and restore, external storage
  (USB, NAS, Google Drive, OneDrive), maintenance, Zigbee and UPS.
- **Account and add-ons** – linking to your account, plan and AI credits, remote access, two-factor
  verification, voice control, appearance and language.

The app follows your browser language (Czech or English).

### Basic buddy and paid AI

- **Free:** the built-in buddy of your home system answers. It handles simple control ("turn off the kitchen
  lights"), but not more complex setup and tasks. All pages of the app work without paying.
- **Paid AI:** picks the right model for each task, sets up automations and dashboards, reads photos and
  documents and remembers what you like. It's paid with AI credits – 1,000 a month with the PRO plan, or one-off
  credits that don't expire – at [moje.chytrejdum.cz](https://moje.chytrejdum.cz) under Plans.

The credits you have left are always shown at the bottom of the menu.

### What the buddy can do (paid AI)

- **Controls the home right away:** "turn the living room lights on at 30 %", "set the heating to 21", "lock up",
  "run the Evening scene", "close the blinds" – done at once and revertible in Change history.
- **Knows what happened:** "when did the door last open?", "who turned the garage light on?", "how warm was the
  bedroom at night?" – from the home system's logbook and history. "How much did we use last month?" – from
  long-term statistics.
- **Checks the whole system:** "is everything OK?" – updates, unavailable devices, low batteries, failing
  integrations, errors in the log, backups and disk space; it offers to fix what it finds.
- **Automations and scenes:** creates and edits them ("add a condition that the lights have been off for 15
  minutes"), writes several situations as one branching automation. "Save the living room as it is now as scene
  Evening."
- **Dashboards:** describe a change in words and the buddy makes it in place – no copies. It also edits
  hand-made and add-on cards (button-card, Bubble Card, Mushroom): name, icon, action or look, and adds another
  button in the same style. A card with its own code always needs your OK.
- **Cameras:** "who was at the gate today?" shows the event snapshot. "Is the gate open?" – it takes the current
  camera picture and answers from it.
- **Documents and House manager:** reads a receipt, contract or inspection report from a photo or PDF; "remind me
  of the boiler inspection in a year", "add milk to the shopping list", "what do we have in the pantry?".
- **Energy and photovoltaics:** helps connect the inverter (Fronius, GoodWe, SMA, SolaX, Growatt, Huawei,
  Victron, Deye, Solinteg), runs appliances on solar surplus, in cheap spot-price hours or in the low tariff,
  sets up the Energy panel and calculates savings.
- **Ventilation and recuperation:** power, modes, zone dampers, ventilation by CO₂ or humidity.
- **Garage door or gate on one relay:** turns a relay that cycles open–stop–close into a proper cover with a state.
- **DIY ESP32 devices:** weather station, CO₂, water leak, relay, thermometer, electricity and water meter
  reader… – ready ESPHome configuration, a wiring picture and a guide (**Add device → DIY ESP devices**).
  Garden watering: a valve controller and a schedule that waits when rain is expected.
- **Choosing devices:** "I want to watch for water in the boiler room, what should I buy?" – the kind of device,
  how many, where to put them and today's prices in Czech shops.
- **Virtual machines (Proxmox):** "restart Frigate", "back up the home system", "give it more memory".
- **Daily report and tips:** every morning it tells you on its own what the home needs; once a day it suggests an
  improvement based on your devices (the **Do it** button).
- **Photos and dictation:** the **+** button attaches up to three photos (a label, wiring, an error message,
  a screenshot). The **Speak** button dictates a message – your browser or phone turns speech into text.
  Reading replies aloud in a natural voice is coming.
- **Name, gender and character:** name the buddy like a family member (she, he, it) and pick its character.
- **Memory:** within one conversation it knows everything you wrote; start a **New conversation** with the button
  in the header (one also starts after 6 hours without a message and after an add-on restart). Long-term memory
  is short notes about what you like – up to 40, until you delete them ("remember…" / "forget…"; see and delete
  them in the portal under Settings → Buddy memory). In the cloud the details of the buddy's steps are kept for
  30 days, a whole conversation for 90 days after the last message.

### What the buddy may do, and privacy

- **What the buddy may do:** in **Passwords and privacy** you choose per area (device control, automations,
  dashboards, devices, cameras, network, energy, system, Proxmox, House manager) **On its own** / **Only with my
  OK** / **Not allowed**. The add-on enforces it – the buddy can't get around it.
  - *On its own* = it makes the change without asking, even a risky one (such as unlocking or opening a garage
    door) – always after a backup, recorded in Change history and revertible.
  - By default network, system and Proxmox are *Only with my OK*, the rest *On its own*.
  - Changing the internet connection, a Wi-Fi name or password, going back to an older backup, removing an
    integration and stopping or restarting a virtual machine **always** need your OK.
- **Confirm in the chat:** whatever waits for your OK is confirmed with a button right under the reply (or in
  Change history under Waiting for you). A proposal is valid for 30 minutes.
- **What goes to the cloud:** your message and what the buddy needs for the task (device names, states). Photos
  in the chat, photos of documents and the current camera picture you ask about are only read in the cloud for
  that answer and are not kept in the conversation. Documents, contracts, the pantry and passwords stay at home
  only; the buddy never sees passwords or the vault's contents. Camera recordings stay at home.

### First start

1. Turn on **Show in sidebar** for the add-on (or click **Open web UI**).
2. In **Chytrej dům → Account and add-ons**, link your home to your account at
   [moje.chytrejdum.cz](https://moje.chytrejdum.cz).
3. For full functionality, activate paid AI in the portal.

### What the add-on can access

- read and change your home system's configuration (automations, rooms, dashboards, backups, updates),
- manage add-ons, backups, updates, the host and its network through the Supervisor (admin role),
- read and change files of the home system and other add-ons (configuration, share, media, backups); from the
  account files it reads only descriptive data (which device signed in and when), never sign-in keys,
- use USB and serial devices (Zigbee and Thread adapters),
- discover cameras and devices on your home network; it adds cameras to the Frigate add-on and connects it to
  the home MQTT broker ("person" sensors).

**Proxmox:** if your home system runs on Proxmox, link it in **System → Computer and machines** (address + API
token; the PVEAuditor role is enough for read-only). The add-on then shows the host load, all machines and
containers and their backups, stops reporting "backups off" when Proxmox backs up, recommends a copy off the
machine and finds Frigate in a container. With the PVEVMAdmin and PVEDatastoreUser roles you can start, stop,
restart and back up machines, take snapshots or change CPUs and memory there (Change history, revert). For
advanced users there is also a link to the Proxmox terminal and web.

Cameras from any integration of the home system (ONVIF, Reolink, UniFi Protect…) show up on the Cameras page even
without Frigate. When Frigate runs somewhere else than as an add-on (own container, another machine), enter its
address on the Cameras page (or in the add-on settings, `frigate_url`, e.g. `http://192.168.1.50:5000`) –
recording and person detection can then be set up through the add-on too.

The add-on never changes your system on its own – only when you or the buddy ask, within the limits you set.

### Options

- **Cloud address** – change only when support tells you to.
- **Frigate address** and **Frigate RTSP address** – only when Frigate doesn't run as an add-on.

Guides: [chytrejdum.cz/en/help](https://www.chytrejdum.cz/en/help/) · Support: info@chytrejdum.cz
