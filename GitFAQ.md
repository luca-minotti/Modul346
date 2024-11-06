# Modul 346

## Git 101

### Was ist Git?
Git ist ein Versionsverwaltungssystem, das benutzt wird, um Quellcode zu verwalten und nachverfolgen. Es bietet eine einfache Möglichkeit, Änderungen am Code aufzuzeichnen und diesen bei verschiedenen Entwicklungsständen zu bearbeiten. Auch ermöglicht es, dass mehrere Entwickler gleichzeitig an einem Projekt arbeiten können, ohne dabei Datenverlust oder Versionskonflikte zu riskieren durch sogenannte Branches.

---

### Welche Vorteile bringt die Verwendung von einem Versionenverwaltungssystem wie Git?
- Alle Änderungen am Code sind nachvollziehbar und man sieht, wer wann was geändert hat
- Man kann den Code auf vorherige Versionen zurücksetzen
- Es können mehrere Entwickler am gleichen Projekt über verschiedene Branches arbeiten
- Über die Branches kann man neue Features ausprobieren, ohne riskieren zu müssen, dass man etwas negativ beeinflusst
- Git lässt sich in CI/CD-Pipelines integrieren, wodurch Tests automatisiert werden können

---

### Wieso kann es sinnvoll sein, nicht alle vorhandenen Veränderungen auf einmal einzuchecken?
- Jede Änderung kann separat nachvollzogen und überprüft werden
- Man kann neue Features so besser organisieren
- Bei einem Problem kann man auf einen kleineren Stand zurückkehren
- Es bietet weniger Konfliktpotenzial durch das schrittweise Einchecken

---

### Wieso sind viele kleine Commits besser als ein riesiger Commit?
- Einzelne Features können besser nachvollzogen werden
- Fehler lassen sich einfacher finden
- Kleinere Commits bieten ein geringeres Risiko an Fehler
- Man kann gezielt nur einen Commit zurücksetzen, falls dieser fehlerhaft ist

---

### Wann und wie oft sollte man seine Änderungen einchecken?
- So oft wie möglich
- Nach jeder kleinen, abgeschlossenen Änderung
- Vor und nach grösseren Änderungen
- Vor dem mergen von Branches