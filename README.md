# SH4RE-ECE496
This repository holds the Xcode project for SH4RE.

## Developer Environment
Required Tools:
- Xcode 14.1 (Link [here](https://developer.apple.com/services-account/download?path=/Developer_Tools/Xcode_14.1/Xcode_14.1.xip), requires Apple ID login)
	- requires MacOS 12.5+
- HomeBrew (or equivalent package manager)
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
- GitHub CLI
	- `brew install gh`
	- Once installed, login to your github account using `gh auth login` and following the prompts. Note: it is easiest to login using HTTPS via a web browser. 

## File Structure

└── SH4RE
    ├── SH4RE (main project folder)
    │ ├── FirebaseDB.swift (this is where database connection is established)
    │ ├── MainView.swift (this is the main content view)
    │ └── SH4REApp.swift (main file)
    ├── SH4RE.xcodeproj (xcode project, double click this to start xocde)
    ├── SH4RETests (unit tests)
    └── SH4REUITests (UI unit tests)
