# FlashLoan-Demo

Lade das Projekt mit dem folgenden Befehl herunter:
```bash
git clone --recurse-submodules https://github.com/flashbros/flashloan-demo
```

## Voraussetzungen

Dieses Projekt benötigt Docker zum ausführen. Docker ist eine Plattform, mit der Anwendungen in Containern entwickelt, ausgeliefert und ausgeführt werde können.

Sie können Docker von der offiziellen Website herunterladen:
[Docker Download](https://www.docker.com/products/docker-desktop)

Stelle sicher, dass Docker gestartet ist

## Ausführung

### Building Images

Gehe in demo-website und smart-contract Ordner und führe jeweils diesen Befehl aus:

```bash
npm run docker
```

### Starting Container

Um die Container zu starten führe den Befehl aus:

```bash
docker compose up -d
```

Die Website sollte sofort unter localhost:3000 erreichbar sein, jedoch dauert das deployen der Contracts normalerweiser ein bisschen länger.

### Stopping Container

Um die Container zu stoppen führe den Befehl aus:

```bash
docker compose down
```
