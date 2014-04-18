TestPlan for SE3Prac5 2048
============================================

Introduction
---------------

The purpose of this document is a Testing Plan for 2048 program for SE3 practicals.

The basic premise of the 2048 game is that you tilt the board left, right, up or down to move numbered tile together.  Any numbers that match, are combined into a single tile with the sum of the values of the two original tiles.  Since only pairs of tiles combine, the values will always be powers of two.  Each time you tilt the board, one new tile with value 2 or 4 is added.  The challenge is to work up to having a tile with 2,048 on it, before the board fills and no move is possible.  The score is calculated as the sum of the number on all tiles that have been combined.  


This documentment will be divided into sections; Section 1 is this section. Section 2 describes the required sources to perform the testing. Section 3 Types of testing that will be applied. Section 4 items that will be tested. Section 5  items that will not be tested. Section 6 List of documents that will be produced during the testing process. Section 7 will describe the risks and dependencies.Finally Section 8 will cover the success criteria of the test.  

Required Resources
---------------------

* Computer Hardware that can run a  text editor, C compiler and Github.
* Github Account, Github Local Repository and Remote Repository.
* Fork of Paul Gardner-Stephen's se3Prac3 repository
* Students to write the code and test cases.


Types of Tests to apply
---------------------------

#### Unit Testing
#### Integration Testing
#### Regression testing
#### Usability testing 
#### Performance testing
#### Installation testing
#### Documentation testing 
#### Operations testing 
#### Security testing 
#### conﬁguration testing 



Types of Tests that will not be useful
--------------------------------------

facility testing - does the system provide all the functions required?"
volume testing - can the system cope with large data volumes?"
stress testing - can the system cope with heavy loads?"
endurance testing - will the system continue to work for long periods?"
storage testing - are there any unexpected data storage issues?"
installation testing - can we install the system successfully?"
reliability testing - how reliable is the system over time?"
recovery testing - how well does the system recover from failure?"
serviceability testing - how maintainable is the system?"


Items to be Tested
---------------------------------
* Does the Program check if the user input is valid.
* Tilt Left Function - Do Numbers stay or move to the left when the L is pressed 
  - Does the numbers stay on the left if they are already positioned at the left.
  - Does the number move to the left side of the board if the index in the furthest left is empty 
  - Does the number move to the left side of the board if the index next to the furthest left is empty and the index on the left has a number. 
   
* Tilt Right Function-  Do Numbers stay or move to the right when the R is pressed 
  - Does the numbers stay on the right if they are already positioned at the right.
  - Does the number move to the right side of the board if the index in the furthest right is empty 
  - Does the number move to the right side of the board if the index next to the furthest right is empty and the index on the right has a value stored. 
  
* Tilt Up Function -Do Numbers move up when the U is pressed 
  - Does the numbers stay up if they are already positioned at the top.
  - Does the number move up at the very top side of the board if the index at the top is empty 
  - Does the number move up to the index below the top if the index on the top has a value stored. 

* Tilt Down Function -Do Numbers move Down  D is pressed 
  - Does the numbers stay down if they are already positioned at the top.
  - Does the number move down at the very bottom side of the board if the index at the bottom is empty 
  - Does the number move down above the index above the bottom index if the bottom index has a value stored.

* Combine 2 Similar Numbers that next to each other
* Combine 2 similar number  with an empty index separating them
* Combine 2 similar number  with two empty indexes separating them

* Don't Combine Unique Numbers 
* Win game condition a tile with 2048
* Lose game condition when all the board is filled and cannot be combined.
* Board Draws
* Ensure


Item NOT to be Tested
---------------------------
* 


Documentations Produced
--------------------------
* How to Play
* Installation Instructions
* Test Results
* Commit log
* Issues log

Risks and Dependencies
--------------------------
### Risks 
* Unclear requirements
* Misunderstanding of requirements
* Hardware or Software failure in the duration of the testing
* 
* 
Risk	Probability	Risk Type	Owner	Contingencies / Mitigation Approach
Unable to acquire the necessary number of skilled personnel as the components become ready to test.	30%	Personnel
Schedule	Test Manager	Resources for components will be split between the existing resources.
Schedule must be adjusted accordingly.
Unable to acquire some of the necessary hardware and software required for integration and system testing	25%	Equipment	Program Manager
Test Manager
Development Manager	Utilize existing acquired hardware.
Split test execution into morning and evening shifts such that testing can occur for multiple teams in the same day using the limited hardware. This requires support of the development during both shifts.
Third party services utilized in the system become unavailable during testing	5%	Third party	Alliance Manager	Setup a communication channel to 3rd party to report and handle issues when they occur.
Use the communication channel above to stay aware of planned outages and maintenance to help schedule test execution.
Components are not delivered on time	25%	Schedule	Development Manager	Integration testing with those components must be delayed until the component is delivered
Overall integration test approach may be modified to do an appropriate amount of bottom-up as well as top-down or sandwich integration.
Schedule must be adjusted accordingly.
Turnover	5%	Personnel	Test Manager	Testers will work in pairs on components. If a single member of the team decides to leave, a secondary testing with the knowledge of the component will still be able to train a new tester or finish the work.
Schedule must be adjusted accordingly.

### Dependencies

Success Criteria
--------------------------

* The Board Visible 
* The Tile values are visible
* The values Go to the Left side
* The values Go to the Right side
* The values Go Up
* The values Go Down
* 2 Similar Numbers Combine 
* Unique Numbers Don't Combine
* Win game condition a tile with 2048
* Lose game condition when all the board is filled and cannot be combined.
