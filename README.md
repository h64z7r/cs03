java c
COMP4348/5348 Assessment – Practical Task 
Enterprise-Scale Software Development (COMP5348) 
Semester 2, 2024 
Practical Task - Extending Bank System
Practical Task 1 (1%): Submit via Canvas by 01 September 2024 23:59 PM (Week 5) 
Practical Task 2 (4%): Submit via Canvas by 22 September 2024 23:59 PM (Week 8) 
In this practical task, we are going to extend the bank system introduced in the Week 3
tutorial. The code solution is provided in the Week 3 tutorial answer, and the sample ERD is available in the Week 3 tutorial (also attached below). It includes the basic functionality of creation of new customers, creation of new accounts, and making transfers between two accounts.
The marketing team of the bank would like to extend the bank system to include some new features, including transaction categories and savings goals. Below is a description of each feature and the associated functional requirements:
1.   Transaction categories. 
Transaction categories allow customers to categorize their transactions (e.g., groceries, utilities, transportation, and entertainment).
Functional requirements:
The system allows the creation, editing, and deletion of custom categories by the customer. Customers must be able to assign a category to each transaction they make.
2. Savings goals. Savings goals allow customers to set specific financial goals (e.g., saving for a holiday trip, a major purchase, or any other financial goal) and track their progress towards  achieving these goals. Each goal has a specific amount and a specific due date.
Example goals include a taking a holiday in December costing $2,000 and buying a car by January costing $20,000.
Functional requirements:
The system allows customers to create, edit, and delete savings goals. For each savings goal, specify the goal, a target amount, and a target date.
Practical Task 1: 
Submit an Entity-Relationship Diagram (ERD) that demonstrate how your models support the business case described above. These ERDs should show all entities, attributes, relationships (including cardinalities), and any other relevant constraints that correspond to the entity types and relationships you intend to have in your solution. Clearly indicate where/how/w代 写Enterprise-Scale Software Development (COMP5348) Semester 2, 2024R
代做程序编程语言hy you are recommending these changes.
Marking guide:
How well the updated model captures the new functional requirements. How well the new modeled requirements are explained and justified.
Practical Task 2: 
In this task, you willfully implement the changes you proposed in Task 1. Specifically, you will implement the transaction categories and savings goals functionality based on the Week 3 Tutorial Answer. While you are not required to develop the front-end user interface, your controller should fully support all the business functionalities. 
Marking guide:
•   Your code fully supports transaction categories and savings goals, with controller methods covering all business functionalities.
•   Your code is easy to understand, with proper explanations and justifications where necessary, so that others can buildupon it.•   Your code correctly factors each component within its corresponding layers. The code follows standard design practices, incorporate the principle of separation of concerns.
Please note that you may choose to implement a different model than your submitted ERD diagram. These two tasks will be marked separately.
Submission instructions for Task 2:
1.  You should submit your solution and a readme.txt/md/pdf file together in a zip file through the course Canvas site. The zip file should include your unikey in the filename. For example, if your unikey is abcd1234, you would label your zip file as abcd1234Prac2.zip. 
Please include comments in the modified or added files to help us find your changes. Please do not include build filesorIDE-generated files in your zip file,e.g., ‘build/’ and ‘.idea/’ .
2.   The readme.txt/md/pdf file should provide an outline of:a.    The components you modified or introduced into the bank system. Make sure you clearly identify where these modifications or additions can be found, and how to find  them.
b.    How to run/test your solution.
c.    Discussion/description/justification of your changes and screenshots showing that the do provide the requested functionality.
3. You maybe asked to run your application and show your implementation to your tutor in the tutorial starting from Week 9.





         
加QQ：99515681  WX：codinghelp
