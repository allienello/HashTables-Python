# HashTables-Python
In this project, I implemented a Hash Table from scratch in Python and used it on an application problem.

This project was for my data structures and algorithms class at university. Areas of the code where it says 'Do not modify' were given by the instructor. Code indicated otherwise by 'Implement below', 'My code below', or 'Modify below' was implemented by me.

Each function I completed had contraints I had to adhere to. This includes runtime and space complexity (as indicate by the docstrings), the skeleton of the function (declaration, parameters, return value), and the overall task or goal.

Using my knowledge on data structures, specifcally hash tables, I implemented the necessary algorithms. I also used my course materials (lecture slides and textbooks), as well as LLMs such as chatGPT when I was stuck on certain aspects.

The application problem for this project was written by the instructor. Similar to the rest of the project, I was given the specifications for the function(s) and an explanation of the problem.

//Application Problem Specs//

Music Representation
A song is represented as a list of melodies (List[List[int]]). Each melody is a list of integers that symbolize musical notes. Two essential points to remember:

Key Signatures: A melody can exist in different key signatures. For our purposes, this means a melody can be represented by a series of integers with a constant offset from another melody. For instance, [1, 2, 6] is equivalent to [2, 3, 7], [4, 5, 9], and so on.

Length Matters: Only melodies of the same length can be deemed similar. Therefore, [1, 2, 3] and [1, 2] are not similar.

Problem Statement
Determine if a song is plagiarizing another by identifying "similar" melodies. A song is considered plagiarizing if the number of similar melodies exceeds the allowed "max similarity".
