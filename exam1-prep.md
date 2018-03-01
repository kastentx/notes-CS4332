# 1NF
First normal form enforces these criteria:
Eliminate repeating groups in individual tables.
Create a separate table for each set of related data.

# 2NF
A functional dependency on part of any candidate key is a violation of 2NF. In addition to the primary key, the relation may contain other candidate keys; it is necessary to establish that no non-prime attributes have part-key dependencies on any of these candidate keys.

# 3NF
A table is in 3NF if and only if both of the following conditions hold:
The relation R (table) is in second normal form (2NF)
Every non-prime attribute of R is non-transitively dependent on every key of R.

## Helpful Summary
Requiring existence of "the key" ensures that the table is in 1NF; requiring that non-key attributes be dependent on "the whole key" ensures 2NF; further requiring that non-key attributes be dependent on "nothing but the key" ensures 3NF. While this phrase is a useful mnemonic, the fact that it only mentions a single key means it defines some necessary but not sufficient conditions to satisfy the 2nd and 3rd Normal Forms. Both 2NF and 3NF are concerned equally with all candidate keys of a table and not just any one key.