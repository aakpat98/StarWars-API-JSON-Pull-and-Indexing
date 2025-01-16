# Star Wars API Data Integration

This project demonstrates how to retrieve data from the Star Wars API (SWAPI) and store it in a PostgreSQL database for efficient querying and analysis.

## Overview

The Star Wars API provides a wealth of information about the Star Wars universe in JSON format. This project involves fetching that data using Python, processing it, and inserting it into a PostgreSQL database. Once the data is stored, SQL is used to create indexes and perform queries to efficiently retrieve information.

```bash
python swapi.py
```

This script will:

- Fetch data from SWAPI.
- Process and normalize the JSON data.
- Insert the data into corresponding PostgreSQL tables.

## Database Schema

The database consists of tables corresponding to different entities from the Star Wars universe, such as:

- `people`
- `planets`
- `starships`
- `vehicles`
- `species`
- `films`

Each table is structured to store relevant attributes provided by SWAPI.

## Indexing and Querying

After populating the database, you can create indexes to optimize query performance. The `SQL Queries.sql` file contains sample SQL queries for indexing and data retrieval.

## Notes

- Ensure that SWAPI is accessible from your environment.
- Handle exceptions and errors gracefully to avoid interruptions during data fetching and insertion.
- Regularly update the data to reflect any changes or additions to SWAPI.

## Resources

- [Star Wars API Documentation](https://swapi.dev/)
- [PostgreSQL Documentation](https://www.postgresql.org/docs/)

## License

This project is licensed under the MIT License.

---

By following this guide, you can successfully integrate data from the Star Wars API into a PostgreSQL database, enabling efficient storage and querying for your applications. 
