# Xcode-IntelliJ-Keybinds
IntelliJ Keybinds for Xcode. Not all the keybindings are migrated yet. 

# Actual Keybindinds

| IntelliJ | xCode | New shortcut |
| :---         | :---           | :---          |
| Duplicate line   |      | ⌘+D    |
| Duplicate selection     |        | ⌘+D      |
| Delete line     | CTRL+K       | ⇧+⌘+L      |
| Delete selection     | CTRL+K       | ⇧+⌘+L      |
| Build     | CTRL+B       | ⌘+F9      |
| Indent code     | CTRL+I       | ⌘+I      |
| Fold     | ⌥+⌘+←        | ⌘-      |
| Unfold     | ⌥+⌘+→      | ⌘=      |
| Step over    | F6       | F8      |
| Step into    | F7       | F7      |
| Step out     | F8       | ⇧+F8      |

# How to install?
-  Download the `IntelliJ.idekeybindings` file
-  Open your terminal and move to `~/Library/Developer/Xcode/UserData/KeyBindings/
-  Execute `open .` to open the actual folder and copy the `IntelliJDark.xccolortheme` file.
-  Open Xcode
-  Go to `Preferences/Key binding and choose your profile.

It can crash on the first time you import this theme, but after reset XCode it should work like a charm ;)

**Feel free to improve it or add more modifications!! It's a work in progress and not all the bindings from IntelliJ are 100% portable for the reserved use of command ⌘ for modifiers**
