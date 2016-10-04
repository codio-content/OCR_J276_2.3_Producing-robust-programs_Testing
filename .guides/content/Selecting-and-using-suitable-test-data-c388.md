When testing is being planned and carried out a **testing plan** should be written including the data to be used, the expected results, the actual results and the corrective action taken.
The types test data should include:

**Valid test** where expected input is used. This ensures that the correct result will be produced with the expected data (sometimes called an ‘in-range test’)

**Boundary test** where the highest or lowest acceptable numbers and those just outside the acceptable range are entered. These check any logical errors that might have been introduced using the <= and >= operators.

**Erroneous test** where data that should be rejected are deliberately input to check that validation routines are functioning as expected (sometimes called an ‘out-of-range test’)

An example of a test plan is shown below to test part of a program where a user is asked to enter the month of their birth as a number:

|Test number  | Test data| Expected result| Actual result| Type of test|
| :------ | :----------- |:----------- |:----------- |:----------- |
| 1 | 9 |Accepted |Accepted |Valid or in-range test |
| 2 | 1 |Accepted |Accepted |Boundary test |
| 3 | 11 |Accepted |Accepted |Boundary test |
| 4 | 13 |Message saying that the entry should be between 1 and 12 |Message displayed as expected |Erroneous test|
