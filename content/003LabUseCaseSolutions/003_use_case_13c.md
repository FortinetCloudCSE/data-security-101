---
title: "Use Case 13C"
linkTitle: "Use Case 13C"
weight: 15
---

{{% notice %}} Prevent notepad.exe from opening a file containing custom regex pattern

{{% /notice %}}

1. Open the policy group created in use case 2 (if not already open)

2. Click “Add policies” 

    ![case13c_1](003_lab_use_cases_images/case13c_1.png)

3. Enter “opened” into the “Search” text box OR expand “File templates” and select “Sensitive file opened”

   ![case13c_2](003_lab_use_cases_images/case13c_2.png)

4. Change the policy name to “Prevent notepad.exe from opening a file containing custom regex pattern” where “jsmith” is your first initial and last name.

5. Scroll to “Process parameters.” Click the text box under “Binary names”

6. Select “Prohibit listed binaries.” Remove the existing entries from “Custom values” and enter “notepad.exe”. Click “Done”

   ![case13c_3](003_lab_use_cases_images/case13c_3.png)

7. Scroll to “File parameters” and uncheck the selected “Policy assets” to clear them. Click “Done.” 

   ![case13c_4](003_lab_use_cases_images/case13c_4.png)

8. Scroll to “Content inspection parameters.” Click the text box under “Content inspection parameters.”

   ![case13c_5](003_lab_use_cases_images/case13c_5.png)

9. Enter “jsmith” into the “Filter by policy asset name” search box where “jsmith” is your first initial and last name. Select the custom regex pattern created in use case 13b. Click “Done.”

   ![case13c_6](003_lab_use_cases_images/case13c_6.png)

10. Expand “Action configuration” and enable “Kill process” and “Display message.” Enter “Use case 13c” in the “Title” text box. Enter “Use case 13c – Prevent notepad.exe from opening a file containing custom regex pattern” in the “Body” text box. Optionally, enable the other options in the “Display message” area if desired.

   ![case13c_7](003_lab_use_cases_images/case13c_7.png)

11. Scroll down and click “Save and exit” in the lower right hand corner.