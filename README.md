# -IlhamiMu-Urlshortener_archive

URL Shortener Microservice
Ein einfacher Microservice, der gekürzte URLs generiert und deren Weiterleitung verwaltet. Entwickelt im Rahmen einer Bachelorarbeit zur Untersuchung des Potenzials generativer KI-Tools in der Softwareentwicklung.



Online-Demo
Der Service ist online abrufbar unter:
https://url-shortener-service-t98x.onrender.com/docs

Hier können alle Endpunkte direkt getestet werden.



Lokale Installation
Repository klonen oder als ZIP herunterladen
bash
git clone https://github.com/IlhamiMu/-IlhamiMu-Urlshortener_archive.git
cd -IlhamiMu-Urlshortener_archive
cd microservice-thesis


Abhängigkeiten installieren
bash
Kopieren
Bearbeiten
pip install -r requirements.txt
Service starten
bash
Kopieren
Bearbeiten
uvicorn main:app --reload

Nutzung
Swagger-Dokumentation (lokal): http://localhost:8000/docs

Beispiel-Endpunkte:
POST /shorten – erstellt eine neue Kurz-URL
GET /{short_id} – leitet auf die Original-URL weiter


