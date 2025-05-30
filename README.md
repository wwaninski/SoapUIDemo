# 📌 Reqres REST API Test Project

Ten projekt zawiera zestaw testów REST API dla [Reqres.in](https://reqres.in), przygotowanych w **SoapUI**. 

## 🚀 Instalacja

Aby uruchomić projekt, wykonaj poniższe kroki:

1. Pobierz i zainstaluj **SoapUI** ([Download SoapUI](https://www.soapui.org/downloads/)).
2. Pobierz plik projektu `reqres-soapui-project.xml`.
3. Uruchom **SoapUI**.
4. Wybierz **File → Import Project**.
5. Wskaż pobrany plik `reqres-soapui-project.xml`.
6. Kliknij **Open**, aby zaimportować projekt.

## 📂 Struktura projektu

Projekt zawiera następujące komponenty:
- **Test Suite:** `Reqres Test Suite`
- **Test Case'y:**
  - `Get Users` – pobranie listy użytkowników.
  - `Create User` – utworzenie nowego użytkownika.
  - `Update User` – edycja istniejącego użytkownika.
  - `Authentication Test` – testowanie logowania.

## 🛠 Właściwości i skrypty Groovy

Projekt wykorzystuje dynamiczne zmienne i skrypt **Groovy**, którry pozwala na przetransferowanie danych z odpowiedzi REST do requesta PUT.
