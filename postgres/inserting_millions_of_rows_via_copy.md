## Inserting millions of rows via copy

If using `psql`, you can use the `copy` command to import a csv file into a table in your database. 

1. Build and export a csv where the headers of this csv match the column names of your table exactly. Let's say we have a `users` table with the fields `first_name`, `last_name`, `email`, and `created_at` and that our exporteds csv is titled `data.csv`
2. Find the url for your database and run `psql postgres://....` in your terminal
3. Run this command ``` \copy users(first_name,last_name,email,created_at) FROM './data.csv' DELIMITER ',' CSV HEADER;```

