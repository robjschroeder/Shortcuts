# My collection of Shortcuts for the Jamf Pro API

Some of these shortcuts are still a work in progress and are subject to change.

## Requirements: 
1. Download the companion app, Toolbox Pro: [Link](https://apps.apple.com/us/app/toolbox-pro-for-shortcuts/id1476205977)
   - You will **_not_** need to complete the in-app purchase to use the Global Variables feature
2. Open the Toolbox Pro app, choose **_Variables_** from the bottom menu and create the following variables:
   - client_id
      - This will be the value for your Jamf Pro API client id
    - client_secret
      - This will be the value for your Jamf Pro API client secret
    - jamfProURL
      - The value for this variables should be your Jamf Pro URL, i.e. https://server.jamfcloud.com
   - access_token
      - The value for this variable can be kept blank, the shortcuts will populate this variable when your token is generated
   
![IMG_0243](https://user-images.githubusercontent.com/23343243/202490011-3aa80f77-8ed9-44c5-ac0a-47b9b91bd4c4.jpg)


## Shortcuts:

#### Generate a bearer token: [Link](https://www.icloud.com/shortcuts/07523b671101426db826ab8425f5d88a)
- Updated: 11.16.2022

#### Invalidate a bearer token: [Link](https://www.icloud.com/shortcuts/f1ff1388c4324399bb8a5f9117b143a1)
- Updated: 11.16.2022

#### Get computer details by serial: [Link](https://www.icloud.com/shortcuts/0027b4089c3f4349b36daf2460fe2d71)
- Updated: 11.16.2022

#### Redeploy Jamf Framework: [Link](https://www.icloud.com/shortcuts/c1900371d02c47fc9907cbba866e52eb)
- Updated: 11.17.2022
