# Sudoku
Next Hatmatz 06/08
### Edit 
- [x] generate(ILP)
### commonFunc
- [x] print_board
- [x] set (gets mode and decides if to update fixed) **Nevo**
- [X] undo **Or**
- [X] redo **Or**
- [x] num_solutions **Or**
- [x] reset **Nevo**
- [x] exit **Nevo**
- [x] validate(ILP)
- [x] save **Nevo**
- [x] load **Nevo**
- [x] solve **Nevo**
- [x] edit **Nevo**


### solve
- [ ] mark_errors **Or**
- [ ] guess (LP)
- [x] hint (ILP)
- [ ] guess_hint (LP)
- [x] autofill **Or**
  - [x] get_nei **Or**

### parser
- [x] user interface **Nevo**

#### Structs
- [x] Stack - for brute force solving (no recursion)
  - [x] Add clear_moves function (to completly clear the moves) - **Or**
  - [x] Add reset_moves function (to move back to first move) - **Or**
- [X] Double sided list - undo/redo **Or**
