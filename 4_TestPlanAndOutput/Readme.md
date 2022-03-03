# Test plan

## High level test plan
|   ID   |     Description    |       Expected I/P      | Expected O/P | Actual O/P |  Type of test  |
| :----: | :----------------: | :---------------------: | :----------: | :--------: | :------------: |
|  H_01  |  View all the books|         N/A             |  1           |   1        | Scenario based |
|  H_02  |   Add a new book   | 20, "RICH DAD POOR DAD"     |  1           |   1        | Scenario based |
|  H_03  |   View a book      |          20            |  1           |   1        | Scenario based |
|  H_04  |   Update a book    |200,"issued","12/02/22","22/02/22","BHANU","PRAKASH",123 | 1 | 1 | Scenario based |
|  H_05  |   Delete a book    |          20            |   1          |      1     | Scenario based |

## Low level test plan
|   ID   |     Description    |       Expected I/P      | Expected O/P | Actual O/P |  Type of test  |
| :----: | :----------------: | :---------------------: | :----------: | :--------: | :------------: |
|  L_01  | ID and title of all the books can be seen |   N/A      |  1         |   1        | Scenario based |
|  L_02  |  To add a new book Enter it's details| 20, "RICH DAD POOR DAD" |    1         |    1       | Scenario based |
|  L_03  |  To Search a book enter its ID and check whether the book has been issued or not. If issued check the due date, the member to whom the book is issued. |          200            |       1      |     1      | Scenario based |
|  L_04  |  To update the status of a book. If issued or renewed, the due date as well as status should be updated | 20, "issued", "12/02/22", "23/02/22", "BHANU","PRAKASH", 123 | 1 | 1 | Scenario based |
|  L_05  |   This is used when a book is deleted.  |          20            |       1      |      1     | Scenario based |

