---
title: "Use Case 11"
linkTitle: "Use Case 11"
weight: 11
---

{{% notice %}} Create a "Sequenced Incident" for your device only

{{% /notice %}}

1. Click “Policies” in the left pane of the management console and select “Sequence rules” in the top center of the screen. Click “Create new rule.”

    {{< figure src="case11_1.png" alt="case11_1" >}}

2. Type “jsmith – Sequence detection rule” in the “Name” box and click “Next”

3. Select the following stages and click “Create”</br>
    a. Collection [TA0009]</br>
    b. Exfiltration [TA0010]

   {{< figure src="case11_2.png" alt="case11_2" >}}

4. Click the edit pencil in the “Include” box

   {{< figure src="case11_3.png" alt="case11_3" >}}

5. Select “Specific entities (by label)” and choose your label created in use case 1

   {{< figure src="case11_4.png" alt="case11_4" >}}

6. Click the edit pencil in the “Mandatory stages” box

   {{< figure src="case11_5.png" alt="case11_5" >}}

7. Select “Exfiltration [TA0010]” and click “Save”

   {{< figure src="case11_6.png" alt="case11_6" >}}

8. Click “Operation mode” and click “Enabled” then click “Publish rule”

   {{< figure src="case11_7.png" alt="case11_7" >}}