# react-native
#create react native app
npm init react-app ./ 
#start it
expo-cli start --tunnel

#publish
expo publish
eas login
eas build:configure
eas build --platform android 
eas build -p android --profile preview
