# Predykcja i analiza cen samochodów

Ten projekt przewiduje ceny samochodów na podstawie różnych cech przy użyciu modeli uczenia maszynowego.

📌 Funkcje

- Przygotowanie i inżynieria cech danych
- Trenowanie i ocena modelu

## 🛠 Konfiguracja środowiska

Aby skonfigurować projekt, wykonaj następujące kroki:

1️⃣  Sklonuj Repozytorium

```sh
git clone https://github.com/GameRuiner/Car-Price-Prediction.git
cd Car-Price-Prediction
```

2️⃣ Utwórz i aktywuj środowisko wirtualne

Na Windows (PowerShell):

```sh
python -m venv .venv
.venv\Scripts\Activate
```

Na macOS/Linux:

```sh
python3 -m venv .venv
source .venv/bin/activate
```

3️⃣ Zainstaluj wymagane biblioteki

```sh
pip install -r working/notebooks/requirements.txt
```

## 📦 Zależności

Aby automatycznie wygenerować plik requirements.txt zawierający wszystkie używane w notebookach pakiety Pythona, uruchom:

```sh
pipreqs --scan-notebooks --force  working/notebooks
```

## 📜 Licencja

Ten projekt jest licencjonowany na zasadach licencji MIT.
