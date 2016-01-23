# LapTimerLocalizations
This repository contains all localizations for Harry's LapTimer and other apps.

Contents of this project will go into our app's builds regularly. Please feel free to correct existing translations or add new languages. Details on the structure and format of files are available from `UILocalization.pdf`, it is mandatory to read this file before changing files.

<b>How to work on translations?</b>

Files described in `UILocalization.pdf` can be changed and updated individually. They can be found in the language specific folder (`<lang>.lproj`). To allow the use of Linguan (MacOSX application) a Xcode project file is provided in addition
(`LapTimerLocalizations.xcodeproj`). To work with `Linguan`, fork and clone the repository. Once cloned, open `LapTimerLocalizations.xcodeproj` with `Linguan` and all `.strings` files will be presented with localizations side by side.

As described in `UILocalization.pdf`, keys in `.strings` files are mostly the English localization. In case a mapping for a key is missing in e.g. `en.lproj/Localizable.strings`, the app will use the key as the localized value. 

In case you have questions, please contact me by mail (Harry@gps-laptimer.de).

Thanks a lot for your support making Harry's apps the ultimate track solution!

<br>
<i>Harry, January 2016</i>

<br>
Disclaimer: All files included are copyright / intellectual property by Harald Schlangmann. 
Any unauthorized access and reuse is not accepted and will be pursued legally.
