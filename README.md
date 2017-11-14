vscode-nb-keybinding
===

This package provide a basic subset of NetBeans keybinding for VSCode.

Feel free to suggest new combination.

Keymap
===
|key                       | command            |
|--------------------------|--------------------|
|alt+shift+f               |editor.action.format|
|ctrl+shift+c              |editor.action.commentLine|
|ctrl+e                    |editor.action.deleteLines|
|ctrl+shift+down           |editor.action.copyLinesDownAction|
|ctrl+shift+up             |editor.action.copyLinesUpAction|
|alt+shift+down            |editor.action.moveLinesDownAction|
|alt+shift+up              |editor.action.moveLinesUpAction|
|ctrl+1                    |workbench.view.explorer|
|ctrl+shift+1              |workbench.files.action.focusOpenEditorsView|
|ctrl+shift+0              |workbench.action.focusActiveEditorGroup|
|ctrl+u u                  |editor.action.transformToUppercase|
|ctrl+u l                  |editor.action.transformToLowercase|
|ctrl+shift+numpad_add     |editor.unfoldAll|
|ctrl+shift+numpad_subtract|editor.foldAll|
|ctrl+shift+w              |workbench.action.closeEditorsInGroup|


Other commands (not from NetBeans):

|key            | command            |
|---------------|--------------------|
|alt+up         |editor.action.insertCursorAbove|
|alt+down       |editor.action.insertCursorBelow|

Disabled
|key            | command            |
|---------------|--------------------|
|ctrl+shift+w   |workbench.action.closeWindow|
