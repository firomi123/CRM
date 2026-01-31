# Mini CRM --- Specyfikacja Projektu

## 🎯 Cel projektu

Stworzenie lekkiego systemu **Mini CRM** do zarządzania: - leadami sprzedażowymi

Aplikacja skupia się na szybkości działania, prostocie i lokalnym
przechowywaniu danych.

------------------------------------------------------------------------

## 📌 Główne funkcjonalności

### 🧩 Zarządzanie Leadami

-   Przypisywanie leadów do firm i kontaktów

### 📊 Kanban Leadów

-   Widok tablicy Kanban
-   Przeciąganie kart między statusami (drag & drop)
-   Statusy przykładowe:
    -   Nowy
    -   W trakcie
    -   Oferta wysłana
    -   Wygrany
    -   Przegrany

------------------------------------------------------------------------

## 🔍 Smart Search

Wyszukiwarka globalna obejmuje: - leady - firmy - kontakty - tagi

Funkcje: - wyszukiwanie pełnotekstowe
------------------------------------------------------------------------

## 📥 Import CSV Leadów

Możliwości: - import danych z pliku CSV - mapowanie kolumn - walidacja
danych przed zapisem - podgląd danych przed importem

------------------------------------------------------------------------

## 💾 Przechowywanie danych

### Opcja podstawowa

-   Local Storage
-   szybka implementacja
-   brak backendu

### Opcja rozszerzona

-   IndexedDB
-   większa skalowalność
-   lepsza wydajność przy większej ilości danych

------------------------------------------------------------------------

## 🧪 Testy

Zakres testów: - parser CSV - walidacje danych - wyszukiwarka (search
engine) - logika Kanban

------------------------------------------------------------------------

## 🛠 Stack technologiczny

### Frontend

-   Vite
-   React
-   TypeScript

### UI

-   Tailwind CSS
-   opcjonalnie shadcn/ui

### Drag & Drop

-   @dnd-kit/core
-   @dnd-kit/sortable

### Testowanie

-   Vitest

