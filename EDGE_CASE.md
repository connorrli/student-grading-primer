# Document your edge case here
- To get marks for this section you will need to explain to your tutor:
1) The edge case you identified
    - If no students, then pulling stats will result in divide by 0 for average, and there will be no marks.

2) How you have accounted for this in your implementation
    - If number of marks == 0, then return a json object containing null values (None in python).