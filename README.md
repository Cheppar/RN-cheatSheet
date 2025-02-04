# Expo Scripts
scripts to create an aab to apk.
refer to expo docs  for updates.
#### create your project
` npx create-expo-app@latest `

#### Build your prototype
 
` eas build -p android `

#### Convert AAB to  APK

  `eas build -p android --profile preview`

#### Submit to AppStore

`eas submit --platform android `
