# React-native-detox
How to install
  1. Install Xcode
  
 

  2. brew -h ( to see all the installe
  2. brew upgrade
  3. react-native init detox
  to check the node version installed:
    5. node -v
 comond to check react native installed in to the system  
  6. react-native -v
  7. brew tap wix/brew: add the channel 
  
  To updates the homebrew
   8. brew tap wix/brew
   
  9. brew install applesimutils 
  
  To updates detox cli globali
    npm detox -g detox-cli
  Install to react native
    npm install -g react-native-cli
   
   Initiate the react native project:
    react-native init detoxprojectname
    
    • cd "~/workspace/detoxproject" && npx react-native run-ios
    - or -
    • Open detoxproject/ios/detoxproject.xcworkspace in Xcode or run "xed -b ios"
    • Hit the Run button

  Run instructions for Android:
    • Have an Android emulator running (quickest way to get started), or a device connected.
    • cd "/Users/vinodvishwakarma/workspace/detoxproject" && npx react-native run-android
    
    To add detox dependency:
      yarn add detox -d
    To add mocha 
      yarn add mocha -d
    To initislize mocha
      detox init -r mocha
      
  =================
      Update them from Software Update in System Preferences or run:
      softwareupdate --all --install --force

    If that doesn't show you an update run:
     sudo rm -rf /Library/Developer/CommandLineTools
     sudo xcode-select --install
  ====================
