**SQL Tasks**

This document outlines the instructions for completing five SQL tasks:

**Task 1: Extract Year, Month, and Day from Date Attribute**

1. Write an SQL query that extracts the year, month, and day from the `date` attribute in the `orders` table.
2. Display the extracted values as three separate attributes alongside the `id` attribute and the original `date` attribute (resulting in a total of five attributes).

**Task 2: Add One Day to Date Attribute**

1. Write an SQL query that adds one day to the `date` attribute in the `orders` table.
2. Display the `id` attribute, the original `date` attribute, and the result of adding one day.

**Task 3: Display Date as Timestamp in Seconds**

1. Write an SQL query that displays the `date` attribute in the `orders` table as the number of seconds since the epoch (timestamp).
2. To achieve this, identify and apply the appropriate function.
3. Display the `id` attribute, the original `date` attribute, and the result of the function.

**Task 4: Count Orders within a Specific Date Range**

1. Write an SQL query that counts the number of rows in the `orders` table where the `date` attribute falls within the range between 1996-07-10 00:00:00 and 1996-10-08 00:00:00.

**Task 5: Create JSON Objects from Order Data**

1. Write an SQL query that displays the `id` attribute, the `date` attribute, and a JSON object in the format {"id": <row id attribute>, "date": <row date attribute>} for each row in the `orders` table.
2. Utilize a function to create the JSON object.