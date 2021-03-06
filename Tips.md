# Tips, Shortcuts, And Aliases 😎

## Intro

**Being able to fly in your terminal is an awesome skill. Using a combo of typing speed, terminal commands, aliases, Vim (_if you dare_), and practice, anyone can be terminal pro; a command-line wizard**

In order to maximize developer tools and helpers, it's essential to have a solid foundation with typing. To improve your skills, the following are some good resources:

>http://www.keybr.com/
> - employs statistics and smart algorithms to automatically generate typing lessons matching your skills;
>- generates random, but readable and pronounceable words using the phonetic rules

>https://www.typingclub.com/
> - Great to develop proper finger placement on keyboard

>http://play.typeracer.com/
> - Just for fun; surprisingly addictive competition-based game.

## Useful Productivity Tools
### Window Resizing:
Free:
Spectacle: https://www.spectacleapp.com/


Paid:
Magnet: https://itunes.apple.com/us/app/magnet/id441258766?mt=12

### Notetaking:
Free:
Evernote: https://evernote.com/

Paid:
⭐️⭐️⭐️⭐️⭐️Quiver: http://happenapps.com/

### Alfred: https://www.alfredapp.com/
- Search/Browse/Set Hotkeys
-Snippets and supports Clipboard History
-Calculate
-Spell/Define

## Keyboard/Shortcut Commands
 `command + spacebar`  **open Spotlight**

`option + spacebar` **open Alfred**

`command + tab` **switch between open apps**

`command + shift + 4` **selective screenshot**

`command + control + shift + 4` **selective screenshot copied to clipboard**

`command + backspace` **delete to beginning of line**

`command + →` **move cursor to end of line**

`command + ←` **move cursor to beginning of line**

`option + →` **jumps cursor to the next word**

`option + ←` **jumps cursor to the previous word**

<code>command + &#96;</code> **toggle between app windows**

##Atom Keyboard Commands
`control + command + ↑ or ↓` **move line up or down**  



## Terminal Commands
>**Tab**
- _Allows for Autocomplete Paths_
- _Press Twice if does not autocomplete to show potential options_
>**top**
- _View All Active Processes_
>**caffeinate**
- _Prevents your machine from going to sleep_
- _Quit this process using Control+C_
>**command + k**
- _Clears terminal window_
>**ctrl + a**
- _moves cursor to beginning of line_
>**ctrl + e**
- _moves cursor to end of line_
>**ctrl + u**
- _Clears the line_
>**ditto**
ditto path/to/source path/to/destination
- _Copy files and folders_
- _Adding -V Prints line for every item being moved_
>**history**
- _shows all commands entered into command line_
- _use with **grep** to find specific commands_
- **history -c** to clear history
>**pbcopy < [file_name]**
- _Place the contents of a file in the clipboard_


## Aliases (with Bash)

⁉️ **What is Bash? What is a shell?**

**Alias Set-Up:**
- navigate to home directory
- Check for .bashrc file
- If not:   
  - create .bashrc file by running:
    `vi ~/.bashrc
    echo PATH=$PATH:~/bin > .bashrc`
- Open File
- At end of file, add the alias
>**alias aliasname='commands'**

**Some useful aliases Part One:**

`alias gst='git status'`

`alias gc='git commit -m'`

`alias ga='git add'`

`alias gaa='git add -A'`

`alias gcb='git checkout -b'`

`alias gco='git checkout'`

`alias gp='git push'`

`alias gpo='git push origin master'`

`alias gb='git branch'`

`alias gba='git branch -a'`

`alias grv='git branch -v'`

`alias modb='atom ~/.bashrc'`

`alias ..='cd ..'`

`alias ...='cd ../../'`

`alias hs='history | grep'` include some text to search

## Plugins and Tools
### Terminal Alternative
**Let's download iTerm2!!!**

### Github plugins

`Emmmet` https://atom.io/packages/emmet
- Expand abbreviations by Tab key

`file-icons` https://atom.io/packages/file-icons

`indent-guide-improved` https://atom.io/packages/indent-guide-improved

`open-in-browser` https://atom.io/packages/open-in-browser

`markdown-preview-plus` https://atom.io/packages/markdown-preview-plus



###Shell Alternative
>***Oh-My-Zsh***

**Oh My Zsh will not make you a 10x developer...but you might feel like one.**
- Uses zsh as alternative shell
- Robust plugins (over 200!)
- Syntax Highlighting
- Colors and Themes!

-Steps
  - Install Zsh
    - `brew install zsh zsh-completions`
  - Verify Install
    -  `zsh --version`
  - Set as Default:
    - `chsh -s $(which zsh)`
  - Verify Default:
    - `echo $SHELL`
  - **Install Oh My Zsh:**
    - Via curl `sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`


## Extras

**run**
`telnet towel.blinkenlights.nl`


**run**

`ruby -e 'C=`stty size`.scan(/\d+/)[1].to_i;S=["2743".to_i(16)].pack("U*");a={};puts "\033[2J";loop{a[rand(C)]=0;a.each{|x,o|;a[x]+=1;print "\033[#{o};#{x}H \033[#{a[x]};#{x}H#{S} \033[0;0H"};$stdout.flush;sleep 0.1}'`
