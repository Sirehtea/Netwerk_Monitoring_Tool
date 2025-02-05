# Server Monitoring Tool

Een tool voor het monitoren van servers, waarbij serverstatussen worden bijgehouden en gerapporteerd in HTML-formaat.

## Functies

- Voegt servers toe aan een monitoringslijst.
- Verwijdert servers uit de monitoringslijst.
- Toont de lijst van gemonitorde servers.
- Monitort servers regelmatig.
- Genereert HTML-rapporten van de serverstatus met tijdstempels.
- Slaat de serverstatuslogboeken ook op in JSON-indeling.

## Installatie

1. **Clone deze repository**  
```bash
git clone https://github.com/Sirehtea/Netwerk_Monitoring_Tool.git
cd Netwerk_Monitoring_Tool
```

2. **Installeer requirements**  
```bash
pip install -r requirements.txt
```

3. **Start applicatie**  
```bash
python monitoring_script.py
```

4. **Interactie met het script**  
Het script biedt een interactieve CLI voor het toevoegen, verwijderen, controleren van servers en het starten van monitoring.

```bash
python monitoring_script.py add <servernaam>
python monitoring_script.py remove <servernaam>
python monitoring_script.py list
python monitoring_script.py start <interval>
```

## MapStructuur

```bash
Netwerk_Monitoring_Tool/
├───reports/
│   ├───monitoring_report.html
│   ├───stijl.css
├───monitoring_log.json
├───monitoring_script.py
├───requirements.txt
├───README.md
├───servers.json
```