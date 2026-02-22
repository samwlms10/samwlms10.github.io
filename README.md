# **CS 499 Portfolio**
## Samuel Williams

Welcome to my Portfolio for the Computer Science program at SNHU!

### Sections
1 - Professional Self Assessment  
2 - Code Review  
3 - Software Design and Engineering  
4 - Algorithms and Data Structure  
5 - Databases  

### Professional Self Assessment

### Code Review
Below is a link to my YouTube channel where I have posted my Code Review.  
In this code review I go through the code base of the Animal Shelter Dashboard  
and where I see can use improvments.  
[Code Review](https://youtu.be/iIicrAOqNUE)
Below now are the improvements that were made and why they were made for each category.  
  
### Software Design and Engineering
The artifact that I made enhancements to was the animal shelter dashboard from CS340.  
The enhancements that I made to this project were removing the hard coded credentials  
in the .py files and putting them into a newly made .env file that I also added to the  
git ignore.  This change greatly improves the security of the system by not allowing accidental  
exposure of sensitive information to be readily available to the public.  I also restructured  
the error handling to the CRUD operations to allow for fault tolerance and to fail gracefully 
if it were to fail.  The comments in the .py files were also improved to better reflect what  
is happening in the code and also to take out any unnecessary comments as well.  Lastly,  
I refactored the code into .py application, thus removing the dependency on Jupyter  
Notebook and also the Apporto SNHU server.  This refactor allows the application to be ran  
on my local machine through Dash.  This change simplifies the application launch and also  
improves portability.  This meets the outcomes since it improves on the code making it safer  
and more maintainable in the future.  It brings security to the forefront of the application  
and also allows the application to be more maintainable and scalable.  Reflecting on what I  
learned throughout redesigning this code is the importance of designing a system to be more than  
just a working application but something that can be built upon and enhanced for the future.  
The biggest challenge that I had was transitioning the application from the SNHU hosted environment 
to something that I could deploy locally.  
  
### Algorithms and Data Structure
The artifact that I continued to make enhancements on was the Animal Shelter Dashboard from CS340.  
The enhancements that I have performed this week focused on improving the applications use of 
algorithms, data structures, and efficiency.  One of those enhancements was to refactor the breed  
distribution logic that was the backbone of the pie chart that showed the top breeds in a chart 
at the bottom of the web page.  I switched the logic from working through pandas logic to a  
dictionary based counting algorithm that iterates through the dataset only once to group and  
count how many of each breed there are in the database.  Those results are then sorted and displayed.  
Another big enhancement that was performed was that I added projection into the read function  
which will let the application only return fields that are required by the dashboard.  This will  
reduce the unnecessary data transfer, thus improving performance.  These enhancements meet  
the course outcomes of designing and evaluating computing solutions using algorithms and  
datastructures, by implementing custom algorithms and showing improved performance.  Going  
through these enhancements I learned the importance of making algorithmic decisions explicit  
rather than rely only on high level libraries to do the algorithmic thinking for you.  Though  
these libraries can be very simple to implement we don’t always know the performance of them  
and can better tell the performance by implementing our own algorithms.  
  
### Databases
The artifact that I continued to enhance this week was the Animal Shelter Dashboard that I first 
developed in CS340.  The enhancements that I focused on this week are for the database section  
of the system.  The database runs through MongoDB and that is what I use to store and retrieve  
different animal records to present in an easy to read Dash web interface.  Last week I introduced  
query projection which limits the fields being returned from the queries thus improving performance  
and removing the unnecessary data transfer.  Another improvement that was made was adding more  
validation to the query filters to make sure they are properly executed.  Along with being properly  
executed I also added safeguards to the update and delete operations to prevent from accidental mass 
deletions/updates to the database.  These changes not only increase the reliability and quality of  
the queries but also the safety as well.  These enhancements meet the planned outcomes by first and  
foremost focusing on the security mindset especially working with the data in a database.  What I learned 
throughout this enhancement was that there is more that goes into the database layer than just storing  
and retrieving data.  You have to keep the data safe not only from attackers but also from accidental  
mishaps such as leaving a delete query blank and deleting the whole database.  

[Original Animal Shelter Dashboard](https://github.com/samwlms10/CS340.git)  
[Updated Animal Shelter Dashboard](https://github.com/samwlms10/CS340-Updated-.git)  
