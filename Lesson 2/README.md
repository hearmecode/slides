Hear Me Code Lesson 2
======

**What you'll learn:** 
* Storing multiple pieces of information in a list
* Adding and removing items from a list, finding its length
* Viewing part of a list
* Changing part of a list without affecting the other parts
* Splitting a string into a list
* Finding whether a value exists in a list or string
* Using loops to run code multiple times
* Using loops to run code over the contents of a list
* Display the position of a list's items alongside its values
* Using zip to loop over multiple lists at once
* Using while loops to continue doing something as long as a condition is met

**Just a few practical examples:**
* For each cell phone number in a list, send a text message
* Break a string containing an address into a list for easier manipulation
* Store many pieces of similar information together in a single variable
* Make changes to every item in a list
* Show 10 movie recommendations
* Find out whether two movie's genres had any similarity

**Examples in real projects:**
* For each movie matching the search terms, add it to the database if it doesn't already exist: [Used in http://shannonvturner.com/bechdel](https://github.com/shannonturner/bechdel/blob/d1b4d805277b74456c4c1d9500b48b994ed77e57/apps/bechdel/views.py#L100)
* Show all choices when more than one movie matched the search terms [Used in http://shannonvturner.com/bechdel](https://github.com/shannonturner/bechdel/blob/d1b4d805277b74456c4c1d9500b48b994ed77e57/apps/bechdel/views.py#L148)
* Split a string into a list on the newlines: [Used in http://shannonvturner.com/seriously](https://github.com/shannonturner/seriously/blob/e157c59c601ad66c8a5a6e1c3562377552a858ff/geocode.py#L7)
* For each school in a list, find its latitude and longitude and save that information in a list: [Used in http://shannonvturner.com/seriously](https://github.com/shannonturner/seriously/blob/e157c59c601ad66c8a5a6e1c3562377552a858ff/geocode.py#L11)
* Create a specific number of bingo sheets: [Used in a bingo sheet generator](https://github.com/shannonturner/bingo-sheets/blob/master/bingo.py#L35)
* If one or two artworks don't load, get a new artwork to replace it until we have two artworks that do load: [Used in http://shannonvturner.com/art/mash](https://github.com/shannonturner/art-games/blob/59809fe951bcfd83e984039b82d9ae1191b04fe2/apps/mash/museum_apis/victoria_albert_museum_api.py#L71)

**Code Samples:**
* https://github.com/shannonturner/python-lessons/tree/master/section_04_(lists)
* https://github.com/shannonturner/python-lessons/tree/master/section_05_(loops)
* https://github.com/shannonturner/python-lessons/tree/master/section_06_(str-list)

**Exercises:**
* 99 bottles (Beginner): https://github.com/shannonturner/python-lessons/blob/master/playtime/lesson02_99bottles.py
* PBJ while (Beginner): https://github.com/shannonturner/python-lessons/blob/master/playtime/lesson02_pbj_while.py
* States (Intermediate): https://github.com/shannonturner/python-lessons/blob/master/playtime/lesson02_states.py
* Movies (Advanced): https://github.com/shannonturner/python-lessons/blob/master/playtime/lesson02_movies.py

### Vocabulary

**Concepts Learned:**
* Lists
* For loops
* While loops
* Nesting our loops

**Keywords learned:**
* in
* for ... in
* while

**Functions learned:**
* raw_input()
* range()
* enumerate()
* zip()

**String Methods learned:**
* .split()

**List Methods learned:**
* .append()
* .pop()
* .extend()
* .insert()