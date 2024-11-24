# Pokemon Data Analysis

This project provides tools and scripts to analyze Pokemon data using SQL and Python. It includes a database schema, helper scripts, and analytical queries to derive insights about Pokemon characteristics, encounters, and possible evolutions.

## Files
- **`PokemonDataAnalysis.dump.sql`**: PostgreSQL database dump that sets up the database schema.
- **`attack_damage`**: Stores results related to Pokemon attack calculations.
- **`encounter_summary`**: Summarizes Pokemon encounter data.
- **`helpers.py`**: Python helper functions for cleaning and formatting data inputs.
- **`helpers.sql`**: SQL script with utility functions for database operations.
- **`my_pokemon`**: Contains personalized Pokemon data.
- **`pokemon_density`**: Analyzes Pokemon density across various regions.
- **`possible_evolutions`**: Records potential evolution paths for Pokemon.

## Features
1. **Database Setup**: Initialize a PostgreSQL database with the given schema.
2. **Pokemon Analysis**:
   - Analyze Pokemon attack statistics.
   - Summarize Pokemon encounters.
   - Explore evolution possibilities and regional densities.
3. **Helper Functions**: Python and SQL utilities to enhance functionality.

## Technology Stack
- **Database**: PostgreSQL
- **Languages**: SQL, Python

## How to Use
1. Import the database schema:
   ```bash
   psql -U <username> -d <database_name> -f PokemonDataAnalysis.dump.sql
   ```
2. Use Python helper functions as needed:
   ```bash
   python helpers.py
   ```
3. Run SQL scripts for data analysis:
   ```bash
   psql -U <username> -d <database_name> -f helpers.sql
   ```

## Author
This project is part of the COMP3311 course. It is designed for educational purposes but can be adapted for broader data analysis needs.
