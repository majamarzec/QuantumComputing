# Practical Quantum Computing ⚛️

Repozytorium zawiera materiały, notatniki (`.ipynb`) oraz implementacje przygotowane w ramach kursu **Practical Quantum Computing**.

## 📖 O kursie
Kurs oferuje praktyczne podejście do informatyki kwantowej. Głównym celem jest zrozumienie kluczowych koncepcji przetwarzania informacji kwantowej poprzez symulacje numeryczne oraz implementacje algorytmów.

**Zakres tematyczny:**
* Podstawowe modele obliczeń kwantowych.
* Bramki i obwody kwantowe.
* Splątanie (Entanglement) i pomiary (testowanie nierówności Bella).
* Wybrane algorytmy kwantowe (k-SAT, Adiabatic QC).
* Fizyczne ograniczenia sprzętu: szum i dekoherencja.

## 🛠 Technologie i Narzędzia
* **Język:** Python 3.11+
* **Framework:** [Qiskit](https://qiskit.org/)
* **Symulacje:** `AerSimulator` (lokalnie) oraz dostęp do systemów IBM Quantum.
* **Środowisko:** Jupyter Notebook.

## 🚀 Struktura projektu
Notatniki są ponumerowane zgodnie z kolejnością realizowanych zagadnień:
1. `01_hello_qubit.ipynb` – Wprowadzenie do pracy z qubitami.
2. `02_kSAT.ipynb` – Rozwiązywanie problemów spełnialności.
3. `03_adiabatic_QC.ipynb` – Adiabatyczne obliczenia kwantowe.
4. `04_run_simulator.ipynb` – Praca z symulatorami lokalnymi.
5. `05_bell.ipynb` – Implementacja testu Bella i nierówności CHSH.

## 📦 Instalacja
Aby odtworzyć środowisko lokalne, użyj dołączonego pliku `pyproject.toml`:

```bash
# Stwórz venv i zainstaluj zależności
python -m venv qiskit_venv
source qiskit_venv/bin/activate
pip install -e .