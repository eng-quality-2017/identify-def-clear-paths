# identify-def-clear-paths

definition clear path - a path <i - n1 - … - nm – j>, m > 0, is a definition clear path with respect to variable x
from i to j
from i to edge (nm, j))
if x is neither defined or undefined in nodes n1, …, nm

1. Build a dictionary with key = type, value = list of strings(rows)
2. Find all data types in the unit (int, string...) and check if exists in dictionary
  2.1 if doesnt exist - add to the type in dictionary
  2.2 if exists - not added
3. Search any use (c-use \ p-use), if the row after 1 statement at least, we add to the dictionary
