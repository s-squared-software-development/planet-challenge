# Getting Started

##PLANET ASSIGNMENT CHALLENGE

###INSTRUCTIONS
The purpose of this assignment is to allow you to demonstrate your understanding of OO principles and techniques (think re-usability, maintainability, flexibility etc). Creativity and elegance is also valued. You should not focus on producing performance-optimized code or ‘as-little-code-as-possible’ to the detriment of readability and maintainability. 
The assignment is designed to be completed within 2 to 4 hours. You may however choose to expend more time, at your own discretion. You are encouraged to add documentation (think todo’s and fixme’s) to indicate portions of the design or code that you would do differently given more time.
Most importantly, your code must work. Code that does not compile or produce output will not be evaluated. 
 
###MANDATORY CRITERIA
The following technologies must be used:

* Java
* Spring
* Hibernate

###SCENARIO

###YOUR MISSION
The above graph represents an interstellar transport system used by Earth’s inhabitants in the year 2145. They require you to build a system that will allow them to find the shortest path from point “A”, being Earth, through the galaxy to any of the planets represented by the other nodes. You are provided with a list of node names and their respective distances between their linked planets.  In addition, you need to ensure that the system will work from any source to destination coordinates specified. 
> PERSIST THE GRAPH INTO AN IN-MEMORY DATABASE

Take the data set provided and create the table structure(s) necessary to hold the data. 
* Use an in-memory DB (H2, Derby DB…etc)
* Use an ORM (Hibernate)

> READ THE FILE AND IMPORT IT INTO THE DB

> EXPOSE THE DATABASE USING A RESTFUL WEB SERVICE

Generate a restful service and expose CRUD operations to manage the database. 

> IMPLEMENT THE ALGORITHM

Construct a suitable object model to describe the routes. Create an algorithm that will determine the shortest path between Earth and any destination provided. 

> EXPOSE THE ALGORITHM USING A RESTFUL WEB SERVICE

Expose the RouteRequest document and return a RouteResponse document with the hops 

> CALL YOUR API

Create a simple example of how you called your API and returns the results 

###SUPPORTING DATA	 
All the supporting data can be found within the project under:
```planet\src\main\resources\data```

Additionally below is some useful metrics to help you:

Light Year Constant ```9,460,730,472,580,800 meters```

Passenger Travel Speed ```7,500,000,000,000 meters/second```

###OVERALL DESIGN 
####CONSIDERATIONS:
* Reusability
* Robustness
* Performance
* Readability
* Separation of concerns

###DELIVERABLES 
####PACKAGE AND SUBMISSION 
Your project submission must consist of these components: 
1.	Source code with a maven build script
2.	The project will be built and executed onsite.
3.	A design.txt or design.md file that contains any assumptions or core design considerations that will position the assignment submission. Feel free to add suggestions on how the system could be improved in subsequence releases.
4.	Include a set of unit tests that verify the tasks defined with a minimum code coverage of at least 80%. 
5.	These elements are the be zipped into a single file with the following file name:
 
###MINIMUM SUBMISSION CRITERIA 
Your program must compile, run and return a result. 
####MARKING CRITERIA 
Your project submission will be evaluated based on the following: 
* Does your program work?
* Comment style and formatting 
* Code style, formatting and adherence to standards and conventions 
* Organisation and layout of classes 
* Design choices and use of OO principles and methodologies
* Unit tests, structure of tests and code coverage (negative and positive scenarios)

###ADDITIONAL INFORMATION 
> NOTE: The requirements are purposely open-ended. Please feel free to make assumptions with the proviso that you can justify your decisions.

##Email your source code ONLY (no .class files) in a zip file [YOUR NAME]_[YYYYMMDD].zip to oliver@s-squared.co.za.

#Good luck!










