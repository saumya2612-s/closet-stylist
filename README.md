# Closet Fashion Stylist (partial build)

## Included and tested
- `backend/app/recommendation_engine/`: colour harmony, fuzzy weather/formality, weighted scoring,
  genetic algorithm, Best Match / Explore / Mix It Up, repetition prevention, thumbs up/down learning
  (including multi-item negatives).
- `database/`: Supabase schema + migration with Row Level Security (NOT executed; no Postgres here).

## Not built yet
Frontend, auth/API routes, image uploads, calendar, trip planner, analytics, style profiles,
deployment config. No GitHub push was made.

## Run tests
    cd backend && pip install -r requirements.txt && python -m pytest -v

## Database
Paste `database/schema.sql` into the Supabase SQL editor. Keep service-role keys server-side only.
