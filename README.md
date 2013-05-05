Regular expressions engine from Java7 (1.7.0_21)

Ideas: 
1. Pattern should support the retrieval of the list of names of named groups
2. Possible support for repeated group value retrieval. 
   For example the pattern "((\\d+)(,\\s*)?)+" will match on string "10,15,20", with group2="20", but
   it is possible to get all values that matched the group2=[10, 15, 20]