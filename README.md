# ReactNative-SpeechtoText
ios app to show speech to text with mobile.

## Getting started
Either clone or download this, additionally run the following:

`npm install -g react-native-cli`
`react-native init AppName`

cd into your AppName and continue:
`npm install react-native-voice --save`

cd in ios
`pod install`

Open the project AppName -> ios -> yourprj.xcworkspace in Xcode

Click on your project and select info tab which is info.plist
Add rows and add: 
- Privacy-Microphone Usage Description
- Privacy-Speech Recognition Usage Description


See App.js in these files, update yours to match

Compile & run
`react-native run-ios`


