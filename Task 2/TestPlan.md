# Approach to Task 2

I would first create a test plan that has:
- The title of the project
- The date
- The version of software/application that includes project
- Document Status (Draft/In Review/Final)
- Purpose of project
- Scope of Project
- Objectives to achieve in project
- Features to be tested
- Test Deliverables
- Test Cases with IDs, Descriptions, Preconditions, Steps, Expected Results, Actual Results, Pass/Fail Criteria, Status (Passed, Failed, Blocked)

After creating the test plan document outlining those details, then I would begin testing using the test cases that I created. 

1.First, I would test and check if the API routes to the shop and cart are accessible using Postman. 

2. After seeing that the API is working correctly and are accessible, I would then test to see the behavior if the shopping cart is empty and the browser is closed. 

3. The expected behavior is no action or callback from twilio to send an SMS message.

4. Then I would test and leave a few items in the shopping cart. Abandon the website.

5. Check the database to see if the cart items are saved and are correct.

6. After 24 hours, I would expect the cron job to fire the twilio API to send me a SMS message, reminding me that I have an unchecked shopping cart with items. 

7. While testing this feature, I would also check the figma/zeplin/other UI design tool, to make sure that the UI of the feature matches the UI designs made. If not, I would ask the UI designer and the Project manager what the finalized UI design of the feature should be.

8. As I work through the test cases, I would use JIRA to track the progress of the testing as well as log any and all bugs/defects to the board. 

9. I would note down the browser and browser version used for documenting bugs.

10. I would include the steps taken to reproduce the bug.

11. List the expected behavior and the actual behavior.

12. I would record the test using the screen record feature in macOS or snipping tool in Windows OS. 

13. I would include also screenshots of the final result of the test for more clarity. 

14. I would share this bugs during standups to give more visibility to them as well as working with developers to have these bugs resolved. 
