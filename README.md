# Zendure Home Assistant Integration (Fork)

Fork von [zendure-ha](https://github.com/fireson/zendure-ha) basierend auf Version 1.3.1.

## Änderungen gegenüber dem Original

### Version 1.4.0
- **Max. Entladeleistung pro Gerät**: Neue Number-Entity pro Zendure-Gerät, mit der die maximale Entladeleistung individuell begrenzt werden kann.
  - `0` = kein Benutzerlimit (Standard, verhält sich wie das Original)
  - `1–N Watt` = Entladeleistung wird auf maximal N Watt begrenzt
  - Gilt für alle Manager-Modi (Smarte Leistungsregelung, Manuell, usw.)
  - Der Manager plant intern bereits mit dem Limit – kein Oszillieren/Nachregeln

## Installation via HACS

1. HACS → Integrationen → 3-Punkte-Menü → **Benutzerdefinierte Repositories**
2. URL: `https://github.com/Pablo1732/zendure-ha-fork`
3. Kategorie: **Integration**
4. Hinzufügen & installieren

## Original-Projekt

Alle Credits gehen an [@fireson](https://github.com/fireson) und die ursprünglichen Autoren.
