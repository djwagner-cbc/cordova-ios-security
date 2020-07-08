# cordova-plugin-ios-security
forked from `cordova plugin add https://github.com/robertklein/cordova-ios-security.git` to fix npm download issue

It will add the following part to the `*-Info.plist` file during build process:

    <key>NSAppTransportSecurity</key> 
    <dict>
      <key>NSAllowsArbitraryLoads</key> <true/> 
    </dict>
