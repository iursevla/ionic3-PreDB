# Ionic 3 Pre-Populated Database Example
Simple Ionic 3 **pre-populated** database starter project.

## To install this project:
1. Clone project `git clone https://github.com/iursevla/ionic3-PreDB.git`
2. Inside the project folder run: `npm i`
3. Add android platform: `ionic cordova platform add android`
4. Next: `ionic cordova build android`
5. After that: `ionic cordova run android`

### Important Note 
Tested with:
1. Android 5.1.1 - **Physical Device Moto G3 Android 5.1.1**
2. Android 6.0.0 - **Google Nexus 5X - 6.0.0 - API 23 from Genymotion**
3. Android 7.0.0 - **Custom 7.0.0 API 24 from Genymotion**
---

## Start from scratch:
1. Create ionic project e.g., `ionic start projectName blank`
2. Run `npm install --save @ionic-native/sqlite`
3. Add cordova-sqlite-ext: `ionic cordova plugin add cordova-sqlite-ext`
4. Create the database (you can use [DB Browser](http://sqlitebrowser.org/) for this) and copy the .db file to your project `/www` folder.
5. Add code to your `home.ts` folder to open the pre-populated database and then execute some query on a existing table on said database.
6. Run your project on a emulator/device and see the results.