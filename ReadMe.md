# GitWrap

## 1. Description

GitWrap is a very simple GUI-wrapper that integrates with Windows Explorer for `Git for Windows`.  
The integration is done all in user mode context and requires no admin privileges.

The purpose is to take the edge off the steep initial learning curve for people that are used to graphical interfaces when working with files.

GitWrap will add a few context menus that allows the user to right-click in the Explorer to perform the most common Git tasks.  
It will also add the current Git status to the top most File Explorer window.

## 2. Requirements

The prerequisites for applying all features of this repo is

* PowerShell 7.2.x
* Git for Windows
* posh-git

The following provides some enancements to this solution

* TortioseGit

## 3. Limitations

Windows File Explorer only support 16 static context menu per entry.
Yo pass by this limitations, some of the code in [Adam the Automator - How to Build a PowerShell Form Menu for your PowerShell Scripts][5] will be tried out in a future version.

## 4. How do I use this repo?

Apply the reg files and you are done.

## 5. References and links

* [Git for Windows][1]
* [PowerShell 7.2 (LTS)][2]
* [TortoiseGit][3]
* [Creating Shortcut Menu Handlers][4]

## 6. Contacts

Please contact the author for any questions or if you'd like to help out.

[1]:https://gitforwindows.org/
[2]:https://learn.microsoft.com/en-us/powershell/scripting/whats-new/what-s-new-in-powershell-72?view=powershell-7.2
[3]:https://tortoisegit.org/download/
[4]:https://learn.microsoft.com/en-us/windows/win32/shell/context-menu-handlers
[5]:https://adamtheautomator.com/powershell-form/
