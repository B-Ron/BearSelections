# BearSelections



Bear Selections: Requirement Document

Overview:
Bear Selections is a search tool, designed for Morgan State University students, that allows students to easily and accurately find the classes they need for the upcoming semester, based on their progress in their undergrad matriculation. Bear Selections will consist of a student catalog, search engine, and a list of classes provided to students to choose classes from. The way Bear Selections works is, students will enter their information needed, in order for the searching system to accurately provide the student with the classes needed for their specific curriculum.

Software Process Model: Waterfall
We will use waterfall process model. We chose this because we believe in completing a task 100% by step before moving on to the next to reduce the amount of work done in between.

Audience and Users:
The audience and users are Morgan State University undergraduate students

Block Diagram for Components



Caption

We start with brainstorming how we will design the search bar

The design of the search bar will have to be able to connect with Morgan’s Websis servers to access each student's catalog and the university’s catalog of classes. After these designs we will implement and test. Given everything runs smooth we will be complete.

If we run into any bugs, we will go back to the implementation process and debug/improve. Then repeat testing till the process is complete.
List both user requirements and system requirements

User Requirements:

Search Box Inputs

System Requirements:
This system shall accept a list of descriptive material that specifies the user’s area of study. The system will return a list of links of results that relate to the input information, specified by the students' information given.

Requirement Validations:
Validity check: 
Function: Confirms information
Description: Will check that the information provided by the students are valid
Inputs: Student Class Search
Source: Reading from Websis
Output: Websis, where student info is stored
Action: Information is valid if all boxes are filled with information that matches each boxes specific input technique. The information will be computed, using websis and catalog information  and a result is returned. 
Requires: Catalog, Student information
Pre-Condition: Student information is recorded 
Post-Condition: Links of a catalog with classes are returned. 
Side effects: None 
Consistency check: 
Function: Checks for the same information between information provided 
Description: The information already provided in the system should not conflict with one another.
Inputs: Previous student input
Source: Current information entered from student; information stored in Websis server
Output: Websis
Action: Information is consistent if the previous input from the student matches the information stored on the server of Websis.
Requires: Previous student input, Websis server
Pre-Condition: Student information that was previously collected is present 
Post-Condition: Student input and Websis Server match 
Side effects: Other results may occur below
Completeness check: 
	Function: Checks that a complete set of requirements have been documented and developed. 
	Description: The information that has been saved in the system should include information that is required for Logging in and finding their classes
	Inputs: Websis; 
	Source: Current information from the set 
	Output: Websis
Action: Once everything is validated, the system runs a check to confirm all tasks have succeeded
Requires: All previous information 



Link to website: https://cse.google.com/cse?cx=a78b3beb6a96dcba5
