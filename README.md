# **Punishment Skript**

Verzió szám: **[1.0.1 - Hotfix](https://pastebin.com/RbzMPk3L)**

Készítette: **[AdamGaming13](https://www.youtube.com/channel/UCMW9GpGBMsOtKGsN1JeXN6Q)**

## **Funkciók:**
- [ ] GUI
- [ ] Tempban
- [ ] Mute
- [ ] Auto update
- [ ] Tab auto complete
- [x] Ban/Unban
- [x] Kick
- [x] Update check
- [x] Config fájl

## **Követelmények\Requirements:**

- **[Skript](https://github.com/SkriptLang/Skript/releases)**
- **[SkQuery](https://www.spigotmc.org/resources/skquery-1-9-1-14.36631/)**
- **[Skript-yaml](https://github.com/Sashie/skript-yaml/releases/)**
- **[SkUtilities](https://github.com/tim740/skUtilities/releases/)**
- **[Skript-json](https://github.com/btk5h/skript-json/releases)**
- **[json.sk](https://forums.skunity.com/resources/json-sk.23/)**

## **Parancsok:**

- `/punishment` - Fő parancs.
  - `help` - A skript használatának utasításai.
  - `skriptreload` - **FIGYELEM!** Csak akkor használd ha teljes skriptet újra akarod índítani!
  - `reload` - Újratöltia a config fáljt. **Használd a /p skriptreload helyett!**
  - `file` - **FIGYELEM!** Csak akkor használd ha nincs meg a config fájl vagy újra akarod rakni a configot!
  - `update` - A Skript frissítési beállításai.
    - `version` - Verzió szám megtenkintése.
    - `log` - Fríssétesi napló megnézése.
    - `check` - Megnézi, hogy van-e elérhető frissítés.
    - `update` - Nincs még funkciója.
- `/ban [játékos] <indok> <idő>` \- Kitiltja a játékost egy indokkal (Idő nem működik).    **[] \- kötelező megadni <> \- optimális** 
- `/kick [játékos] <indok>` \-  Kirúgja a játékost egy indokkal.    **[] \- kötelező megadni <> \- optimális**
- `/unban [játékos] <indok>` \- Feloldja a játékost tiltálsát egy indokkal.    **[] \- kötelező megadni <> \- optimális**
