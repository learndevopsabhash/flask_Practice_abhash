**Jenkins CI-CD**

Step 1: Login in to HeroVired Jenkins Portal

**Url** - <https://jenkinsacademics.herovired.com/>

![Image: image_001.png](./Jenkins%20CI_images/image_001.png)

Step 2: Once Login Successfully -> Home Page will Open
![Image: image_002.png](./Jenkins%20CI_images/image_002.png)

Step 3: Click on “**+ New Item**”

![Image: image_003.png](./Jenkins%20CI_images/image_003.png)

a. Enter an item name - Abhash-CICD

b. Select an item type – Pipeline

c. Then – Ok

d. On next page – Fill some **Description**

**![Image: image_004.png](./Jenkins%20CI_images/image_004.png)**

e. Go down and select Pipeline Definition – **Pipeline script form SCM** –> **SCM** -> **Git -> Save & Apply.**

![Image: image_005.png](./Jenkins%20CI_images/image_005.png)

f. **Branches to build** -> \*/main & **Script Path** -> Jenkinsfile

![Image: image_006.png](./Jenkins%20CI_images/image_006.png)

![Image: image_007.png](./Jenkins%20CI_images/image_007.png)

Step 4. Setup Node for Pipeline

# a. Go to Setting tab -> Nodes -> New Node

![Image: image_008.png](./Jenkins%20CI_images/image_008.png)

# b. Fill Details:

Name, Description, Remote root directory, Launch method, Host

![Image: image_009.png](./Jenkins%20CI_images/image_009.png)

Step 5: Create Secret for MONGO\_URI and SECRET\_KEY for Pipeline.

![Image: image_010.png](./Jenkins%20CI_images/image_010.png)

Step 6: Configure Extended E-mail Notification for pipeline email notification.

I use default email.

![Image: image_011.png](./Jenkins%20CI_images/image_011.png)

Step 7:Create Pipeline in Jenkinsfile.

![Image: image_012.png](./Jenkins%20CI_images/image_012.png)

![Image: image_013.png](./Jenkins%20CI_images/image_013.png)![Image: image_014.png](./Jenkins%20CI_images/image_014.png)![Image: image_015.png](./Jenkins%20CI_images/image_015.png)

![Image: image_016.png](./Jenkins%20CI_images/image_016.png)![Image: image_017.png](./Jenkins%20CI_images/image_017.png)

Step 8: Once Pipeline is completed push into Github

![Image: image_018.png](./Jenkins%20CI_images/image_018.png)

Step 9: Check Pipeline Result:

![Image: image_019.png](./Jenkins%20CI_images/image_019.png)

![Image: image_020.png](./Jenkins%20CI_images/image_020.png)![Image: image_021.png](./Jenkins%20CI_images/image_021.png)![Image: image_022.png](./Jenkins%20CI_images/image_022.png)![Image: image_023.png](./Jenkins%20CI_images/image_023.png)

![Image: image_024.png](./Jenkins%20CI_images/image_024.png)

![Image: image_025.png](./Jenkins%20CI_images/image_025.png)![Image: image_026.png](./Jenkins%20CI_images/image_026.png)

![Image: image_027.png](./Jenkins%20CI_images/image_027.png)

![Image: image_028.png](./Jenkins%20CI_images/image_028.png)

![Image: image_029.png](./Jenkins%20CI_images/image_029.png)

![Image: image_030.png](./Jenkins%20CI_images/image_030.png)