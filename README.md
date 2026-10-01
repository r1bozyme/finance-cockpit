# Regel-Cockpit

Persönliches Dashboard, das ein Portfolio gegen ein festes Regelwerk prüft (Verkaufsleitern, Konzentrationsgrenzen, Liquiditätsregel, Sparrate, Zielpfad).

Der Code enthält keine Daten. Die App liest sie zur Laufzeit aus einem privaten Repo über einen Fine-grained Token, der nur im `localStorage` des jeweiligen Geräts liegt (Key `fc-sync`). Erwartete Dateien im Daten-Repo: `rules.json`, `snapshot.json`, `weekly.json`, `state.json`.
