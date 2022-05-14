## Pre-requisiti
Scaricare ed installare tutte le dipendenze necessarie per eseguire Tensorflow Lite e YoloV5 (PyTorch) sul vostro raspberry.
Potete utilizzare un ambiente virtuale oppure anaconda.

### 1. TFLite
Inserire le immagini nella cartella ``images`` ed eseguire il comando:

```
python detect.py  --model animals_20_epochs.tflite
```

### 2. YoloV5
Inserire le immagini nella cartella ``data/images`` ed eseguire il comando:

```
python detect.py --source data/images --weights best.pt --conf 0.25
```