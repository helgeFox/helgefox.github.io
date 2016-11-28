##FOX Publish stuff
-----------------------------------------

### Sublime Text

####Package Control

You need to have a package called Package Control installed. This is a plugin for Sublime Text that manages other packages for you. From Package Control you can manage (install/uninstall/update and much more) all your sublime plugins. Here's how to get started:
* Open Sublime Text (2 or 3).
* Go to `View->Show Console`
* Visit [packagecontrol.io][] and copy the text from the corresponding tab (sublime text 2 or 3).
* Copy selected text and paste into Sublime Text console (the field at bottom of Sublime Text Window that appeared during step two).
* Hit `Enter`, wait a couple of seconds and you should see a message saying Package Control has been installed.
* (Optionally) go to `View->Hide Console` to free up screen real estate.

[packagecontrol.io]: http://packagecontrol.io/installation

####FOX Repo

Add a new repository to package control:
* In Sublime Text hit `Ctrl+Shift+P` (or `Cmd+Shift+P` on Mac).
* Type in `add repository`.
* You should see a list of options and one that says "Package Control: Add Repository". This is the one.
* Hit `Enter`.
* A textfield reveals towards the bottom of the window Here you should type or copy-paste this url `https://raw.githubusercontent.com/helgeFox/FOX-sublime-repo/master/repository.json` into it and hit `Enter`.
* All Sublime Text Plugins specific to FOX Publish employees should now be available for installation through package control, as any other package, though some packages are dependent on a specific version of Sublime Text. Here is a list of packages (and their dependencies).
	* [IndentXml][] any
	* [GetImportXml][] st3

[IndentXml]: https://github.com/helgeFox/fox-indent-xml
[GetImportXml]: https://github.com/helgeFox/fox-getimportxml
