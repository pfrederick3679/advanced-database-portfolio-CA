# Portfolio 1 — Database Design and Modelling

I organised the data into player, game, match, score. The design document explains the fields, keys, relationships and business rules. The normalisation document shows the sample tables at 1NF, 2NF and 3NF.

## Database checks

| Table | Rows |
| --- | --- |
| player | 2 |
| game | 2 |
| match | 2 |
| score | 2 |

The 29 invalid inserts were rejected at their expected constraints, and the valid sample rows remained unchanged.

## Files

- [Design](Design.md)
- [ER diagram](ERDiagram.md)
- [Normalisation](Normalisation.md)
- [Schema](Schema.sql)
- [Sample data](SampleData.sql)
- [Constraint tests](ConstraintTests.sql)
- [Table and constraint evidence](DatabaseResults.png)

## Run the SQL

Create a fresh PostgreSQL database. Run the schema first, then the sample data. Run the deliberately invalid statements in ConstraintTests.sql individually outside a transaction; each is expected to produce an error.

## References

- [PostgreSQL — constraints](https://www.postgresql.org/docs/17/ddl-constraints.html)

