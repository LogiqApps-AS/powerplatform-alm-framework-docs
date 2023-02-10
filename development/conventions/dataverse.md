# Dataverse

### Entities

Entities are always nouns. Each table has a singular and a plural name.

### Columns

Consistency and care in naming columns is important to both give clues about how they should be used as well as a clear way to understand what values they will contain.

### Related Columns

Related column logical names should be suffixed with `id`. As an example, a many-to-one relationship from a table called Measure to a table called Session might be `pub_sessionid`.

Relationship table names should be renamed to `pub_measure_N1_session`.

### Boolean Columns

Boolean columns are either true or false; yes or no, 1 or 0. They have only two states. Name your boolean columns with a verb, such as `IsActive` or `HasSales`.
