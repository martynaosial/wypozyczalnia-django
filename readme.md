# Wypożyczalnia: aplikacja Django + REST API

Projekt z przedmiotu „Projektowanie aplikacji webowych”: aplikacja wypożyczalni w Django z REST API (Django REST Framework), kontami użytkowników i rolami.

*EN: Course project: a rental-service web app in Django with a REST API, user accounts and roles.*

## Co jest w projekcie
- **Modele danych:** użytkownik z rolą (własny model `User`), kategorie, produkty (z właścicielem i dostępnością), wypożyczenia ze statusem i datą.
- **REST API:** lista i szczegóły produktów, produkty w kategorii, wyszukiwanie, wypożyczenia, miesięczny raport wypożyczeń i usuwanie produktów (dwie ostatnie tylko dla administratora).
- **Uwierzytelnianie i uprawnienia:** tokeny i sesje; osobne uprawnienia dla użytkowników i administratorów.
- **Widoki HTML:** rejestracja, logowanie, lista i szczegóły produktów, własny CSS.

## Technologie
Python, Django, Django REST Framework, SQLite.

## Uruchomienie
```
cd folder_projekciku
pip install django djangorestframework
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

## Autorki
- Julia Napora
- Martyna Osial
