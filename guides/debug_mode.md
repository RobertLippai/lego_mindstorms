
# Enable debug mode on Macos

From Finder click **Go** then click **Go To**

In the Go To window and paste:

`~/Library/Containers/com.lego.retail.mindstorms.robotinventor/Data/Library/Application Support/MINDSTORMS_ROBOTINVENTOR/`

or vis shell `cd ~/Library/Containers/com.lego.retail.mindstorms.robotinventor/Data/Library/Application\ Support/MINDSTORMS_ROBOTINVENTOR/` then `open .`




Now open the **userSettings.json** with a text editor.
![alt text](./src/ms_folder.png?raw=true)

Go to the end of the file, and add the following string:

`,“ui.debug”:true`
so the end of file line looks like ,"ui.consent.DataEssential":true *,“ui.debug”:true}*

![alt text](./src/settings_json.png?raw=true)

Save the file then open the Mindstorms app.
The debug menu now should appear.
![alt text](./src/mindstorms.png?raw=true)
