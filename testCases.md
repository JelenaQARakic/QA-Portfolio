| | | | | | | |
|-|-|-|-|-|-|-|
|Case No.|Test Case Name|Precondition|Test Data|Step No.|Test Steps|Expected Results|
|1|Log in with Email Verification with valid credentials  (Error Guessing)|The Match It application is installed and opened on Android. The user is on the login screen.|Valid Email: example.ex9589@gmail.com  Verification Code: Received via email after entering the email address.|1|Enter a valid email address.|The email address is valid.|
| | | | |2|Click on "Continue further."|The button is responsive, and the application proceeds to the next step.|
| | | | |3|Copy the code from the email and paste it into the "Code" field.|The code is successfully copied and pasted.|
| | | | |4|Click on "Enter the code."|The code is accepted, and the application prepares for the next stage.  The application displays a message: "You are one step away from a real match! You have two options:" "Continue to tutorial" "Skip"|
|2|Log in with Email Verification using invalid credentials (Error Guessing)|The Match It application is installed and opened on Android. The user is on the login screen.|Invalid Email: rakic.jelena991gmail.com  Incorrect Verification Code: Incorrectly copied code from the email.|1|Enter an invalid email address (e.g., missing "@" symbol).| |
| | | | |2|Click on “Continue further”. | |
| | | | |3|Copy an incorrect code from the email and paste it into the “Code” field.| |
| | | | |4|Click on “Enter the code”.|The application should gracefully handle an invalid email format and incorrect verification code, possibly displaying error messages.|
|3|Maximum Technologies Selection Limit (Boundary Value)| The user is on the profile screen for adding technologies. The user has already selected the maximum allowed number of technologies (20).|Current selected technologies: [Tech1, Tech2, ..., Tech20]  Attempted to select: Angular|1|Verify that there are 20 technologies already selected. | |
| | | | |2|Attempt to select one more technology (e.g., Angular).|The application should only allow candidates to select up to 20 technologies. The number of selected technologies should remain at 20, and there should be no indication of the attempt to select an additional technology. The application should handle the boundary case gracefully without errors or unexpected behavior.|
|4|Decreasing Experience to Minimum Allowed Value (BVA)|The candidate is logged into the application and is on the "Experience" tab. Initial experience years should be: 5 |n/a|1|Locate the "Experience" tab. | |
| | | | |2|Click to decrease the experience years using the "-" button until it reaches 0.|The application should allow the user to decrease the experience years using the "-" button. The displayed experience years should decrease with each tap, and when the user attempts to go below 1, the value should remain at 1, as it is the minimum allowed value.|
|5|Adding a Job Advertisement (Combination of Testing Techniques)|To validate the successful creation of a job advertisement in the system with various testing techniques.|The recruiter is logged into the application and is on the "Advertise" tab.|1|Click on the "Add Advertisement" button.|The system should open the job advertisement creation form.|
| | | | |2|Fill in the position name as "Test Developer."|The position name is successfully filled.|
| | | | |3|In the "Technologies" section, select the following 5 technologies: - Java (Experience: 5 years) - SQL (Experience: 3 years) - Amazon S3 (Experience: 2 years) - Magento (Experience: 1 year) - Git (Experience: 5 years)|Technologies are selected without errors.|
| | | | |4|Fill in the name of the project as "Desperados Santos."|The project name is successfully filled.|
| | | | |5|In the "About Project" section, describe it as a Co-op game for up to 6 players, a treasure hunt.|The project description is successfully filled.|
| | | | |6|Set the number of team members to 8.|The number of team members is successfully set.|
| | | | |7|From the Location dropdown menu, select "Serbia."|Serbia is selected as the location without errors.|
| | | | |8|In the Industry dropdown menu, choose "Gaming."|The gaming industry is selected without errors.|
| | | | |9|Select "Belgrade" from the City dropdown menu.|Belgrade is selected as the city without errors.|
| | | | |10|Choose the "Startup" option for the project type.|The project type is set to Startup without errors.|
| | | | |11|Select "Outsource" as the Project Development Methodology.|The development methodology is set to Outsource without errors.|
| | | | |12|In the Benefits section, add the following:  - "Fitpass" (First Benefit)  - "Private Health Insurance" (Second Benefit)|Benefits are added without errors.|
| | | | |13|In the Working Method section, check the "Hybrid" method. |The working method is set to Hybrid without errors.|
| | | | |14|In net salary in the EU, enter a minimum of 800 and a maximum of 2000 euros.|The salary range is set without errors.|
| | | | |15|Check the "Display the Salary" option.|The salary display option is checked without errors.|
| | | | |16|Click on the "Create" button."|The message appears: “Job position has been created successfully.”. A button below reads: “Get me back to all job advertisements.”. This test case incorporates boundary value analysis (BVA), error guessing, decision table testing, and state transition testing techniques to ensure comprehensive test coverage.|
