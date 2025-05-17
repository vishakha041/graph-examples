# graph-examples


## Ingestion.
All the movies from TMDB dataset are converted into connected nodes with the schema
```mermaidjs
erDiagram
    MOVIE }o--o{ PERSON : CAST
    MOVIE }o--o{ PERSON : CREW
```

## Queries.

## Visualization
Using a library called Jaal