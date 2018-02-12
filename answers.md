W3 D1 Homework Answers

Questions

1) Return ALL the data in the 'movies' table.

SELECT * FROM movies;

2) Return ONLY the name column from the 'people' table

SELECT name FROM people;

3) Oops! Someone at CodeClan spelled Kate's name wrong! Change it to reflect the proper spelling (change 'Kte Preston' to 'Kate Preston').

UPDATE people
SET name = 'Kate Preston'
WHERE name = 'Kte Preston';

4) Return ONLY your name from the 'people' table.

SELECT name FROM people
WHERE name = 'Verity Ashforth';

5) The cinema is showing 'Batman Begins', but Batman is DC, not Marvel! Delete the entry from the 'movies' table.

DELETE FROM movies
WHERE title = 'Batman Begins';

6) Create a new entry in the 'people' table with the name of one of the instructors.

INSERT INTO people (name) VALUES ('Finn Porter');

7) Jarrod Bennie, has decided to hijack our movie evening, Remove him from the table of people.

DELETE FROM people
WHERE name = 'Jarrod Bennie';

8) The cinema has just heard that they will be holding an exclusive midnight showing of 'Guardians of the Galaxy 2'!! Create a new entry in the 'movies' table to reflect this.

INSERT INTO movies (title, year, show_time) VALUES ('Guardians of the Galaxy 2', 2017, '00:00');

9) The cinema would also like to make the Guardian movies a back to back feature. Update the 'Guardians of the Galaxy' show time from 14:05 to 21:30

UPDATE movies
SET show_time = '21:30'
WHERE title = 'Guardians of the Galaxy';
