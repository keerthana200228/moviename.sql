-- create a table
CREATE TABLE movie (
  id INTEGER PRIMARY KEY,
  actor TEXT NOT NULL,
  director TEXT NOT NULL,
  year INTEGER NOT NULL,
  movie name TEXT NOT NULL
  
);
-- insert some values
INSERT INTO movie VALUES (1, 'samuthra kani', 'anabazhagan','2012','sattai');
INSERT INTO movie VALUES (2, 'suriya', 'gnanavel','2021','jai bhim');
-- fetch some values
SELECT * FROM movie
