# Assignment 3 - Writeup

Assignment 3 is all about creating this natural language query system.  In order to do so, you have to write a lot of functions to retrieve infomation.  You will also have to write a function to return answers from a pattern-action list.  There is a lot of work to accomplish in this assignment, but this portion is intended for you to write about what you accomplished.

## Reflection Questions
1. In your own words describe the `search_pa_list` function.
    The search_pa_list function will interate through the user input's string (using the split method to divide the string into individual words). If the question matches the data structure, then the search_pa_list will use an action method to find the needed information (based on the % and _) from the source list. 

2. What movie did you add to the `movies.py` file?  What year was it made? Any specific reason you added that movie?
    Forest Gump. It was made in 1994. We were talking about Forest Gump in AP Lit to discuss plot structure and I remembered really loving it when I watched it the first time. 

3. What pattern / action did you add to the paList data structure?  Why do you think that is a useful pattern / action?
    I added (str.split("cast of %"), actors_by_title) to the paList data structure. From using Google, I typically search up "cast of _" which leads me to the same answer when I search up "who acted in _" its just faster and completes the same action as  (str.split("who acted in %"), actors_by_title),.

4. What is chatbot would you create that would be like this?  Describe why you would create it and what it would do.
    A chatbot that I would create would be a chat bot that could tell you the best selling skin care product from well known brands, the user rating, and the price. I think its hard to find good products, especially when your starting a new regiment, that are within range of some people's budgets.

5. What was the most difficult portion of this assignment?
    I think initially,  understanding the implication of the match function inside the action functions (a3.py) was a bit difficult. In addition, because Python has so many short cuts I don't know of, solving a function takes way longer and becomes more convuluted/ complicated. 

6. Did you write a new assert for your pattern action?
    Yes.
 



