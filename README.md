MovieAnalyzer Project
Overview
The MovieAnalyzer project is a Python 3 program designed to analyze and display movie data from a CSV file. The program reads a dataset containing movie titles, release years, and ratings, then provides users with a menu-driven interface to explore the data through various sorting and statistical operations.

Features
User Prompt for File Input: The program prompts the user to enter the path to the CSV file containing movie data.

Data Parsing & Error Handling: The CSV file is read and processed into a structured format, converting years to integers and ratings to floating-point values. The program handles corrupt or missing data gracefully.

Summary Statistics: The program calculates and displays key statistics, including:

Average movie rating

Highest-rated movie(s)

Lowest-rated movie(s)

Total number of movies in the dataset

Sorting Options: Users can choose to:

Display movies sorted by rating in descending order.

Display movies sorted by year in ascending order.

User-Friendly Interface: The menu is structured for easy navigation, and information is displayed in a well-formatted manner.

Exit Option: The user can exit the program at any time by selecting the appropriate menu option.

Implementation Details
The program utilizes Python’s csv module to read and parse the dataset efficiently.

A list of dictionaries is used to store movie data in memory, ensuring quick access and manipulation.

Sorting is implemented using Python’s built-in sorting functions for optimal performance.

The program follows best practices in coding structure and formatting for readability and maintainability.
