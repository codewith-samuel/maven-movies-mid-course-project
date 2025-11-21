# Maven Movies MySQL Analysis  
### Maven Analytics – MySQL for Data Analysis Bootcamp  
**Mid-Course Project | November 2025**

![Maven Movies ERD](mavenmoviesERD.png)

## Project Overview
This repository contains my solutions to the mid-course project in the **Maven Analytics MySQL for Data Analysis** bootcamp.  
The goal was to write clean, efficient SQL queries to answer 8 real-world business questions about the Maven Movies DVD rental company using the `mavenmovies` database.

## Database
- Classic DVD rental schema (Sakila-inspired)
- 16 tables: `film`, `inventory`, `rental`, `customer`, `payment`, `staff`, `store`, etc.
- Full database creation + data script included (`mavenmovies_database.sql`)

## Business Questions Answered
| # | Question | Key Insight (from my results) |
|---|-------------------------------------------------------------|-------------------------------|
| 1 | List all staff members with name, email, and store ID | Only 2 staff members (Mike & Jon) |
| 2 | Inventory count per store | Store 1: 9,160 items │ Store 2: 8,933 items |
| 3 | Active customers per store | Store 1: 326 active │ Store 2: 273 active |
| 4 | Total customer emails stored (data-breach liability) | 599 emails |
| 5 | Unique film titles per store + total unique categories | Store 1: 3,567 titles │ Store 2: 3,581 titles │ **16 unique categories** |
| 6 | Cheapest / most expensive / average film replacement cost | $9.99 / $29.99 / ~$20.23 |
| 7 | Average & maximum payment processed | ~$4.20 average │ $11.99 max |
| 8 | Customer ranking by lifetime rentals (top loyal customers) | Top customer: Eleanor Hunt – **46 rentals** |

## Files in This Repository
- `mavenmovies_database.sql` → Full database schema + data (run this first)
- `solutions.sql` → All 8 queries with clear comments
- `mavenmoviesERD.png` → Entity Relationship Diagram (visual schema)
- `results/` → Screenshots of key query outputs (optional but included)

## How to Run
1. Create a new database in MySQL Workbench
2. Run `mavenmovies_database.sql`
3. Open and execute `solutions.sql`

## Skills Demonstrated
- SELECT, GROUP BY, aggregate functions (COUNT, AVG, MIN, MAX)
- Filtering (WHERE), sorting (ORDER BY), aliases
- Writing readable, commented, production-style SQL
- Understanding relational database schemas

Feel free to clone, fork, or use as a reference!  
Questions or suggestions? Open an issue or reach out – happy to discuss SQL or data analysis.

Made with ❤️ while leveling up my analyst skills.
