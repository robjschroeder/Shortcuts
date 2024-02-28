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
   
![Screenshot 2024-02-28 at 9 42 46 AM](https://github.com/robjschroeder/Shortcuts/assets/23343243/ea7eee56-f847-4da3-b427-5c59723b2be2)


## Shortcuts:

Within the Shortcuts app, I have organized my Jamf Pro shortcuts into two containers, `Jamf Pro Modules` and `Jamf Pro Actions`

The `Jamf Pro Modules` contains shortcuts that are meant to be re-used and called by the `Jamf Pro Actions` shortcuts. The `Jamf Pro Actions` contains the individual asks that you are requesting from Jamf Pro. 

### Jamf Pro Modules
<img width="1112" alt="Screenshot 2024-02-28 at 9 46 28 AM" src="https://github.com/robjschroeder/Shortcuts/assets/23343243/0c09e08c-a898-413a-866b-1300496094cf">

### Jamf Pro Actions
<img width="1112" alt="Screenshot 2024-02-28 at 9 46 33 AM" src="https://github.com/robjschroeder/Shortcuts/assets/23343243/2c0221e2-8d79-48d9-b2d0-bfc259339136">

### Links to Shortcuts

#### Jamf Pro Modules
[Mac/Device - Get Serial](https://www.icloud.com/shortcuts/1686e78913784e85bf11e335a64d759e)

[JPAPI - Get Access Token - API Role/Client](https://www.icloud.com/shortcuts/7dfdfb2bfdea4249ab03a2f4f1d705c5)

[JPAPI - Invalidate Token](https://www.icloud.com/shortcuts/5f028eeeaceb49dca864aef51ad9de9d)

[JPAPI - Device - Choose Command From List](https://www.icloud.com/shortcuts/2ac6a2030e6b4be6ad6da25128221f28)

[JPAPI - Get Device Record From Serial](https://www.icloud.com/shortcuts/27f49bce7f4f4f3ca42ef15c3727770f)

[JPAPI - Get User Record From Username](https://www.icloud.com/shortcuts/2c94c46e1ef04db595084082f470cf71)

[JPAPI - Mac Choose Command From List](https://www.icloud.com/shortcuts/4e4c7e024edd467d86f1a730fb489a99)

[JPAPI - Get Computer Record From Serial](https://www.icloud.com/shortcuts/50012e07bcba4e53b1d72287f0c10771)

[JPAPI - Get Server Version](https://www.icloud.com/shortcuts/90b4424213234e9fa666c928524c2299)

[JPAPI - Get Server Start Up Status](https://www.icloud.com/shortcuts/38ce68b544f44673a0f5fe6d4c23cc47)

[JPAPI - Get Server Basic Information](https://www.icloud.com/shortcuts/4e2e1b2e6bd044dcb65f69e919a86343)

[JPAPI - Get Activation Code](https://www.icloud.com/shortcuts/5931af380b304cf0b372b550202c4752)

[JPAPI - Get Inventory Information](https://www.icloud.com/shortcuts/0094136266c14a17a55be2743309fbb5)

[JPAPI - Get Notifications](https://www.icloud.com/shortcuts/a71488a7c49a4e39ad7849a697f17966)

#### Jamf Pro Actions
[Mac - Add Computer to Static Group](https://www.icloud.com/shortcuts/e2fc2d279fe84b5f80945e9a92aabe1a)

[Mac - Get Computer & User Info](https://www.icloud.com/shortcuts/9f2345e8ec25453684d3dfed3e2c6456)

[Mac - Send Command](https://www.icloud.com/shortcuts/b0d99eacf2cc43c1b3ad6027b067c0af)

[Mac - Redeploy Jamf Framework](https://www.icloud.com/shortcuts/f5871be6537c47da8dd0348d1af7fb2e)

[Mac - Delete Computer Record](https://www.icloud.com/shortcuts/5d87aa712f2149e299517e61a3973669)

[Device - Get Device & User Info](https://www.icloud.com/shortcuts/a702b39c25664952a4c09a52ab6f4ad4)

[Device - Send Command](https://www.icloud.com/shortcuts/af53c1b0b5ac45a9872c18bf622d15ff)

[Get Jamf Pro Server Information](https://www.icloud.com/shortcuts/78f0cc6d3f5045af8bddc137ba57a037)
