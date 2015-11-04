# GAS-Dialog
Google Apps Script library that provides Add-on styled alerts and prompts.

## Setup

This library is already published as an Apps Script, making it easy to include
in your project. [To add it to your script](https://developers.google.com/apps-script/guide_libraries), do the following in the Apps Script code editor:

1. Click on the menu item "Resources > Libraries..."
2. In the "Find a Library" text box, enter the project key
   `MWPmswuaTtvxxYA71VTxu7B8_L47d2MW6` and click the "Select" button.
3. Choose a version in the dropdown box (usually best to pick the latest
   version).
4. Click the "Save" button.

Alternatively, you can copy and paste the files directly into your script project.

## Getting started

````js

  // This displays a dialog with a YES and NO buttons
  var ui = SpreadsheetApp.getUi();
  
  var response = Dialog.show(
    'Test 3 Title',       // Title
    'Test 3 Message',     // Message
    400,                  // Height
    100,                  // Width
    ui.ButtonSet.YES_NO); // Buttons
    
  Logger.log('Test 3 - PASSED. Reponse: ' + response);
````

See the functions in Dialog.gs for more info.
