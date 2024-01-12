**Bug Report 1: Display Issue in Education Tab**

**Summary:** <span class="mark">The first education card is cut off
after adding multiple education cards and the page truncates the
beginning of the data upon returning to the tab.</span>

**Description:** After entering data for four different colleges or
universities, revisiting the Education tab reveals that the information
for the first college is cut off from the beginning of the page.

**Preconditions:**

1.  The candidate has logged into the app.

2.  The candidate has listed information for four college educational
    institutions.

**Environment/Reproduced on:**

- Device: Android Huawei P30 Lite

- Operating System: Android 9.0 (Pie) + EMUI 9.1

**Priority/Severity:**

- **Priority:** Low

- **Severity:** Low

**Steps to Reproduce:**

1.  Navigate to the Education tab.

2.  Enter data for four educational institutions.

3.  Return to the home page.

4.  Revisit the Education tab and observe the display.

**Expected Result:** Educational data should appear complete without any
truncation from the beginning of the page.

**Actual Result:** The educational data is cut off from the beginning of
the page, leading to an incomplete display.

**Attachment:**

**A screenshot has been provided in the "media" folder with the same bug title.

----------------------------------------------------------------------------------------------------------------------------

**Bug Report 2: Non-Clickable "Add Education" Button**

**Summary:** Profil-Education-"Add education" is disabled after adding 4
educational institutions

**Description:** If the candidate has already added four educational
institutions and tries to add another, the "Add Education" button is
non-clickable, hindering the addition of further educational entries.

**Preconditions:**

1.  The candidate has added four education institutions.

**Environment/Reproduced on:**

- Device: Android Huawei P30 Lite

- Operating System: Android 9.0 (Pie) + EMUI 9.1

**Priority/Severity:**

- Priority: Medium

- Severity: Moderate

**Steps to Reproduce:**

1.  Launch the MatchIT app and log in.

2.  Navigate to the Education tab.

3.  Click on the "Add Education" button.

**Expected Result:** Tapping the "Add Education" button should enable
the user to add more education entries.

**Actual Result:** The "Add Education" button is disabled.

**Attachment:** Video has been provided in the QA portfolio folder with
the same bug title.

**Attachment:**

**A screenshot has been provided in the "media" folder with the same bug title.

----------------------------------------------------------------------------------------------------------------------------

**Bug Report 3: Decreasing Number of Selected Technologies**

**Summary:** Clicking a technology (e.g. Amazon Aurora) checkbox reduces
the total number of selected technologies.

**Description:** If the candidate has already added 20 technologies and
attempts to click on the "Amazon Aurora" checkbox, continuing to click
will decrease the total count of selected technologies, possibly
resulting in negative numbers such as "-1".

**Preconditions:**

- The application has been downloaded from Google Play.

- The candidate has logged into the app.

- The candidate has listed twenty technologies.

**Environment/Reproduced on:**

- Android Huawei P30 Lite, OS: Android 9.0 (Pie) + EMUI 9.1

**Priority/Severity:**

- **Priority:** High

- **Severity:** Major

**Steps to Reproduce:**

1.  Launch the MatchIT app and log in.

2.  Navigate to the Technologies tab.

3.  Select twenty technologies by clicking on the checkboxes.

4.  Attempt to click on the "Amazon Aurora" checkbox.

5.  Observe the behavior by clicking multiple times until negative
    numbers appear in the selected technologies.

**Expected Result:** Tapping on the "Amazon Aurora" checkbox should
prompt a message informing the user that the maximum number of selected
technologies have been reached.  
If the candidate wishes to add more, they should first deselect one
technology to select another. Alternatively, consider increasing the
maximum allowed selected technologies.

**Actual Result:** Clicking on the "Amazon Aurora" checkbox decreases
the count of selected technologies with each click.  
Multiple clicks may lead to negative numbers, which should not be
allowed.

**Attachment:**

**A screenshot has been provided in the "media" folder with the same bug title.

----------------------------------------------------------------------------------------------------------------------------

**Bug Report 4: Display issue in skills and badges**

**Summary:** The last 2 skills and badges are"Cut of"/ Shrinked

**Description:** When scrolling to the bottom of the Skills and Badges
tab, two skills are visible, but their images are cut off. It is
uncertain whether there are additional skills because the images for the
skills are incomplete.

**Preconditions:**

1.  The application has been downloaded from Google Play.

2.  The candidate has logged into the app.

3.  The candidate is on the Skills and Badges page.

**Environment/Reproduced on:**

- Device: Android Huawei P30 Lite

- Operating System: Android 9.0 (Pie) + EMUI 9.1

**Priority/Severity:**

- **Priority:** Low

- **Severity:** Low

**Steps to Reproduce:**

1.  Launch the MatchIT app and log in.

2.  Navigate to the Skills and Badges tab.

3.  Select all skills by clicking on the checkboxes.

4.  Scroll down the page.

5.  Observe the images/elements for the last two skills.

**Expected Result:** The images of the last two technologies should be
obvious, clarifying whether all skills are displayed to the candidate.
By scrolling, it should be evident if there are no more skills and
badges.

**Actual Result:** The page needs to be completed, with parts of the
images for the last two skills missing. The candidate is still
determining if additional skills and badges exist.

**Attachment:**

**A screenshot has been provided in the "media" folder with the same bug title.

----------------------------------------------------------------------------------------------------------------------------

**Bug Report 5: Alignment Issue with Table Background Color**

**Summary:** The table's background color is not correctly aligned and
is absent in the latter half of the screen during vertical scrolling.

**Description:** While a recruiter is on the advertisement page and
vertically scrolls, the background color fails to display properly.

**Preconditions:**

1**.** The recruiter has logged into the MatchIT app.

2**.** The recruiter is currently on the advertisement page.

**Environment/Reproduced on:**

\- Device: Android Huawei P30 Lite

\- Operating System: Android 9.0 (Pie) + EMUI 9.1

**Priority/Severity:**

**- Priority:** Low

**- Severity:** Low

**Steps to Reproduce:**

1**.** Launch the MatchIT app and log in as a recruiter.

2**.** Navigate to the advertisement page.

3**.** Horizontally scroll to the right to inspect the page layout.

4**.** Observe the absence of background color in the second half of the
screen.

**Expected Result:** The background color aligns correctly, covering all
elements on the page.

**Actual Result:** The table's background color is not visible on the
entire screen.

**A screenshot has been provided in the "media" folder with the same bug title.
