# Employee Management System: Backend mit Spring Boot

Dieses Repository enthält das Backend einer Employee Management System-Anwendung, entwickelt mit Spring Boot. Es bietet eine robuste REST-API für die Verwaltung von Mitarbeiterdaten und ist darauf ausgelegt, nahtlos mit einem separaten Frontend zu interagieren.

## Funktionen des Backends

### 1. **Komplette Funktionalität:**
- Bereitstellung von REST-APIs für CRUD-Operationen (Erstellen, Bearbeiten, Löschen und Anzeigen von Mitarbeitern).
- Konfiguration für Cross-Origin-Anfragen (CORS) zur Unterstützung von Frontend-Integration.

### 2. **Technologien:**
- **Backend:** Spring Boot zur Entwicklung skalierbarer REST-APIs.
- **Datenbank:** MySQL als relationale Datenbank.

---

## Backend-Entwicklung mit Spring Boot

### a. **Projektsetup**
- Erstellung einer Spring-Boot-Anwendung mit folgenden Abhängigkeiten:
  - Lombok (Reduktion von Boilerplate-Code)
  - JPA (Java Persistence API für Datenbankzugriffe)
  - MySQL-Treiber
  - Spring Web (Bereitstellung von REST-APIs)

### b. **Datenbankkonfiguration**
- Einrichtung einer MySQL-Datenbank mit folgenden Konfigurationen in `application.properties`:
  - URL
  - Benutzername
  - Passwort

### c. **REST-APIs**
- Implementierung von Endpunkten für die Verwaltung von Mitarbeitern:
  - **POST:** Erstellen eines neuen Mitarbeiters.
  - **GET:** Abrufen eines Mitarbeiters oder einer Liste aller Mitarbeiter.
  - **PUT:** Aktualisieren eines Mitarbeiters.
  - **DELETE:** Löschen eines Mitarbeiters.
- Erweiterte CORS-Konfiguration zur Unterstützung von Anfragen aus verschiedenen Ursprüngen.

### d. **Architektur**
- **Service-Schicht:** Business-Logik und Datenvalidierung.
- **Repository-Schicht:** Datenbankinteraktion mit JPA.
- **Controller-Schicht:** Verarbeitung von API-Anfragen und Antworten.

---

## Setup und Installation

### Voraussetzungen:
- Java 21 oder höher
- MySQL-Datenbank
- Maven (zur Verwaltung von Abhängigkeiten)

### Schritte:
1. **Repository klonen:**
   ```bash
   git clone <repository-url>
   ```
2. **Projekt importieren:**
   - Öffnen Sie das Projekt in IntelliJ IDEA oder einer ähnlichen IDE.
3. **Datenbank konfigurieren:**
   - Passen Sie die Datenbankdetails in der Datei `application.properties` an.
4. **Anwendung starten:**
   ```bash
   mvn spring-boot:run
   ```