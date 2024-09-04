# Getting Started

this is a short tutorial on how to adapt the UI in standard work zone. Its a way to change standard views, adapt filters and more.

## How to adapt your UI in Work Zone

### 1. Step/ set flexEnabled = true
Make sure that your deployed apps have **flexEnabled** set to **true**

```json
"sap.ui5": {
    "flexEnabled": true,
    "dependencies": {
      "minUI5Version": "1.120.8",
      "libs": {
        "sap.m": {},
        "sap.ui.core": {},
        "sap.ushell": {},
        "sap.fe.templates": {}
      }
    },
...
```

### 2. Step/ create a role collection

The 2nd step is to create a new role collection and assign the roles **AdminFlexKeyUser** and **FlexKeyUser** to it. <br>
Don't forget to assign your user to this role collection as well.

![Bildschirmfoto 2024-09-04 um 14 37 16](https://github.com/user-attachments/assets/b57e1804-11fd-4ff9-9899-790281124193)

### 3. Step/ set Key-User adaptations = true

the next step is to set the **UI Adaptation by Key User** to true. You can find this setting by opening the **Website-Editor** in work zone. 

![Bildschirmfoto 2024-09-04 um 14 42 18](https://github.com/user-attachments/assets/fa42adb0-36a8-48ac-a638-c02b91d4a68c)

*** final Step/ adapt the UI

finaly you can open your WZ website and navigate to the app you want to adapt. Click on the user icon in the top right and select **Adapt UI**. <br> 
Your website will open in the edit mode and you can make your changes. Have fun! 

![Bildschirmfoto 2024-09-04 um 14 46 35](https://github.com/user-attachments/assets/40445e8c-9f49-4349-b317-46c44fbe185e)

# if you have questions

contact niklas.ennser@agilita.ch
