# SafePath - Backend API

## Application Database

**Application DB Connection String:** `postgresql://db_appdb_69b2ce5c7233c9d357dbbf8b_user:F5X9h%5EtVCTQW1n9B%2AQQUM%25Z%241%5Edov3Pj@ep-ancient-sea-adx5pkkp.c-2.us-east-1.aws.neon.tech:5432/AppDB_69b2ce5c7233c9d357dbbf8b?sslmode=require`

**Swagger API Tester URL:** /swagger

## Google APIs (Gemini, Maps, Speech-to-Text)

The backend can use a Google API key provided via the **GOOGLE_API_KEY** environment variable (set on Railway). Use it for Gemini LLM, Maps, and Speech-to-Text. Check **GET /api/google/status** and **GET /api/google/health** to verify the key is set and reachable.

## Recommended Tools

**Recommended SQL Editor tool (Free):** [pgAdmin](https://www.pgadmin.org/download/)

## Deployment

This backend is configured for Railway deployment using nixpacks.toml.
