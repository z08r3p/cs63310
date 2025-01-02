java cXMUM.OAA - 100/2/8-V3.0 Page | 3
F. Task(s)
Consider the graph in Figure 1, each vertex is representing a place to visit and each edge is 
representing the cost from/to the Adjacent vertex.
Figure 1 : The graph
XMUM.OAA - 100/2/8-V3.0 Page | 4
I. Coding:
1. Represent the graph using adjacency matrix.
2. Print the sequence the visited places using BFS and DFS (following the cost and 
start with any place selected by the user).
3. Print the sequence of DFS user preference and BFS user preference where, the 
sequence of visited places starting by any place selected by the user and the next 
place shall be based on the BDF or DFS traversal. If there is more than one options, 
ask the user to select one of them then continue until there is no more segregation. 
Do this process using DFS and BFS separately. 
So, your welcome screen shall print matrix representation for the graph, then asked the 
user to select between DFS Basic or BFS Basic or DFS user preference or BFS user 
preference. Then ask the user to select the start point. If the user chooses the Basic version, 
show the traversal sequence starting from the start point (selected by the user) based on 
the cost. If the user chooses the user preference version, you are going to show suggestion 
what is the next place to visit (or to enqueue) and its cost. If there is more than one 
suggestion at the same time, allow the user to select one of the possible suggestions and 
continue until all the places has been visited and there is no more suggestion. At the end, 
print the traversal order sequence based on the selected method. 
II. Report:
In your report, show the following:
1- Show screenshot for the output of your matrix representation of the graph. 
2- Show screenshots for two complete examples, one using DFS (User preference) and 
another one using BFS (User preference). 
XMUM.OAA - 100/2/8-V3.0 Page | 5
Example: 
(after print the matrix representation)
Which method you want to use: 
1- DFS sequence (Basic)
2- BFS sequence (Basic)
3- DFS sequence (User preference) 
4- BFS sequence (User preference) 
User choose: 3
Please Select your start point: 
User choose: KLIA
Please what place you want to visit after KLIA: 
1- KLCC (12)
2- Melaka (50)
3- TBS (10)
User choose: 1
Output: 
Based on DFS(User preference) , after visiting KLCC you may visit next: 
1- TBS (5)
2- Batu Caves (30)
3- Aquaria KLCC(2)
User input: 2
Output: after visiting Batu Caves you may visit next:
1- Genting Highland (15)
2- Colmar Malaysia (10)
…. Until visiting all the places and there is no more suggestion 
Final Output: 
The sequence of visited places based on DFS and your preference is:
KLIA, KLCC, Batu Caves, ……..
XMUM.OAA - 100/2/8-V3.0 Page | 6
APPENDIX 1
MARKING RUBRICS
Co代 写XMUM.OAA、Java/Python
代做程序编程语言mponent 
Title Assignment 2: Graph Percentage 
(%) 12.5
Criteria
Score and Descriptors
Weight 
(%) Marks Excellent
(17-20)
Good
(14-16)
Average
(10-13)
Need 
Improvement 
(6-9)
Poor
(1-5)
Give suggestion 
Traversing 
algorithms give 
suggestion 
correctly and 
allow the user to 
choose if there 
is more than one 
suggestion.
Traversing 
algorithms give 
suggestion 
correctly and 
allow the user to 
choose if there is 
more than one 
suggestion with 
less interaction 
Traversing 
algorithms give 
suggestion 
correctly without 
allow the user to 
choose if there is 
more than one 
suggestion or 
there is minor 
mistake 
Traversing 
algorithms 
give 
suggestion 
incorrectly 
Traversing 
algorithms 
don’t give 
any 
suggestion 
20
Criteria Excellent
(10)
Good
(8-9)
Average
(6-7)
Need 
Improvement
(5-4)
Poor
(1-3)
Quality of
implementation
The concept is 
correct. The
code is error 
free, runnable 
and perform the 
traverse
correctly. The
code is readable 
and graph is 
defined 
dynamically. 
The concept is 
correct. The code 
is error free, 
runnable and 
perform the 
traverse correctly. 
But the code is 
not readable or 
graph is not 
dynamic. 
The concept is 
correct. The code 
is error free, 
runnable but the 
traversing has 
minor problem. 
the function is 
readable
The concept 
is correct. 
The code is 
error free. 
But cannot 
run
The concept 
is correct. 
The code 
has some 
error and 
cannot run.
10
Report
Format
Report is well
written without
grammar and
spelling
mistakes. Good
presentation
format. All
sections present.
Report format
adhered to.
Grammar
mostly sound.
All sections
present. 
Some
grammatical
mistakes.
Formatting
needs
improvement.
Poor format.
Plenty of
grammatical
mistakes.
Format
completely
ignored. 10
Effort on the 
code 
The code is well 
organized, 
readable, have 
clear comments. 
all the input 
possibilities are 
handled 
The code is 
organized and 
have comments. 
all the input 
possibilities are 
handled 
The code is 
organized with a 
few comments. 
Not all the input 
possibilities are 
handled
The code is 
mess and 
comments 
not clear or 
copy and 
paste. Not 
all the input 
possibilities 
are handled
The code is 
mess and 
there are no 
comments 
or copy and 
paste. No 
handling. 
10
TOTAL 50
Note to students: Please include the marking rubric when submitting your coursework.

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
