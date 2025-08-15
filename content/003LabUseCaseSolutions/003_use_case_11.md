---
title: "Use Case 11"
linkTitle: "Use Case 11"
weight: 11
---

{{% notice %}} Create a "Sequenced Incident" for your device only

{{% /notice %}}

1. Click “Policies” in the left pane of the management console and select “Sequence rules” in the top center of the screen. Click “Create new rule.”

    ![case11_1](003_lab_use_cases_images/case11_1.png)

2. Type “jsmith – Sequence detection rule” in the “Name” box and click “Next”

3. Select the following stages and click “Create”</br>
    a. Collection [TA0009]</br>
    b. Exfiltration [TA0010]

   ![case11_2](003_lab_use_cases_images/case11_2.png)

4. Click the edit pencil in the “Include” box

   ![case11_3](003_lab_use_cases_images/case11_3.png)

5. Select “Specific entities (by label)” and choose your label created in use case 1

   ![case11_4](003_lab_use_cases_images/case11_4.png)

6. Click the edit pencil in the “Mandatory stages” box

   ![case11_5](003_lab_use_cases_images/case11_5.png)

7. Select “Exfiltration [TA0010]” and click “Save”

   ![case11_6](003_lab_use_cases_images/case11_6.png)

8. Click “Operation mode” and click “Enabled” then click “Publish rule”

   ![case11_7](003_lab_use_cases_images/case11_7.png)