# FoodMood

![Angular](https://img.shields.io/badge/Angular_19-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel_11-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![PHP](https://img.shields.io/badge/PHP_8.2-777BB4?style=for-the-badge&logo=php&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![NgRx](https://img.shields.io/badge/NgRx-BA2BD2?style=for-the-badge&logo=ngrx&logoColor=white)
![PrimeNG](https://img.shields.io/badge/PrimeNG-007ACC?style=for-the-badge&logo=primeng&logoColor=white)
![Monorepo](https://img.shields.io/badge/Monorepo-143055?style=for-the-badge)

Aplikacja rozwiązująca odwieczny problem: **"chcemy coś zjeść, ale nie wiemy co"**.

Użytkownik przechodzi krótki quiz dotyczący nastroju, preferencji smakowych i okoliczności posiłku, a na końcu otrzymuje dopasowane propozycje gastronomiczne — co zjeść i gdzie.

## Jak to działa

1. Użytkownik startuje quiz
2. Odpowiada na pytania (np. rodzaj kuchni, ostrość, czas oczekiwania, budżet)
3. Algorytm dopasowuje propozycje na podstawie odpowiedzi
4. Wyświetlane są rekomendacje gastronomiczne (potrawy / restauracje)

## Struktura repo

- `frontend/` — aplikacja Angular (UI quizu i wyników)
- `backend/` — API w PHP (logika dopasowania, dane o potrawach/restauracjach)

## Uruchomienie

### Frontend

```bash
cd frontend
npm install
npm start
```

### Backend

```bash
cd backend
composer install
```
