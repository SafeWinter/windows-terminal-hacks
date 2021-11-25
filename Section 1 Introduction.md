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



