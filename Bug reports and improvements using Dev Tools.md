**Bug Report 1: Display and Content Overlapping on Samsung Galaxy Fold**

**Summary:** Content and display issues identified on the "Add
Advertisement" page when accessed through Samsung Galaxy Fold.

**Description:** During mobile testing using Chrome dev tools with the
Galaxy Fold option selected, the content on the "Add Advertisement" page
experiences overlapping, causing the text to extend beyond the expected
elements.

**Preconditions:**

- The user is logged into the Match IT app.

- The user is on the "Add a new job ad" page.

**Environment/Reproduced on:**

- Device: Galaxy Fold

**Priority/Severity:**

- Priority: High

- Severity: High

**Steps to Reproduce:**

1.  Log in to the Match IT app.

2.  Click on “Add Advertisement”.

3.  Scroll down the page.

4.  Observe the elements and notice the text extending beyond the
    expected elements.

**Expected Result:** The page for adding new job positions should be
displayed correctly and intuitively. There should be no overlapping of
text and elements.

**Actual Result:** The text and elements are overlapping, leading to a
less-than-optimal user experience.

*Attachment:* Screenshots from the Galaxy Fold displaying the
overlapping issue.

*Note:* The severity and priority are both marked as high due to the
impact on user experience and the potential for confusion caused by the
overlapping elements.

**A screenshot has been provided in the "media" folder with the same bug title.


--------------------------------------------------------------------------------------------------------------------

**Bug Report 2: Inability to Input Salary Range on Samsung Galaxy Fold**

**Summary:** The "Add Advertisement" page on Samsung Galaxy Fold does
not allow the user to input the salary range.

**Description:** While attempting to add a new job advertisement on the
Match IT app through the Samsung Galaxy Fold, users are unable to input
the minimum and maximum salary values. The input fields for salary are
unresponsive, preventing users from specifying the desired salary range
for the job position.

**Preconditions:**

- The user is logged into the Match IT app.

- The user is on the "Add a new job ad" page.

**Environment/Reproduced on:**

- Device: Galaxy Fold

**Priority/Severity:**

- Priority: High

- Severity: High

**Steps to Reproduce:**

1.  Log in to the Match IT app.

2.  Click on “Add Advertisement”.

3.  Attempt to input the minimum and maximum salary values.

4.  Observe that the input fields for salary are unresponsive.

**Expected Result:** Users should be able to input the minimum and
maximum salary values for the job position on the Galaxy Fold, providing
a complete and accurate representation of the job offer.

**Actual Result:** The input fields for salary are unresponsive,
preventing users from specifying the desired salary range.

**Video** has been provided into the folder QA portfolio with the same
bug title.

----------------------------------------------------------------------------------------------------------
**Bug Report 3: Unexpected Token Error in Bootstrap JavaScript**

**Summary:**

Encountering an "Unexpected token '\<' error in the console logs while
loading Bootstrap JavaScript.

**Description:**

During the application's execution, a critical error occurs in the
console logs with the message "Uncaught SyntaxError: Unexpected token
'\<' at bootstrap.min.js:1:1." This error indicates a syntax issue in
the Bootstrap JavaScript file, specifically at the very beginning of the
file.

**Preconditions:**

**-** Recruiter is logged into the app

\- The application is loaded in a web browser.

\- Bootstrap JavaScript file is included in the project.

**Steps to Reproduce:**

1\. Open the web application in a supported browser.

2\. Open the browser's developer tools and navigate to the console logs.

3\. Observe the "Uncaught SyntaxError: Unexpected token '\<' at
bootstrap.min.js:1:1" error.

**Expected Result:**

The application should load without any JavaScript errors and the
Bootstrap JavaScript file should be executed successfully.

**Actual Result:**

The console logs show a critical error in the Bootstrap JavaScript file,
indicating an "Unexpected token '\<' at bootstrap.min.js:1:1."

**Attachments:**

Screenshot of the console logs displaying the error message.
**A screenshot has been provided in the "media" folder with the same bug title.

A snippet of the HTML file where the Bootstrap JavaScript file is
included.

**Notes/Suggestions:**

\- Verify the correctness of the Bootstrap JavaScript file path.

\- Ensure that the Bootstrap version aligns with the jQuery version and
is loaded after jQuery.

\- Confirm that no network issues are preventing the proper loading of
the Bootstrap JavaScript file.

\- Check for file corruption by downloading the Bootstrap JavaScript
file again from the official source.

Severity/Priority:

\- Severity: High

\- Priority: High (as it affects the core functionality of the
application)

**A screenshot has been provided in the "media" folder with the same bug title.

**Log: Uncaught SyntaxError: Unexpected token '\<' (at
bootstrap.min.js:1:1)**
