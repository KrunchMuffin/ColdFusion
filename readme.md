# Coldfusion package for Sublime Text 2

* Coldfusion syntax highlight.
* Auto Inserts closing hash #
* Less than  (<) triggers cfml auto complete
* Keyboard Shortcuts

### Keyboard Shortcuts
* ctrl+shift+3 `<cfoutput>#SELECTION#</cfoutput>`
* ctrl+shift+o `<cfoutput>SELECTION</cfoutput>`
* ctrl+alt+r `<cfscript>SELECTION</cfscript>`
* ctrl+alt+d  `<cfdump var="#SELECTION#">`
* ctrl+shift+m  `<!--- SELECTION --->`

## Installation

If you are a git user, the best way to install this bundle and keep up to date is to clone the repo directly into your `Packages` directory in the Sublime Text 2 application settings area.

### Using Git

Go to your Sublime Text 2 `Packages` directory and clone the repository using the command below:

    git clone https://github.com/SublimeText/ColdFusion "ColdFusion"

### Download Manually

* Download the files using the GitHub .zip download option
* Unzip the files and rename the folder to `Coldfusion`
* Copy the folder to your Sublime Text 2 `Packages` directory

### Package Control

* Follow instructions on http://wbond.net/sublime_packages/package_control
* Install using Package Control: Install > ColdFusion package

##Notes
* CFSCript highlighting is a work in progress for CFCs (trying to make GoTo Symbol (Ctrl+Shift+R) work)
* cfml_completions.py Auto Complete will only work with Sublime Text 2 Build 2151 or greater
* Not all tag and function snippets have been ported
