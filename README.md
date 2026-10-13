# Healthcare Data Analysis using MySQL

34 SQL queries answering business questions on a hospital database (patients, admissions, doctors, provinces).

## Tools
MySQL

## SQL concepts used
- Multi-table `INNER JOIN` (patients, admissions, doctors, province names)
- `UNION ALL`, `GROUP BY` with `HAVING`, subqueries
- `CASE WHEN` (obesity flag from BMI, gender counts), weight-group bucketing
- String functions (`CONCAT`, `UPPER`, `LOWER`, `LIKE`) and date functions (`YEAR`, `DAY`)
- Data cleaning with `UPDATE` (replacing NULL allergies)

## Example questions solved
- Patients admitted multiple times for the same diagnosis
- Patients grouped into weight bands with counts
- Epilepsy patients treated by a doctor named Lisa, with the doctor's specialty
- Provinces whose total patient height is at least 7,000

## Files
- `sql/healthcare_queries.sql` all queries with the question as a comment above each
