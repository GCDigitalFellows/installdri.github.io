# Git
Git is a distributed version control system used to manage changes to text files. 

# OS/X

On OS/X, git is part of the xcode command line tools. To install them:

1. Open a [terminal](osx_terminal).

2. Type the following in the terminal:
```bash
xcode-select --install
```
3. [Test install](#test-install)

# Windows
As part of installing git, install the gitbash command line environment so that the command line is consistent across Windows, OSX and Linux.

1. Download git for windows:
https://git-scm.com/download/win

2. *Click* on the git installer:

![git installation icon, looks like a tree branch inside 4 colored squares](../images/windows/git/git00.png)

3. Accept the license and *click* `Next`:

 ![license acceptance window](../images/windows/git/git01.png)

4. Select the installation folder, default is fine. *Click* `Next`:

![installation folder browser with text window showing folder path](../images/windows/git/git02.png)

5. Select the components to be installed, the default is fine: 

![list of check boxes showing install options: additional icons, on the desktop, Windows Explorer integration, Git Bash, Git GUI, Git LFS, Associate *.git configuration files with the default text editor, associate .sh files to be run with bash,  use a true type font in all console windows, check daily for git for windows, check daily for git console updates](../images/windows/git/git03.png)

- Windows Only: select start menu folder (default is fine):

![textbox with browse button listing start menu folder options](../images/windows/git/git04.png)

6. Choose the default editor used by Git. Select `Visual Studio Code` as the default editor. *Click* `Next`:

![installation menu containing drop down of editor options: nano, vim, notepad++, visual studio code, visual studio code insiders](../images/windows/git/git06.png)

7. Choose the "Use Git from the Windows Command Prompt" radio button and then *click* `Next`:

![three radio buttons: use git from git bash, use git from windows command prompt, use git and optional unix tools from the windows command prompt](../images/windows/git/git07.png) 

9. Choose the HTTPS transport backend (the default is fine). *Click* `Next`: 

![list of radio button optionsL 1) use the OpenSSL library, 2) use the native windows secure channel library](../images/windows/git/git08.png)

10. Configure the line ending conversions (the default is fine). *Click* `Next`:

![list of radio button options: 1) checkout Windows-style, commit unix-style , 2) checkout is as is, commit is unix style, 3)checkout as is, commit is as is](../images/windows/git/git09.png)

11. On the 'configuring the terminal emulator to use with Git Bash' window, choose the "Use Windows default console window" option:

![two radio buttons: 1) Use MinTTY, 2) use Windows default console window](../images/windows/git/git10.png)

12. Configure the extra options (the defaults are fine). *Click* `Next`:

![check boxes: 1) enable file system caching, 2) enable git credential manager, 3) enable symbolic links](../images/windows/git/git11.png)

13. VSCode should now be installing:
 
 ![image of progress bar](../images/windows/git/git12.png)

14. *Click* through the rest of the install, leaving the defaults, and then *click* `Finish` on the last window: 

![final installation window that says "completing the git setup wizard"](../images/windows/git/git13.png)

14. [Test install](#test-install)

## Test Install

Test that git is installed:

1. Open a [windows](windows_terminal.md) or [OS/X](osx_terminal.md) terminal. 

2. Type the following into the terminal:
```bash
 git
 ```

The terminal should print something like:

```bash
usage: git [--version] [--help] [-C <path>] [-c name=value]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]


```
