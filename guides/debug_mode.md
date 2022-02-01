
# Enable debug mode on Macos

From Finder click **Go** then click **Go To**

In the Go To window paste:
*~/Library/Containers/com.lego.retail.mindstorms.robotinventor/Data/Library/Application Support/MINDSTORMS_ROBOTINVENTOR/**


Now open the **userSettings.json** with a text editor.
![alt text](./guides/src/ms_folder.png?raw=true)

Go to the end of the file, and add the following string:
**“ui.debug”:true** 
Make sure to include the quations marks too!
![alt text](./guides/src/settings_json.png?raw=true)

Save the file then open the Mindstorms app.
The debug menu now should appear.
![alt text](./guides/src/mindstorms.png?raw=true)
