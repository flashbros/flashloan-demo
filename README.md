# FlashLoan-Demo

Lade das Projekt mit dem folgenden Befehl herunter:
```bash
git clone --recurse-submodules https://github.com/flashbros/flashloan-demo
```

## Voraussetzungen

Dieses Projekt benötigt Docker zum ausführen. Docker ist eine Plattform, mit der Anwendungen in Containern entwickelt, ausgeliefert und ausgeführt werden können.

Hier kann Docker von der offiziellen Website heruntergeladen werden:
[Docker Download](https://www.docker.com/products/docker-desktop)

Stelle sicher, dass Docker gestartet ist.

## Ausführung

### Building Images

Gehe in demo-website und smart-contract Ordner und führe jeweils diesen Befehl aus:

```bash
npm run docker
```

### Starting Container

Um die Container zu starten führe den Befehl im Hauptordner aus:

```bash
docker compose up -d
```

Die Website sollte unter der Adresse ``localhost:3000`` im Browser erreichbar sein, jedoch dauert das deployen der Contracts normalerweiser ein bisschen länger.

### Stopping Container

Um die Container zu stoppen führe den Befehl im Hauptordner aus:

```bash
docker compose down
```
