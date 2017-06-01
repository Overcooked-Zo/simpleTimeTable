# simpleTimeTable
Group project for BITP3453 Mobile Application Development

1)	Setup environment variable
-	Right click to My Computer >> Properties >> Advance System Settings >> Environment Variable >> Choose Path and click Edit >> Add :
-	;<your_sdkPath>\android-sdks\tools ;<your_sdkPath>\android-sdks\platform-tools
-	Click OK >> Click Apply

2)	Install Node.js
-	Download the Node.js at https://nodejs.org/en/
-	Run the node-v*.*.*.msi installer
-	After installation finish, run command prompt (run as administrator) 
-	Run:  node –v. By right you should be getting the version of the Node.js 

3)	Install Cordova
-	After successful Node installation, run:  npm install –g cordova

4)	Install Ionic Framework
-	npm install -g cordova ionic

- ionic start simpleTimeTable
- cordova platform add android
- cordova plugin add cordova-sqlite-storage
