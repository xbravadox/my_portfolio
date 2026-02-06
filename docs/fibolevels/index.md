# FiboLevels_ML-AI - Projekt skanera giełdowego

FiboLevels_ML-AI to zaawansowane narzędzie analityczne łączące klasyczną analizę techniczną, uczenie maszynowe (ML) oraz sztuczną inteligencję (LLM) w celu identyfikacji i oceny wysokoprawdopodobnych setupów giełdowych opartych na konfluencji poziomów Fibonacciego.

## Główne Funkcjonalności
 - ***Automatyczna weryfikacja trendu***: System analizuje położenie ceny względem średniej SMA 200 na interwałach W1 i D1, co stanowi fundament strategii.
 - ***Detekcja Konfluencji***: Silnik identyfikuje klastry cenowe poprzez nakładanie się poziomów Fibonacciego (38.2, 50.0, 61.8, 78.6) wyznaczonych z ostatniego szczytu i wielu dołków rynkowych.
 - ***Analityka ML***: Model Machine Learning przeszukuje 20-letnią historię notowań (Yahoo Finance) w celu znalezienia analogicznych setupów i wyliczenia statystycznego prawdopodobieństwa sukcesu.
 - ***Synteza AI***: Integracja z modelem LLM pozwala na wygenerowanie narracyjnej oceny ryzyka i komentarza analitycznego na podstawie twardych danych technicznych.
Interaktywny Dashboard: Intuicyjny interfejs zbudowany w Streamlit, prezentujący wykresy, dane statystyczne oraz rekomendacje AI.