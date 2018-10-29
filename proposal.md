# X-Team 80 Project Proposal

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description

To complete a degree, students have to navigate a maze of major requirements compounded with prerequisites for each class. This leads to many students spending more semesters (and tuition money!) than necessary to complete a degree that should have taken less time. We intend to solve this problem with a progrem that will determine the most optimal schedule per semester and thus the least amount of time needed for a degree.

We will solve this using a DiGraph modeling classes as node and prerequisites and directed edges. We can determine the optimal schedule using a combination of BFS and topological sort.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)  
class scheduler


2. Output: Describe the output your program will produce.  Include and example format of the output produced.
A list of classes you should take for each semester and the least amount of semesters to finish your degree. 


3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.
A list of classes and the required prerequisites to take each class. Each class should be required to complete the major.


4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.  
simple GUI(For add/delete classes button, the amount of credit to graduate, the table for the list of classes to complete each semester)


5. Types List: Break your solution idea down into units that you think can be implemented with a single class.  
A simple graph node class to store the data for each required class. An overarching graph class to store every class. A main runner class to start the program and handle I/O and start/handle the UI. An UI class to handle all graphical elements which may then split into more subclasses for each graphical element.


Name each interface or class and briefly describe its function or purpose.  
* Node: Stores information for classes
* Graph: Stores information for every class
* Main: Runs the program, handles I/O and UI
* UI: Handles graphics
* Elements Subclasses(Button/List/etc): Handles graphical elements

## Edit and Submit this file and any figures referenced by this document.

