# X-Team 103 Project Proposal Movies^2

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

Briefly describe a problem that your team would like to solve.  
Describe at a high level a program that could solve that problem.

When our team met up for the first time and were getting to know each other, the topic of movies came up. We all asked each other what our favorite movie was, but we all were unsure of our favorite movies since it was hard to think of every movie we have seen before. For this proposal, we wanted to make a program that organized movies you have seen where you can add movies to custom "playlists" for organizational purposes.

To solve this problem, we want to implement a hash table with buckets as a collision resolution. A hash table will represent a collection in the program with each index coordinating to its own playlist of movies. The indexes will store a reference to a linked list where each node is a different movie. The key of the node will be the movie title and the value returned when searched for will be a reference to a movie object that will print the year, director, lead actors, and a brief summary. Users will be able to create a new playlist, by adding on to the hashtable, and add movies to current playlists, by creating a new node in the linked list. 

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)
  
  Movies^2


2. Output: Describe the output your program will produce.  Include and example format of the output produced.
  
  The program will be able to output the data of a movie, the movies in a playlist, and the collection of playlists depending       on what the user selects to be outputted. 
   
   Example Output: 
   
                   Comedy, Thriller, Favorites
                   
                   "The Shining", "Psycho", "The Exorcism"
                   
                   "Black Panther" (2018)
                   Directed by: Ryan Coogler
                   Starring: Chadwick Boseman, Michael B Jordan, Lupita Nyong'o
                   Summary: T'Challa, heir to the hidden but advanced kingdom of Wakanda, must step forward to lead his people into a new future and must confront a challenger from his country's past.

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.

   The program will be able to take input for new playlists, movies in a playlist, and data for a specific movie.
   
   Example Input: 
                  
                  Insert Movie Playlist Title:
                  
                  Insert Movie Name(" "): 
                  
                  Movie Year(Optional):
                  Director(Optional):
                  Stars(Optional):
                  Brief Summary(Optional):


4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.
       
   See figure 1 for a visual represenation of our interface


5. Types List: Break your solution idea down into units that you think can be implemented with a single class.
   
   To create the hash table, we could do that in one class that will be the HashTable class. Inside the HashTable class we will have an inner Node class to make nodes for the linked list in the hash table. We will also have a Movie class used to create movie objects to store data about the movies in the array. To run the program and call for input values, we will have a Main.java class that will call all the methods and run the actual program. Lastly, we will have the TestHash class where will will JUnit test the program for all values to ensure it runs 



## Edit and Submit this file and any figures referenced by this document.

