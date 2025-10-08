# Windows Reinstall & Backup Guide

Repozytorium zawiera prosty i bezpieczny zestaw instrukcji oraz skryptów pomagających przygotować backup i wykonać reinstalację Windows tak, aby nie utracić ważnych plików.

## Co znajdziesz w repo
- `CHECKLIST.md` — jedna strona do wydruku: co zrobić przed reinstalacją.
- `INSTALL.md` — krok-po-kroku: 3 metody reinstalacji (Reset keep files / In-place repair / Clean install).
- `backup/backup.ps1` — PowerShell script: kopiuje foldery użytkownika, eksportuje sterowniki i listę zainstalowanych programów.
- `docs/` — szczegółowe instrukcje i porady.

## Szybki start
1. Sklonuj repo:  
   `git clone https://github.com/TwojeUser/windows-reinstall-guide.git`
2. Przeczytaj `CHECKLIST.md`.
3. Uruchom PowerShell jako Administrator i wykonaj `backup/backup.ps1`.
4. Wybierz metodę z `INSTALL.md` i postępuj krok po kroku.

## Licencja
Plik `LICENSE` zawiera informacje o licencji (np. MIT).

## Kontakt / Contribution
Masz pomysł lub poprawkę? Otwórz issue lub pull request. Użyj szablonów `ISSUE_TEMPLATE.md` i `PR_TEMPLATE.md`.
