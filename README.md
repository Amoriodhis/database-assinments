# da--  Answer 1
CREATE TABLE student (
    id INT PRIMARY KEY,
    fullName VARCHAR(100),
    age INT
);

--  Answer 2
INSERT INTO student (id, fullName, age) VALUES
(1, 'Alice Johnson', 19),
(2, 'Bob Smith', 18),
(3, 'Charlie Brown', 21);

--  Answer 3
UPDATE student 
SET age = 20 
WHERE id = 2;tabase-assinments
