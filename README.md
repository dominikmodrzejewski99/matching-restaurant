# matchingRestaurant

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
