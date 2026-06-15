# System Zarządzania Teatrem - Relacyjna Baza Danych

## Opis projektu
Projekt obejmował zaprojektowanie od podstaw relacyjnej bazy danych dla systemu ewidencji spektakli i sprzedaży biletów oraz stworzenie aplikacji webowej w środowisku Oracle APEX.

## Technologie i narzędzia
* Środowisko: Oracle APEX
* Baza danych: Oracle Database
* Narzędzia: SQL Developer
* Języki: SQL, PL/SQL

## Kluczowe funkcjonalności
* Zaprojektowanie struktury tabel, relacji oraz więzów integralności.
* Implementacja logiki biznesowej i walidacji danych przy użyciu SQL i PL/SQL.
* Stworzenie funkcjonalnego interfejsu użytkownika w Oracle APEX.

## Podgląd interfejsu aplikacji (Oracle APEX)

### 1. Panel Główny (Dashboard) i Moduły Systemu
Ekran startowy prezentujący kluczowe wskaźniki finansowe (łączny przychód, sprzedane bilety) oraz dający dostęp do głównych modułów operacyjnych teatru.

<img width="1888" height="984" alt="Zrzut ekranu 2026-01-06 190821" src="https://github.com/user-attachments/assets/a0dac360-120c-4be3-b582-f199ac41730f" />


### 2. Kalendarz Repertuaru
Dynamiczny widok kalendarza pobierający dane bezpośrednio z bazy, umożliwiający podgląd zaplanowanych spektakli w danym miesiącu.

<img width="1531" height="807" alt="Zrzut ekranu 2026-01-06 230527" src="https://github.com/user-attachments/assets/5bb9b5c0-b2c0-416b-b84b-53d3e988b763" />


### 3. Generowanie Biletów i Obsługa Kasowa
Moduł sprzedażowy, który po udanej transakcji aktualizuje liczbę dostępnych miejsc w bazie i generuje gotowy do druku bilet z kodem QR.

<img width="910" height="842" alt="Zrzut ekranu 2026-01-06 191332" src="https://github.com/user-attachments/assets/58bd295f-8afc-4b26-9860-91bd1d8bc30d" />


### 4. Zarządzanie Obsadą i Logika Biznesowa
Formularze pozwalające na przypisywanie pracowników (np. aktorów, reżyserów, charakteryzatorów) do konkretnych spektakli, z wbudowaną walidacją i powiadomieniami o sukcesie operacji.

<img width="805" height="518" alt="Zrzut ekranu 2026-01-05 195724" src="https://github.com/user-attachments/assets/ac756287-4b7c-490b-bab9-2c03e8534a2b" />

