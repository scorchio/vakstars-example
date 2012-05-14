# VAK stars example

This is an example Python application which tries to produce useful statistics for a real life game from an SQLite database.

The purpose of this application is to provide a good programming exercise for [Dorothie](http://github.com/Dorothie) to
play around.

### The goal is the following:

- Connect to the *vakstars.sqlite* SQLite database from a new Python script called *stats.py*.
- Based on command line arguments, print out various statistics in natural Hungarian language. 
- Every statistic should be based on a time interval given as a command line argument. The intervals which should be implemented are *"daily"*, *"weekly"* and *"monthly"*. 
- The needed statistics are:
    - List all persons who didn't get a vote in the given interval. (Result should be a list of names.)
    - List the top 5 persons who got the most votes in the given interval. (Result should be a list of pairs of names and number of votes.)
    - List the top 5 persons who gave the most votes in the given interval. (Result should be a list of pairs of names and number of votes.)
    - List the top 5 persons who got the most votes in the given interval - based on their number of votes in the previous interval. (Result should be a list of pairs of names and a percentage value.)
    - List the top 5 persons who gave the most votes in the given interval - based on their number of votes in the previous interval. (Result should be a list of pairs of names and a percentage value.)
- Where percentage values are expected, negative percentages should be handled correctly. For example we would like to be able to display someone in the top 5 even if their votes are -37% compared to the previous interval.

### For starting out:

- [The official Python documentation](http://www.python.org/doc/) is a great place for Python-related information.
- You can find the [best Git book online here](http://progit.org/book/). I might be biased a bit, bit still, this is a
great book.
- Try to use *Sqliteman* for opening and studying the database.
- *PyCharm* is my recommended IDE for Python, but it's by no means necessary for completing the exercise.
- Read the example code - which handles the basic management of the database - in *vakstars.py*.
- Use the [issue tracker of this GitHub project]
(https://github.com/scorchio/vakstars-example/issues) for asking questions or to report (highly possible) bugs in the example code. Assign the issue to *scorchio* and don't forget to set the label of the issue properly.


