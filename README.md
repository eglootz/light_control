# Lichterkontrolle und künstliche Intelligenz — Was ist möglich?

In diesem Ordner bewahre ich alle Dateien auf, welche im Zusammenhang mit meinem eingereichten Jugend-Forscht-Projekt stehen.

### Voraussetzungen
Um die Dateien in ihrem Ursprung auszutesten, muss man zusätzlich eine Datei namens credentials.py anlegen, in welcher man benötigte Login-Daten und Schüssel einspeichert. Diese werden anschließend in jeder Datei importiert. Ich habe meine Daten aus Sicherheitsgründen nur lokal gespeichert.
Zu den benötigten Daten zählen u.a.:

#### Gmail
- general_password = allgemeines Passwort
- password = Passwort für Code-Informationen
- sender_email = Email des Senders
- receiver_email = Email des Empfängers
#### Twitter API
api_key = API-Schlüssel
api_secrets = API-Secret
access_token = Zugriffstoken
access_secret = Zugriffscode
#### HUE API
ip_adress = IP-Adresse der Brücke
user = Nutzername
#### OPENAI API
openai_api_key = Schlüssel der KI

#### Installierte packages
Es muss nur das Open-AI-Paket installiert sein:
- pip install openai

### Dateien und ihre Bedeutung
- light_gui.py — manuelle Lichtersteuerung
- automatic_lights.py — Alarmanlage
- intelligente_beleuchtung.py — Steuerung unter Einbezug der KI
