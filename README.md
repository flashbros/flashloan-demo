# FlashLoan-Demo

## Voraussetzungen

Dieses Projekt benötigt Docker zum ausführen. Docker ist eine Plattform, mit der Sie Anwendungen in Containern entwickeln, ausliefern und ausführen können.

Sie können Docker von der offiziellen Website herunterladen:
[Docker Download](https://www.docker.com/products/docker-desktop)

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
