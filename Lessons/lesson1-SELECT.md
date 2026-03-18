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

**Explanation:** 
- Use `SELECT` to retrieve data
- Specify the column name (`title`) to get only that column
- `FROM Movies` tells the database which table to query

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

**Explanation:**
- Similar to Task 1, but selecting the `director` column
- You can select any specific column by name

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

**Explanation:**
- To select multiple columns, separate them with commas
- The order matters: `SELECT title, director` will return title first, then director
- You can select as many columns as you need

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

**Explanation:**
- Here we select `title` and `year` columns
- You can see how to combine different columns in one query

---

### Task 5: Find `all` the information about each film
**Question:** Select all columns from the Movies table.

**Solution:**
```sql
SELECT * FROM Movies;
```

**Expected Output:**
All columns (Id, Title, Director, Year, Length_minutes) for all films

**Explanation:**
- The asterisk `*` is a wildcard that means "all columns"
- `SELECT *` is useful when you want everything
- This returns: Id, Title, Director, Year, Length_minutes

---

## Key Concepts

✅ **SELECT** - Retrieves data from a database
✅ **Column Names** - Specify which columns you want
✅ **Asterisk (*)** - Wildcard for all columns
✅ **Comma-separated** - Use commas to select multiple columns
✅ **FROM** - Specifies which table to query

---

## What I Learned

- SELECT is the most basic SQL command
- You can select one column, multiple columns, or all columns
- Column order matters in SELECT statements
- The * wildcard is very useful for quick queries
- Always remember the FROM clause to specify the table

---

## Common Mistakes to Avoid

❌ **Forgetting FROM clause** - Every SELECT needs to know which table
❌ **Typo in column names** - SQL is case-sensitive for column names
❌ **Missing comma between columns** - Must separate multiple columns with commas
❌ **Using SELECT without specifying columns** - This won't work (except with *)

---

## Practice Challenges

1. Try selecting just the `year` column
2. Select `title`, `director`, and `year` together
3. Select `id` and `length_minutes` columns
4. What happens if you try to select a column that doesn't exist?