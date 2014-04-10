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



Types of Tests that will not be useful
---------------------------

Types of Tests apply
---------------------------

* Unit Testing
* Integration Testing
* 

Game Functions to be Tested
-----------------------

* Board Drawing 
* Tilt Left Function
* Tilt Right Function
* Tilt Up Function
* Tilt Down Function
* Combine 2 Similar Numbers
* Don't Combine Unique Numbers 
* Win game condition a tile with 2048
* Lose game condition when all the board is filled and cannot be combined.


Game Functions NOT to be Tested
---------------------------
* 


Test Items Documentations
--------------------------

Risks and Dependencies
--------------------------

Success Criteria
--------------------------
