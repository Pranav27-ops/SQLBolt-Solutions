# Lesson 1: SELECT Queries

## Exercise 1 — Tasks

### Task 1: Find the `title` of each film
**Question:** Select only the title column from the Movies table.

**Solution:**
```sql
SELECT title FROM Movies;
```

**Expected Output:**
- Toy Story
- A Bug's Life
- Toy Story 2
- Monsters, Inc.
- Finding Nemo
- The Incredibles
- Cars
- Ratatouille
- WALL-E


---

### Task 2: Find the `director` of each film
**Question:** Select only the director column from the Movies table.

**Solution:**
```sql
SELECT director FROM Movies;
```

**Expected Output:**
- John Lasseter
- John Lasseter
- John Lasseter
- Pete Docter
- Andrew Stanton
- Brad Bird
- John Lasseter
- Brad Bird
- Andrew Stanton



---

### Task 3: Find the `title` and `director` of each film
**Question:** Select both the title and director columns from the Movies table.

**Solution:**
```sql
SELECT title, director FROM Movies;
```

**Expected Output:**
| Title | Director |
|-------|----------|
| Toy Story | John Lasseter |
| A Bug's Life | John Lasseter |
| Toy Story 2 | John Lasseter |
| Monsters, Inc. | Pete Docter |
| Finding Nemo | Andrew Stanton |
| The Incredibles | Brad Bird |
| Cars | John Lasseter |
| Ratatouille | Brad Bird |
| WALL-E | Andrew Stanton |



---

### Task 4: Find the `title` and `year` of each film
**Question:** Select the title and year columns from the Movies table.

**Solution:**
```sql
SELECT title, year FROM Movies;
```

**Expected Output:**
| Title | Year |
|-------|------|
| Toy Story | 1995 |
| A Bug's Life | 1998 |
| Toy Story 2 | 1999 |
| Monsters, Inc. | 2001 |
| Finding Nemo | 2003 |
| The Incredibles | 2004 |
| Cars | 2006 |
| Ratatouille | 2007 |
| WALL-E | 2008 |



---

### Task 5: Find `all` the information about each film
**Question:** Select all columns from the Movies table.

**Solution:**
```sql
SELECT * FROM Movies;
```

**Expected Output:**
All columns (Id, Title, Director, Year, Length_minutes) for all films



---


