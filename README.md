AIM: Study of Tuple in Python
Theory:
The difference between a list and a tuple are: lists are mutable, allowing for the modification, addition, or removal of elements after creation using square brackets [], whereas tuples are immutable, meaning their contents cannot be changed once defined using parentheses (). Because of this fixed nature, tuples are generally more memory-efficient and faster for iteration, making them ideal for protecting data that should remain constant throughout a program. Conversely, lists are better suited for collections of data that require frequent updates. Additionally, tuples can be used as keys in dictionaries or elements in sets because they are hashable, whereas lists cannot. For deeper technical specifications, you can consult the official Python documentation on sequence types.

ALGORITHM:

Tuple of Exam Result-

Start
Initialize a tuple result with ("Maths", 97, "A+").
Unpack the elements of result to variables sub, marks, and grade.
Output the values of sub, marks, and grade.
If marks (\ge 75), then print "Distinction".
Stop.

Tuple of Employee's Attendance for a week-

Start
Initialize a tuple attendance with values ("p", "a", "p", "a", "p", "a", "p").
Count the occurrences of "p" in attendance and display the result.
Count the occurrences of "a" in attendance and display the result.
If "a" exists in the attendance tuple, print "The employee was absent at least once".
Stop.
