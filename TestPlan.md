TestPlan for SE3Prac5 2048
============================================

Introduction
---------------

The purpose of this document is a Testing Plan for 2048 program for SE3 practicals.

The basic premise of the 2048 game is that you tilt the board left, right, up or down to move numbered tile together.  Any numbers that match, are combined into a single tile with the sum of the values of the two original tiles.  Since only pairs of tiles combine, the values will always be powers of two.  Each time you tilt the board, one new tile with value 2 or 4 is added.  The challenge is to work up to having a tile with 2,048 on it, before the board fills and no move is possible.  The score is calculated as the sum of the number on all tiles that have been combined.  


This documentment will be divided into sections; Section 1 is this section. Section 2 describes the required sources to perform the testing. Section 3 Features to be tested. Section 4 Features that will not be tested. Section 5 List of documents that will be produced during the testing process. Section 6 will describe the risks and dependencies. Finally Section 7 will cover the success criteria of the test.  

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
#### security testing 
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
* Tilt Down Function -Do Numbers move Down  D is pressed 

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
