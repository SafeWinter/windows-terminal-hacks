# Section 1 Introduction

## Ch01 Getting started with the new Windows Terminal

> **terminal** vs **shell**
>
> - **terminal**: is essentially "what you see" when using the command line
> - **shell**: doesn't have a UI; it's a command-line program. require a terminal to collect input and display output
> - `cmd.exe` and `powershell.exe` will implicitly start the `conhost.exe` terminal

![image-20211125231206874](F:\Courses\winTerminal\imgs\s1\s1c1.png)



New features of Windows Terminal:

- modern UI (acrylic effect, Cascadia Code font, Powerline glyphs etc.)
- flexible JSON-based customization system
- open source: https://github.com/microsoft/terminal/



Q: How to update Windows Terminal automatically?
A: inside the Microsoft Store app, enable automatic updates by going to **Settings** and select **Update apps automatically**

![image-20211125232913231](F:\Courses\winTerminal\imgs\s1\s1c1-2.png)





How to Launch Windows Terminal: Press `wt` + <kbd>enter</kbd> from:

1. Start menu
2. Run dialogue
3. Windows Explorer location bar
4. task bar: <kbd>Win</kbd> + `1`, <kbd>Win</kbd> + `2`, ...
5. right click: `Open in Windows Terminal` option



Open Windows Terminal on full screen: (`-F` flag)

```shell
$ wt -F
```





## Ch02 Learning the Windows Terminal UI

Get rid of <kbd>Ctrl + Tab</kbd>, please. 

Get used to the **terminal tabs**, just like in your Chrome or Firefox browser.



Some useful shortcuts for the **tabs**:

<kbd>Ctrl + Shift + T</kbd>: open a new tab with our default shell

<kbd>Ctrl + Shift + W</kbd>: close the current tab

<kbd>Ctrl + Shift + Space</kbd>: open the new shell dropdown menu. The list would grow automatically, and the following shortcuts would be available: <kbd>Ctrl + Shift + 1</kbd>, <kbd>Ctrl + Shift + 2</kbd>, ...

<kbd>Ctrl + Shift + D</kbd>: open a "duplicate" of the currently active tab

<kbd>Ctrl + Tab</kbd>: navigate to the next tab

<kbd>Ctrl + Shift + Tab</kbd>: navigate back

<kbd>Ctrl + Alt + [1-9]</kbd>: activate the tab at that index

Besides, Tabs also support **drag-and-drop reordering**



Set tab color: Right-click on a tab and select `Color…` to open a color picker



Some useful shortcuts for the **panes**:

- <kbd>Alt</kbd> + clicking the plus button: open the default shell in a new pane
- <kbd>Alt</kbd> + selecting a shell from the new shell dropdown menu: open that shell in a new pane.
- <kbd>Alt + Shift + D</kbd>: duplicate the current shell into a new pane (while new tabs are opened by <kbd>Ctrl</kbd>)
- <kbd>Alt + Shift + Minus</kbd>: open a new default shell horizontally (create a **horizontal border**)
- <kbd>Alt + Shift + Equals</kbd>: open a new pane vertically (create a **vertical border**)
- <kbd>Alt + Arrow</kbd>: (the `Up`, `Down`, `Left`, or `Right` arrows) will switch to the pane in the direction of the arrow key, and any pane can be clicked with the mouse to activate it.
- <kbd>Alt + Shift + Arrow</kbd>: resize the active pane in that direction
- <kbd>Ctrl + Shift + W</kbd>: close a pane