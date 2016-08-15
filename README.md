# OpenFrameworks OSX template

This is just a template I'm making to try to improve my OpenFrameworks workflow.
It already has a .gitignore file in it (taken from [here](https://github.com/openframeworks/openFrameworks/blob/master/scripts/templates/gitignore/.gitignore)), so it's ready for proper version control,
and it also contains some reminders of commands to run so that I don't have to
run the whole XCode application just to compile the source files.
(note: you still need to have XCode and XCode command line tools installed)

Hopefully in the future I'll add some shader templates and such.

### Commands
Open the project generator (I have an alias in of/apps/myApps)

`open -a projectGenerator`

List all targets, build configurations, and schemes used in project

`xcodebuild -list -project <your_project_name>.xcodeproj`

Build a particular scheme

`xcodebuild -scheme <your_scheme_name> build`

XCode command line commands from [here](https://developer.apple.com/library/ios/technotes/tn2339/_index.html)

After pulling from this repository, remove and replace the origin remote before I accidentally overwrite the template.

`git remote rm origin`
