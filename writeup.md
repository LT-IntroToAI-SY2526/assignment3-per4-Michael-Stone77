# Assignment 3 - Write UP

## Description
This assignment completes our movie chatbot system by implementing action functions that query our movie database and building a natural language interface. You implemented functions to search for movies by year, director, and actors, as well as the core search system that matches user queries to appropriate database operations. This builds directly on the pattern matching work from Assignment 2 to create a functional conversational AI system.

## What to complete
1. Complete all action functions in `a3.py` (title_by_year, title_by_year_range, etc.)
2. Implement the `search_pa_list` function to handle pattern matching and responses  
3. Add at least one new movie to the database with proper formatting
4. Create a new pattern/action pair and add it to the pa_list
5. Ensure all provided assert statements pass
6. Complete the reflection questions below
7. Push your code to github for grading

## Reflection Questions

1. What are some key programming concepts or techniques that you learned while completing this assignment?
Some key programming concepts I learned while doing this assignment was how to go through a list in python.  This is key to programming as lists are used in lots of codes so now that I know how to use them and go through them, I can now use that for other codes I come across in the future.


2. How does the overall movie chatbot system work? Explain the flow from when a user types a query to when they receive an answer.
How it works is that it starts when a user types in a query, this then makes the chatbots search function to take key words from those queries and match them with info in the database.  It also uses the functons to figure out what information needs to be returned to the user.  After it goes through the list, it will either find a match and return what it finds to the user or it will find nothing a return no answers.  If a user enters something that does not match up with anything in the database, the chatbot will simply return I don't understand.



3. What are some real-world applications where this type of pattern-matching chatbot system could be useful? How might you extend or improve this system for practical use?
Some real world applications where this type of chatbot system would be useful is databases as it would allow people to find what there looking for quickly and efficiently like looking for medical records of a certain patient or looking through a database of fingerprints to find the fingerprints of a crime suspect.  One thing I might extend for this system for practical use is adding more action functions to the code so that it can find things more effecently and not get bogged down from trying to answer a query that doesn't match any of the already existing functions.  This would let it reach further into the database and extend the types of queries it can answer.