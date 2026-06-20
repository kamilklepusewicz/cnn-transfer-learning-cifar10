# Porównanie architektur CNN z transfer learningiem

Projekt zaliczeniowy z przedmiotu Projektowanie i Zastosowania Sieci Neuronowych.

## Cel projektu

Celem projektu jest porównanie skuteczności wybranych architektur konwolucyjnych sieci neuronowych w zadaniu klasyfikacji obrazów na zbiorze CIFAR-10.

## Wykorzystane modele

- Simple CNN trenowana od zera
- ResNet18 z transfer learningiem
- MobileNetV2 z transfer learningiem

## Zakres analizy

Modele porównano pod względem:
- dokładności klasyfikacji,
- czasu treningu,
- liczby trenowanych parametrów,
- macierzy pomyłek,
- przykładowych predykcji.

Projekt rozszerzono również o element Explainable AI z wykorzystaniem metody Grad-CAM dla modelu ResNet18.

## Wyniki

Najlepszy wynik uzyskał ResNet18, osiągając około 76% accuracy na zbiorze testowym. Modele wykorzystujące transfer learning osiągnęły lepsze wyniki niż prosta sieć CNN trenowana od zera.

## Link do notebooka Kaggle

https://www.kaggle.com/code/kamilklepusewicz/por-wnanie-architektur-cnn-z-transfer-learningiem?scriptVersionId=328947275
