# MLnaGPW_SDA
Projekt Analizy i Modelowania Danych Giełdowych

Ten projekt ma na celu przeprowadzenie analizy danych giełdowych oraz zastosowanie różnych modeli regresji do przewidywania cen akcji na przykładzie rzeczywistych danych z rynku.
Opis Projektu

Celem tego projektu jest zaprezentowanie procesu analizy danych giełdowych oraz zastosowania trzech różnych modeli regresji w celu przewidywania cen akcji na kolejny dzień. Projekt wykorzystuje dane historycznych notowań giełdowych, w tym ceny otwarcia, zamknięcia, najwyższe i najniższe ceny oraz wolumen handlu, pobrane ze strony giełdowej.
Wykorzystane Modele

W projekcie wykorzystano trzy różne modele regresji do przewidywania cen akcji:

    Linear Regression (Regresja Liniowa): Model liniowej regresji wykorzystuje liniową zależność między cechami a cenami akcji do przewidzenia przyszłych cen.

    RNN LSTM (Recurrent Neural Network Long Short-Term Memory): Model ten wykorzystuje sieć neuronową typu RNN z komórkami LSTM, co pozwala uwzględnić zależności czasowe w danych i lepiej modelować szereg czasowy.

    Random Forest Regressor: Model oparty na losowym lesie, który tworzy wiele drzew regresji i łączy ich przewidywania w celu uzyskania bardziej stabilnych i precyzyjnych prognoz.

Struktura Projektu

    notebooks/ zawiera notatniki Jupyter z kodem analizy danych i modelowania.
    results/ to folder, gdzie przechowywane są wyniki analiz i modelowania.
    README.md to plik, który zawiera opis projektu.

Jak Używać Projektu

    Sklonuj repozytorium na swój lokalny komputer.
    Uruchom notatniki w folderze notebooks/, aby przeprowadzić analizę danych i modelowanie.
    Wyniki analizy i modelowania będą zapisywane w folderze results/.

Wymagania

    Python 3.x
    NumPy
    pandas
    scikit-learn
    Keras (do modelu RNN LSTM)
    matplotlib
    Jupyter Notebook

Autor

Projekt został stworzony przez [Twoje Imię/Nazwisko].
