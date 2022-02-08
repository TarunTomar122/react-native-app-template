# react-native-app-template
wanna use?  

1. npx react-native init urappname
2. copy paste everything bt the android, ios, app.json etc.
3. rename in package.json as per ur app name.
4. create a firebase project and add google-signin by adding a google-services.json file in android folder.
5. also update the top level build.gradle and app/build.gradle
6. if u need to get a sha1 for ur firebase just run the following command -      
    keytool -list -v -keystore ./android/app/debug.keystore -alias androiddebugkey -storepass android -keypass android
7. do npm install and npm run android
8. incase of any error enjoy fixing :)
