---
title: "Lab Access Instructions"
linkTitle: "Lab Access Instructions"
weight: 1
---

### Management Console Access Instructions

{{% notice warning %}} Please note that the FortiDLP management console is a shared environment. Any changes made can impact other users if not properly scoped via labels. Please see the "Lab Rules of Engagement" page before making any changes.{{% /notice %}}

1)  Open your preferred browser (Chrome, Edge, or Firefox) and navigate to:

https://fortidlp-training.reveal.nextdlp.com/

2)  Login to FortiDLP with the course credentials you received via the email address you used to register for the course.

    ![consoleAccess1](001_lab_access_instructions_images/vm_access_3.jpg)

{{% notice note %}} If you did not receive or cannot find the email with your login credentials, notify a course instructor who will initiate a "re-send" of the credentials. {{% /notice %}}

{{% notice tip %}} Your user name is your first initial followed by your last name... NOT your email address (ex. John Smith would be "jsmith") {{% /notice %}}

### Virtual Endpoint Access and Configuration Instructions

1)	Enter the URL for your specific assigned VM device.

2)	Enter your assigned “username” and “password” in the appropriate fields and click "Login". The Username identifies your device:
  
    ![labAccess1](001_lab_access_instructions_images/vm_access_1.jpg)

3)	On the VM device open the Chrome Browser:

    ![labAccess2](001_lab_access_instructions_images/vm_access_2.jpg)

4)	Enter the FortiDLP Training Platform URL in to the Chrome browser:

https://fortidlp-training.reveal.nextdlp.com/

5)	Logon to FortiDLP with your assigned course credentials:

    ![labAccess3](001_lab_access_instructions_images/vm_access_3.jpg)

6)	Click the "Admin" icon:

    ![labAccess4](001_lab_access_instructions_images/vm_access_4.jpg)

7)	On Admin page click “Agent Deployment” in the left hand pane:

    ![labAccess5](001_lab_access_instructions_images/vm_access_5.jpg)

8)  Expand the "XPERTS2025" enrollment code and click "Copy code" then click "Download" to obtain the agent installer:

    ![labAccess10](001_lab_access_instructions_images/vm_access_10.jpg)

9)  Go to "Downloads" folder and double click the agent installer package downloaded in the previous step

10) Accept the terms in the license agreement and click "Next:"

    ![labAccess13](001_lab_access_instructions_images/vm_access_13.jpg)

11) Paste the enrollment code copied in step 8 into the text box under "Install with a code" and click "Install:"

    ![labAccess15](001_lab_access_instructions_images/vm_access_15.jpg)

12) When prompted, click "Finish" to complete the install:

    ![labAccess16](001_lab_access_instructions_images/vm_access_16.jpg)

{{% notice warning %}} When prompted, DO NOT reboot the machine at this point! {{% /notice%}}

13) Click "Nodes" in the left pane of the management console and click "Table" to confirm that your agent is reporting in successfully:

    ![labAccess18](001_lab_access_instructions_images/vm_access_18.jpg)

14) Reboot your VM and log in again.

15) CONGRATULATIONS! You have successfully installed the FortiDLP agent on your lab virtual machine.