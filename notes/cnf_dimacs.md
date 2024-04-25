# DIMACS
- Can have comments at top, lines start with c
- Next is problem line, starts with **p**
    - `p cnf 3 4`: CNF problem with 3 vars and 4 clauses
- Rest of file is clauses
    - List of numbers, each number is an $X_i$
    - Can be negated
- Number 0 marks the end of each clause, so **clauses can be split over multiple lines**

