#Test Plan
| Test ID | Description | Expected Input | Expected Output | Actual Output | Pass/Fail |
| --- | --- | --- | --- | --- | --- |
| TID_01 | Player 1 wins | Player 1, enter a number :5,Player 2, enter a number :2,Player 1, enter a number :1,Player 2, enter a number :3,Player 1, enter a number :9 | Player 1 win | Player 1 win | Pass |
| TID_02 | Player 2 wins | Player 1, enter a number :2,Player 2, enter a number :3,Player 1, enter a number :4,Player 2, enter a number :6,Player 1, enter a number :5,Player 2, enter a number :9 | Player 2 win | player 2 win | Pass
| TID_03 | Invalid move | Player 1, enter a number :4,Player 2, enter a number :2,Player 1, enter a number :2 | Invalid Move | Invalid Move | Pass |
| TID_04 | Draw | Player 1, enter a number :5,Player 2, enter a number :3,Player 1, enter a number :2,Player 2, enter a number :8,Player 1, enter a number :4,Player 2, enter a number :6,Player 1, enter a number :7,Player 2, enter a number :1,Player 1, enter a number :9 | Game Draw | Game Draw | Pass |
| TID_05 | Player 2 wins | Player 1, enter a number :3,Player 2, enter a number :7,Player 1, enter a number :5,Player 2, enter a number :8,Player 1, enter a number :6,Player 2, enter a number :9 | Player 2 win | Player 2 win | Pass |
| TID_06 | Player 1 wins | Player 1, enter a number :1,Player 2, enter a number :5,Player 1, enter a number :4,Player 2, enter a number :9,Player 1, enter a number :7 | Player 1 win | Player 1 win | Pass |
| TID_07 | Giving float values | Player 1, enter a number :1,Player 2, enter a number:5.5 | Invalid Move | Player 1,enter a number: Invalid move | Fail |

