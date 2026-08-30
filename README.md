# AI Use Case Evaluator

## Modul

IN258 Document Oriented Databases and Exchange Formats

## Projektziel

Ziel dieses Projekts ist die Entwicklung einer Anwendung zur Bewertung von KI-Anwendungsfällen.

Die Anwendung speichert verschiedene Use Cases in einer dokumentenorientierten Datenbank (MongoDB), bewertet deren KI-Eignung anhand definierter Kriterien und ermöglicht den Vergleich unterschiedlicher Lösungsansätze.

Leitfrage:

> Unter welchen Bedingungen erzeugt der Einsatz von KI einen grösseren Nutzen als eine klassische, regelbasierte oder manuelle Lösung?

---

# Technologien

- Java 21
- Maven
- MongoDB
- MongoDB Compass
- Git / GitHub
- Visual Studio Code

---

# Projektstruktur

```text
AI-UseCase-Evaluator
│
├── src
│   └── main
│       └── java
│           ├── Main.java
│           │
│           ├── model
│           │   └── UseCase.java
│           │
│           ├── service
│           │   └── MongoService.java
│           │
│           └── evaluation
│               └── UseCaseEvaluator.java
│
├── screenshots
│
├── README.md
│
└── pom.xml
```
