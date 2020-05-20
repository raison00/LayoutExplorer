
# DevTools and the Flutter Widget Inspector Layout Explorer
## DevTools UX Punch List 2020 
[Network](https://github.com/flutter/devtools/issues/1980) <br>
[Timeline](https://github.com/flutter/devtools/issues/1964)<br>
[Performance](https://github.com/flutter/devtools/issues/1977)<br>
[Info](https://github.com/flutter/devtools/issues/1957)<br>
[Debugger](https://github.com/flutter/devtools/issues/1972)<br>
[Inspector](https://github.com/flutter/devtools/issues/1984)<br>
[Logging](https://github.com/flutter/devtools/issues/1982)<br>
[Memory](https://github.com/flutter/devtools/issues/1974)<br>
##
## Flutter Layout Explorer:  Using Flutter's Dart DevTools for Resolving the RenderFlex Overflow Errors 
 ![visualization of layout explorer](http://www.feliciachamberlain.com/flutter/devtools/layout-explorer-logo-diagram.png)
 
 >Note: This feature is only available in the alpha version of DevTools written in Flutter. Currently, the Layout Explorer only supports exploration of flex layouts.

* [Flutter Layout Explorer](https://flutter.dev/docs/development/tools/devtools/inspector#using-the-layout-explorer): The Flutter Layout Explorer helps you to better understand Flutter layouts.
* [Layouts in Flutter](https://flutter.dev/docs/development/ui/layout): Widgets are used for both layout and UI elements.
* [flutter_error_studies repo](https://github.com/InMatrix/flutter_error_studies): A repo for collecting case studies of Flutter error messages

### Objective
![render overflow error on mobile device](http://www.feliciachamberlain.com/flutter/devtools/flutter-overflow-issue-phone.png)

* [Flutter Layout & the  RenderFlex overflow error](https://github.com/flutter/flutter-intellij/issues/4089): Provide visual tooling for troubleshooting common Flutter flex layout patterns.


### Gists:  Visualizing Common Layout Issues with Flutter Tools and Solutions
* [Flutter RenderOverflow Errors using CustomMultiChild ](https://gist.github.com/raison00/b11a9a7dedf70500d9fb8bd215d86de6): Sample Overflow Challenge: Using CustomMultiChild Layout to Resolve RenderOverflow Errors
* [Flutter RenderOverflow Solution using CustomMultiChild ](https://gist.github.com/raison00/fb4ce93653187da22f9cfdb9eab7af52): Sample Overflow Solution: Using CustomMultiChild Layout to Resolve RenderOverflow Errors
* [Flutter RenderOverflow Solution using Flexible Widget](https://gist.github.com/raison00/679ad092bdfd5979e766507c1dc7a0e9): Using Flexible Widget to solve render flex overflow errors
* [Flutter RenderOverflow Solution using Expanded Widget](https://gist.github.com/raison00/27f6302019514b0c5f8150f9fdfa6a88): Using Expanded Widget to solve render flex overflow errors
* [Flutter Box Constraints](https://gist.github.com/raison00/311b04d2898178f14766675673dfa16a): Box Constraints Visualization; no text clipping issues/errors but can have a render overflow error in the column
* [Flexible vs NonFlexible Widgets in CustomMultiChildLayout](https://gist.github.com/raison00/2ebedc6a99cd8b5bbe68d6689a4223c8): CustomMultiChildLayout with flexible vs non-flexible widgets

### Open
* [Active: Layout Explorer --> Widget Inspector](https://github.com/flutter/flutter-intellij/issues/4511): Embedding Layout Explorer to the Widget Inspector in IntelliJ
* [Active: Layout Explorer --> IntelliJ](https://github.com/flutter/flutter-intellij/issues/4512): Apply changes to user code from the layout explorer embedded in IntelliJ
* [Active: Layout Explorer --> quick jump to overflow source](https://github.com/flutter/devtools/issues/1546): FR - LayoutExplorer - Add option to quick jump to overflowing widget
* [Active: Will be closed soon](https://github.com/flutter/devtools/issues/1590): DevTools Debugger not available after launching Layout Explorer
* [Active: Style Guidance for DevTools](https://github.com/flutter/devtools/pull/1847): UX guidance for specific aspects of UI/UX DevTools visual standards
* [Active: Theme Inspector](https://github.com/flutter/devtools/issues/483): Visualizing the widgets and elements
* [Active: UX Punch List Item: Consistent Scroll Physics](https://github.com/flutter/devtools/pull/1911): UI changes from a UX review: consistent scroll physics
* [Active: UX Punch List Item: Accessible Color](https://github.com/flutter/devtools/issues/1880): Green status color is too light in the light theme
* [Active: Inspector text color has regressed](https://github.com/flutter/devtools/issues/1931): Changes made to Light Theme: Inspector text color has regressed

### In Queue 
* [Design DevTools Landing Page](https://github.com/flutter/devtools/issues/433): An informational / orientation landing page for DevTools. Having a page like this, perhaps served from /, would address a few workflow issues.
* [Flutter Console Layout Issues: UX Messaging](https://github.com/flutter/flutter/issues/41149): Improve message for the RenderFlex Overflow error
* [Flutter Layout Explorer Contextual UX](https://github.com/flutter/devtools/issues/1546): UX Workflow: Add option to quickly jump to overflowing widget
* [Flutter Visual Search & Browse in IDE](https://github.com/flutter/flutter-intellij/issues/4081): Provide an in-IDE widget search and browsing experience that covers all Flutter stock widgets and a few popular community-generated widgets. Widget preview images and rich descriptions should be readily accessible in the IDE for the user to assess relevance to their tasks.
* [Persist the memory profile timeline](https://github.com/flutter/flutter/issues/44013#issuecomment-596662684): UX Workflow: the memory profile timeline







### Closed
* [Alpha version access to Flutter Inspector Layout Explorer](https://github.com/flutter/devtools/issues/1481): How to access the Flutter Inspector Layout Explorer
