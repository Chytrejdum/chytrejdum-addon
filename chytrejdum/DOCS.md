# Chytrej dům

**Česky** · [English below](#english)

## Co to je

Asistent pro správu a ovládání chytré domácnosti. Napíšeš mu obyčejnou češtinou, co chceš – třeba
„rozsviť v noci tlumeně chodbu, když se otevřou dveře“ – a on to v domácím systému nastaví: automatizace,
místnosti, ovládací panely, kamery, Zigbee i doplňky. Nemusíš znát YAML ani názvy entit.

V panelu **Chytrej dům** najdeš navíc přehled domu, zařízení, Historii změn (každá změna je zapsaná a jde
vrátit) a stav zabezpečení.

## Základní asistent a placená AI

- **Zdarma:** odpovídá vestavěný asistent domácího systému. Zvládne jednoduché ovládání („zhasni v kuchyni“),
  ale ne složitější nastavení a úlohy.
- **Placená AI:** na každý úkol si vybere vhodný model, nastaví automatizace i ovládací panely a pamatuje si,
  co máš rád. Platí se AI kredity – AI předplatným, nebo jednorázově – na
  [moje.chytrejdum.cz](https://moje.chytrejdum.cz) v sekci Balíčky.

Na Přehledu pod chatem vždy vidíš, která verze ti odpovídá.

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

Rizikové změny (instalace doplňku, aktualizace, smazání, spínání zásuvek) se provedou až po tvém potvrzení
v Historii změn. Sám od sebe doplněk nastavení systému nemění.

## Nastavení

- **Adresa cloudu** – měň jen na pokyn podpory.

Podpora: info@chytrejdum.cz

---

## English

### What it is

An assistant for managing and controlling your smart home. Tell it in plain words what you want – for example
"dim the hallway lights at night when the door opens" – and it sets it up in your home system: automations,
rooms, dashboards, cameras, Zigbee and add-ons. No YAML or entity names needed.

The **Chytrej dům** panel also gives you a home overview, devices, Change history (every change is recorded and
can be undone) and a security overview. The app follows your browser language (Czech or English).

### Basic assistant and paid AI

- **Free:** the built-in assistant of your home system answers. It handles simple control ("turn off the kitchen
  lights"), but not more complex setup and tasks.
- **Paid AI:** picks the right model for each task, sets up automations and dashboards, and remembers what you
  like. It's paid with AI credits – an AI subscription or one-off credits – at
  [moje.chytrejdum.cz](https://moje.chytrejdum.cz) under Plans.

The Overview page always shows under the chat which version is answering.

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

Risky changes (installing an add-on, updates, deleting, switching sockets) only happen after you confirm them
in Change history. The add-on never changes your system on its own.

### Options

- **Cloud address** – change only when support tells you to.

Support: info@chytrejdum.cz
