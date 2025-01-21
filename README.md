# Prädikative Instandhaltung - Fallbeispiel: Wälzlager

Wälzlager sind ein wichtiges Bauteil. In diesem Fallbeispiel ermitteln wir Fehler in Wälzlagern mithilfe von Deep Learning. Das Jupyter-Notebook führt Sie Schritt-für-Schritt zu einer erfolgreichen Fehlerdiagnose.

## Verwendeter Datensatz

Wir verwenden den Datensatz von der MFPT (Society for Machinery Failure Prevention Technology): https://www.mfpt.org/fault-data-sets/.

## Inhalt des Notebooks

1. Datenanalyse - Hier können Sie sich die gegebenen Daten ansehen.
2. Datenvorbereitung - Hier zeigen wir, wie die Daten für das KI-basierte Lernen umgewandelt werden
3. Training - Hier trainieren wir ein (vortrainiertes) neuronales Netz und werten die Trainingsergebnisse aus.
4. Ergebnis - Hier visualisieren wir die Ergebnisse vom Training.

## Verwendete Bibliotheken

Folgende Bibliotheken werden verwendet und müssen installiert sein.

1. Pandas - pip install pandas
2. PyTorch - pip install torch
3. TorchVision - pip install torchvision
4. SciPy - pip install scipy
5. PyWavelets - pip install PyWavelets

## Verwendung dieses Fallbeispiels

### Docker

Wenn Sie Docker verwenden, starten Sie das Jupyter-Notebook mit

```
docker compose up
```

### Jupyter Notebook

Wenn Sie Jupyter Notebook lokal installiert haben, navigieren Sie in den src/ Ordner und starten Sie das Notebook mit

```
jupyter lab
```

## Bei Fragen

Bei Fragen wenden Sie sich an Daniel Schreiber (daniel.schreiber@hs-merseburg.de).

## Weiterführende Links

1. Datensatz: https://www.mfpt.org/fault-data-sets/
2. Umsetzung des Fallbeispiels in MATLAB: https://de.mathworks.com/help/predmaint/ug/rolling-element-bearing-fault-diagnosis-using-deep-learning.html?s_tid=srchtitle_site_search_1_rolling-element-bearing-fault-diagnosis-using-deep-learning
