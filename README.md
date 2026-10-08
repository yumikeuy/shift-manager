# ShiftMaster (shift-master)

System do automatycznego planowania grafików pracy dla małych biznesów handlowo-usługowych.

> **Projekt akademicki**  
> **Przedmiot:** Inżynieria Oprogramowania 1  
---

## 📌 O projekcie

**ShiftMaster** to aplikacja webowa/mobilna wspierająca zarządzanie zasobami ludzkimi w sektorze MŚP (np. kawiarnie, restauracje, małe punkty usługowe). Projekt rozwiązuje powszechny problem chaosu organizacyjnego związanego z ręcznym układaniem harmonogramów pracy, konfliktami dyspozycyjności oraz ciągłymi zmianami w zespole.

Głównym celem systemu jest automatyzacja procesu tworzenia optymalnego grafiku pracy na podstawie preferencji pracowników oraz wytycznych zdefiniowanych przez pracodawcę.

---

## 💡 Główne funkcjonalności

### 1. Panel Administratora / Menedżera
* Definiowanie ram czasowych okresu rozliczeniowego.
* Konfiguracja zmian (długość, godziny rozpoczęcia/zakończenia).
* Określanie zapotrzebowania na personel (minimalna/maksymalna liczba pracowników, wymagane role, np. barista, kucharz, kierownik zmiany).
* Zarządzanie bazą pracowników, rolami oraz limitami etatowymi.
* Publikacja i edycja wygenerowanych harmonogramów.

### 2. Panel Pracownika
* Wprowadzanie i edycja dyspozycyjności oraz preferencji godzinowych.
* Zgłaszanie urlopów i niedostępności.
* Podgląd aktualnego oraz nadchodzącego grafiku pracy.
* Otrzymywanie powiadomień o otwarciu okresu planowania i opublikowaniu nowego harmonogramu.

### 3. Moduł Automatycznego Harmonogramowania
* Algorytm optymalizujący przypisanie pracowników do zmian.
* Uwzględnianie ograniczeń twardych (*hard constraints*): limity kodeksowe, wymagana obsada stanowisk, odpoczynek dobowy/tygodniowy.
* Uwzględnianie ograniczeń miękkich (*soft constraints*): preferencje pracowników, sprawiedliwy podział weekendów/zmian popołudniowych.


## 🚀 Uruchomienie lokalne (w przygotowaniu)

```bash
# Sklonuj repozytorium
git clone [https://github.com/](https://github.com/)[użytkownik]/shift-master.git

# Przejdź do katalogu projektu
cd shift-master
