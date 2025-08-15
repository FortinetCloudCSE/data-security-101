---
title: "Use Case 5"
linkTitle: "Use Case 5"
weight: 5
---

{{% notice %}} ### Generate a warning prompt for any file downloaded from OneDrive

{{% /notice %}}


1. Open the policy group created in use case 2 (if not already open)

2. Click “Add policies”

    ![case5_1](003_lab_use_cases_images/case5_1.png)

3. Enter “download” into the “Search” text box OR expand “Browser templates” and select “Sensitive file downloaded”

    ![case5_2](003_lab_use_cases_images/case5_2.png)

4. Change the policy name to “jsmith – Warn any file downloaded from OneDrive” where “jsmith” is your first initial and last name.

5. Scroll down to “Website Parameters” and click into “Select assets or define filters” under “SaaS apps”

   ![case5_3](003_lab_use_cases_images/case5_3.png)

6. Click “Select from the SaaS app inventory”

   ![case5_4](003_lab_use_cases_images/case5_4.png)

7. Change the radio button to “Prohibit listed SaaS apps” and click “Add apps”

   ![case5_5](003_lab_use_cases_images/case5_5.png)

8. Enter “one” into the “Filter by SaaS app name” text box and select “Microsoft 365 OneDrive” and “Microsoft OneDrive” by placing checks in the box. Click “Add apps”

   ![case5_6](003_lab_use_cases_images/case5_6.png)

9. Click “Done” to add the apps to the policy

   ![case5_7](003_lab_use_cases_images/case5_7.png)

10. Expand “Action configuration” and enable “Display message. Enter “Use case 5” in the “Title” text box. Enter “Use case 5 – Warn any file downloaded from OneDrive” in the “Body” text box. Optionally, enable the other options in the “Display message” area if desired.

   ![case5_8](003_lab_use_cases_images/case5_8.png)

11. Scroll down and click “Save and exit” in the lower right hand corner.

12. You should now see the newly created policy in the window
