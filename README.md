aim: Study of Tuple in Python

theory: In this experiment we learned how to use tuple in python. 
Tuples are immutable, i.e. they cannot be edited whereas lists can be. 
Tuple use () brackets while lists use [] brackets. 
print(tpl[1]) displays the 2nd element of the tuple. 
print(tpl[1:4]) displays the 2nd, 3rd and 4th element of the tuple.
tpl7+=tpl8 adds element of tpl8 to tpl7 but changes the memory location of the tuple tpl7.
sorted(tuple) sorts the tuple in ascending order, but for lists we use list.sort().
tpl=(10,)*5 , printing this will print the value 10 five times.
id(tpl) , printing this will display the memory location of the tuple.

algorithm: 
a) Analyzing Student Marks
Initialize Data: Create a tuple containing the numerical marks of the students.[marks()]
Find Extremes: Identify the highest value using max() and the lowest value using min().
Count Entries: Determine the total number of students in the tuple using len().
Calculate Totals: Add all the marks together to find the sum using sum().
Calculate the Mean: Divide the sum by the total number of students to find the average (sum()/len()).
Organize Data: Use sorted() to display the marks in ascending order (Note: this creates a new list as tuples are immutable).
Display Results: Print the maximum, minimum, total count, sum, average, and sorted marks.

b) Unpacking Student Records
Initialize Record: Store a student's data (Subject, Marks, Grade) inside a single tuple.
Unpack Data: Assign the tuple values to three separate variables: subject, marks, and grade. (subject, marks, grade = result)
Evaluate Performance: Check if the marks variable is greater than or equal to 75.
Output Results: Print the individual variables and display "Distinction" if the condition is met.

c) Tracking Attendance
Initialize Attendance: Create a tuple (attendance) containing strings representing "P" (Present) and "A" (Absent).
Count Occurrences: Use the attendance.count() method to find the total number of "P" entries and "A" entries.
Check Absence: Use an if statement to check if the count of "A" is greater than or equal to 1.(if attendance.count("a")>=1:)
Display Results: Print the counts and a notification if the employee was absent at least once.

conclusion: Hence tuples were implemented in python and operations were done on them.
