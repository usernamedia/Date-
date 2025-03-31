# Java Date Class Project

## Project Overview
As a beginner in Java, this project was an exciting challenge to implement a `Date` class that can handle various operations related to dates. The goal of this project was to create a `Date` class with fundamental functionality such as validating dates, updating them, calculating the day of the week, and sorting a list of `Date` objects.

This project covers the basics of object-oriented programming in Java, including the creation of classes, methods, and constructors. Through this project, I also gained experience in handling real-world scenarios like leap years and date differences, which are key when working with date-related applications.

### Key Features Implemented:
- **Date Validation (`isValidDate`)**: Ensures that a date is valid by checking if the day, month, and year fall within reasonable ranges. The validation also considers leap years, which is essential for handling dates like February 29.
  
- **Update Date (`updateDate`)**: Allows updating the day, month, and year attributes of the `Date` object, but only after validating that the new date is valid.

- **Day of the Week (`getDayOfWeek`)**: Returns the name of the day (e.g., "Monday", "Tuesday") for any given date. This involved using Java's built-in `Calendar` class.

- **Date Difference (`calculateDifference`)**: Computes the difference (in days) between two `Date` objects. This is done by converting the dates into `Calendar` objects and calculating the difference in milliseconds.

- **Sorting Dates (`compareTo`)**: Implements the `Comparable<Date>` interface to allow sorting a list of `Date` objects in ascending order based on the year, month, and day.

### Why This Project Was Valuable:
- **Real-World Application**: Working with dates is a fundamental part of many real-world applications, and this project provided me with a solid understanding of how to handle them in Java.
  
- **Hands-on Learning**: As a beginner, implementing the `Date` class from scratch helped me understand how to structure a class, write methods, and apply Java's built-in libraries effectively.

- **Challenges and Learning**: 
    - One of the biggest challenges was handling leap years and ensuring the validation method could correctly identify valid and invalid dates, such as February 29 on non-leap years.
    - I also learned how to use the `Comparable` interface to sort objects in Java, which I had not previously worked with.
