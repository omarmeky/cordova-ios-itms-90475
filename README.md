# cordova-ios-itms-90475
`cordova plugin add https://github.com/omarmeky/cordova-ios-itms-90475.git`

It will add the following part to the `*-Info.plist` file during build process:

    <key>UIRequiresFullScreen</key> 
    <string>YES</string>
    
This will fix ERROR ITMS-90475: "Invalid Bundle. iPad Multitasking support requires launch story board in bundle..."
