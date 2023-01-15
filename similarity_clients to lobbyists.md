### 1) Trennung der '2023-01-04_12_00_Lobbyregistersuche_organizations_clients_lobbyists.csv' in clients & lobbyists
- via Textfacette über 'role'
- beide entstandenden csvs als eigene Projekte in OpenRefine öffnen
### 2) in beiden Projekten eine neue Spalte aus 'label_fuer_abgleich' erstellen
- dort dann via regex alle non-word-characters entfernen: value.replace(/\W/, "")
