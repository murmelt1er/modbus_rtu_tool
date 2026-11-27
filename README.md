# Modbus RTU Tool

Eigenständiges Windows-Tool für USB-RS485-Adapter zum Scannen, Beschreiben und Inbetriebnehmen von Modbus-RTU-Feldgeräten (inkl. Thermokon JOY & LCF02 Register-Doku, Geräteprofilen und Excel-IBN-Import/Export).

## Funktionen
- **1. Scan:** Schnelles Scannen über beliebige Modbus-IDs und Registeradressen (FC01–FC04) mit automatischer Register-Doku und Wertdekodierung (z. B. `×0.1 °C`, Vorzeichen, Klartext-Status).
- **2. Schreiben:** Batch-Schreiben auf mehrere Modbus-IDs gleichzeitig inkl. optionaler Rücklese-Prüfung.
- **3. Geräte:** Vordefinierte Templates für alle 5 **Thermokon JOY**-Varianten (`Joy Fancoil 5DO`, `Joy Fancoil EC AO2DO`, `Joy Fancoil EC 3AO`, `Joy HC AO2DO`, `Joy HC 3AO`) sowie `LCF02 2AO3DO` & `LCF02 5DO`, durchsuchbarer **Doku-Register Browser** und Batch Read.
- **4. IBN-Liste:** Inbetriebnahme-Liste mit Raumbezeichnung, Beschreibung, Gerätetyp, Status, Live-IBN-Buscheck und Excel-Import/Export (`.xlsx`).

## Verwendung (ohne Installation)
1. `Modbus_RTU_Tool.exe` herunterladen und direkt starten — Python oder zusätzliche Pakete sind nicht erforderlich.
2. Optional `Modbus_IBN_Vorlage_Joy.xlsx` als Excel-Vorlage für den Import verwenden (oder direkt im Tool über **„Excel-Vorlage“** neu erzeugen).
