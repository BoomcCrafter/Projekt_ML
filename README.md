# Poznań Air Quality Prediction 🌍

## 1. Temat i problem

Celem projektu jest stworzenie aplikacji wykorzystującej **Machine Learning do prognozowania jakości powietrza w Poznaniu**.

Problemem, który chcemy rozwiązać, jest brak łatwo dostępnej, lokalnej prognozy poziomu zanieczyszczenia powietrza. Dostępne systemy prezentują głównie aktualne lub historyczne pomiary, natomiast nasza aplikacja ma umożliwić przewidywanie przyszłego poziomu smogu.

Model będzie analizował historyczne stężenia pyłów PM2.5 i PM10 oraz dane meteorologiczne, takie jak temperatura, wilgotność, ciśnienie i prędkość wiatru.

Planujemy uwzględnić kilka stacji pomiarowych na terenie Poznania, umożliwiając użytkownikowi wybór interesującej go lokalizacji.

## 2. Dla kogo tworzymy aplikację?

Aplikacja będzie skierowana przede wszystkim do:

- **Mieszkańców Poznania**, którzy chcą monitorować i przewidywać jakość powietrza w swojej okolicy.
- **Osób aktywnych fizycznie**, np. biegaczy i rowerzystów, planujących aktywności na świeżym powietrzu.
- **Osób wrażliwych na zanieczyszczenia**, które chcą świadomie planować czas spędzany na zewnątrz.

## 3. Co aplikacja będzie zwracać użytkownikowi?

Po wybraniu lokalizacji w Poznaniu aplikacja docelowo wyświetli:

- **Prognozowane stężenie PM2.5 i PM10** na kolejną godzinę (µg/m³).
- **Ocenę jakości powietrza** na podstawie prognozowanych wartości.
- **Wykres zmian stężenia zanieczyszczeń** w czasie.
- **Prosty komunikat dla użytkownika** informujący o przewidywanej jakości powietrza.

## 4. Technologie i dane

- **Python** – przetwarzanie danych i tworzenie modeli ML.
- **Pandas, NumPy, Matplotlib** – analiza i wizualizacja danych.
- **Scikit-learn** – budowa i ocena modeli regresyjnych.
- **GIOŚ** – historyczne pomiary jakości powietrza w Poznaniu.
- **Open-Meteo** – historyczne dane meteorologiczne.

## 5. Plan realizacji

1. Zebranie danych dotyczących jakości powietrza i warunków pogodowych.
2. Eksploracyjna analiza danych (EDA) i czyszczenie zbioru.
3. Przygotowanie cech do modelu ML.
4. Trenowanie i porównanie modeli regresyjnych.
5. Ocena skuteczności prognoz.
6. Przygotowanie prostego interfejsu aplikacji umożliwiającego wybór lokalizacji i wyświetlenie prognozy.
