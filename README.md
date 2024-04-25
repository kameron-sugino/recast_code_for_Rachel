# recast_code_for_Rachel
Takes a wide format table (samples on rows, and groups, variables, etc. on columns) and pivots it such that groups are on columns and variables on rows. In the example data, after reading in the file, we want to reshape our data based on Group and Diet, so we select those under group. Since we only want to pivot on the group and data, we select ID, Group, and Diet in the remove dropdown to leave us with only the refactored group ID and the data to pivot. 

To use the app [Click Here](https://kameron-sugino.shinyapps.io/recast_table/)
