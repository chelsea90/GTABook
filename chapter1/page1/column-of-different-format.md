### Column of different format

Files location:[http://192.168.18.60/Chelsea/GraphingTesting/tree/master/ColumnOfDifferentFormat](http://192.168.18.60/Chelsea/GraphingTesting/tree/master/ColumnOfDifferentFormat)

TestCase 1:

| Type id | Type name | Case id | Case description | Test data | Expected results |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | Text, numeric&categorical | 1 | Text in X | Fill row numbers | Plot Correct |
|  |  | 2 | Text in Y | Fill row numbers | Plot Correct |
|  |  | 3 | both X and Y columns | Fill row numbers | Plot Correct |
|  |  | 4 | column properties: text & numeric |  | Plot Correct |
|  |  | 5 | column properties: Text |  | Plot Correct |
|  |  | 6 | right click column to set as Categorical or not |  | Plot Correct |

TestCase 2:

| Type id | Type name | Case id | Case description | Test data | Expected results |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 2 |  | 1 | mixed text and numeric data in X | Fill row numbers | Plot Correct |
|  |  | 2 | mixed text and numeric data in Y columns | Fill row numbers | Plot Correct |

note: When making plot from such X column, tick label will be Text from Dataset if half of the range is text.

TestCase 3:

| Type id | Type name | Case id | Case description | Test data | Expected results |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 3 |  | 1 | Linked data plotting \(for different plot type） | Fill row numbers | Plot Correct |
|  |  |  | Linked data plotting \(grouped plot） | Fill row numbers | Plot Correct |



