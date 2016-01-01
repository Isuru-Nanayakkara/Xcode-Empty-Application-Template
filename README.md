Xcode Empty Application Template
================================

In Xcode 6 onwards, the Empty Application template has been removed. This is a blow for us who still want and like to use xib files.

But no need to fret! It isn't difficult to add it back.


## Install

##### [Alcatraz](https://github.com/supermarin/Alcatraz)
- Simply search for *Xcode Empty Application Template*.
- Click on the icon on the left to install.
- Restart Xcode.


##### Manually
- Clone or download the repo. 
- Copy the `Empty Application.xctemplate` directory to the following location, `{Xcode.app}/Contents/Developer/Platforms/iPhoneOS.platform/Developer/Library/Xcode/Templates/Project Templates/iOS/Application/`.
- Restart Xcode.
or
- Clone or download the repo.
- Create the `~/Library/Developer/Xcode/Templates/Project Templates/Application/` directory
- Copy the `Empty Application.xctemplate` directory to `~/Library/Developer/Xcode/Templates/Project Templates/Application/` 
- Restart Xcode. 

The second method will avoid Apple overwriting your template but is a per user solution.
