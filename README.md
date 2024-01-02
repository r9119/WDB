# WDB Web datenbeschaffung HS 2023
In diesem Repo liegt der Code, Daten und Dokumentation für die WDB mini challenge vom HS 2023.

## Daten:
Die Daten sind im Verzeichnis `data` gespeichert und wurden von der offiziellen Website [Nasdaq.com](https://www.nasdaq.com/market-activity/stocks/screener) gesammelt. Es gibt zwei Dateien in diesem Verzeichnis:
- `nasdaq_stock_list.csv`: enthält das Tickersymbol, den Firmennamen und die Marktkapitalisierung aller an der Nasdaq notierten Aktien.
- `nasdaq_listed_company_financials`: enthält die Finanzdaten aller derzeit an der Nasdaq notierten Aktien.

## Installation:
Um die benötigten Pakete zu installieren, führen Sie den folgenden Befehl im Terminal aus:
```
pip install -r requirements.txt
```

## Verwendung:
Der gesamte Code wurde im Jupyter-Notebook `src\nasdaq_data_scraping.ipynb` geschrieben. Nachdem alle Pakete installiert wurden, kann man das gesamte Notebook ausführen, um die Daten von der Nasdaq seite zu scrapen und im Verzeichnis `data` zu speichern.