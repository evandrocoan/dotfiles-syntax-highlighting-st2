# Dotfiles Syntax Highlighting for Sublime Text 2/3

Want ShellScript (Bash) syntax highlighting for your dotfiles? You're damn right you do!


## Installation

### By Package Control

1. Download & Install **`Sublime Text 3`** (https://www.sublimetext.com/3)
1. Go to the menu **`Tools -> Install Package Control`**, then,
   wait few seconds until the installation finishes up
1. Now,
   Go to the menu **`Preferences -> Package Control`**
1. Type **`Add Channel`** on the opened quick panel and press <kbd>Enter</kbd>
1. Then,
   input the following address and press <kbd>Enter</kbd>
   ```
   https://raw.githubusercontent.com/evandrocoan/StudioChannel/master/channel.json
   ```
1. Go to the menu **`Tools -> Command Palette...
   (Ctrl+Shift+P)`**
1. Type **`Preferences:
   Package Control Settings – User`** on the opened quick panel and press <kbd>Enter</kbd>
1. Then,
   find the following setting on your **`Package Control.sublime-settings`** file:
   ```js
       "channels":
       [
           "https://packagecontrol.io/channel_v3.json",
           "https://raw.githubusercontent.com/evandrocoan/StudioChannel/master/channel.json",
       ],
   ```
1. And,
   change it to the following, i.e.,
   put the **`https://raw.githubusercontent...`** line as first:
   ```js
       "channels":
       [
           "https://raw.githubusercontent.com/evandrocoan/StudioChannel/master/channel.json",
           "https://packagecontrol.io/channel_v3.json",
       ],
   ```
   * The **`https://raw.githubusercontent...`** line must to be added before the **`https://packagecontrol.io...`** one, otherwise,
     you will not install this forked version of the package,
     but the original available on the Package Control default channel **`https://packagecontrol.io...`**
1. Now,
   go to the menu **`Preferences -> Package Control`**
1. Type **`Install Package`** on the opened quick panel and press <kbd>Enter</kbd>
1. Then,
search for **`Dotfiles`** and press <kbd>Enter</kbd>

See also:

1. [ITE - Integrated Toolset Environment](https://github.com/evandrocoan/ITE)
1. [Package control docs](https://packagecontrol.io/docs/usage) for details.


## File Types Supported

- `.ackrc`
- `.aliases`
- `.antigen`
- `.bash_aliases`
- `.bash_profile`
- `.bash_prompt`
- `.bashrc`
- `.brew`
- `.curlrc`
- `.env`
- `.env.development`
- `.env.test`
- `.env.production`
- `.env.local`
- `.env.development.local`
- `.env.test.local`
- `.env.production.local`
- `.env.example`
-	`.env.testing`
-	`.env.dusk.testing`
-	`.env.dusk.local`
- `.envrc`
- `.eslintignore`
- `.exports`
- `.extra`
- `.functions`
- `.git`
- `.gitattributes`
- `.gitconfig`
- `.gitignore`
- `.gitignore_global`
- `.hushlogin`
- `.inputrc`
- `.jsbeautifyrc`
- `.jshintignore`
- `.lftprc`
- `.npmignore`
- `.npmrc`
- `.osx`
- `.packages`
- `.pkginit`
- `.screenrc`
- `.symlink`
- `.zlogin`
- `.zlogout`
- `.zprofile`
- `.zshenv`
- `.zshrc`
- `.zsh-theme`
- `.zpreztorc`
- `.xsessionrc`
- `.wgetrc`
- `symlink`
- `symlink`
- `zshrc`
- `zshenv`
- `zlogin`
- `zlogout`
- `zprofile`
- `zpreztorc`

If you want other file types add them in or submit a pull request.

### Credits

- Matt Banks ([@mattbanks](http://twitter.com/mattbanks))

#### Contributors

- [mathiasbynens](https://github.com/mathiasbynens)
- [lotsofcode](https://github.com/lotsofcode)
- [vivek](https://github.com/vivek)
- [darinmorrison](https://github.com/darinmorrison)
- [alrra](https://github.com/alrra)
- [theskumar](https://github.com/theskumar)
- [kikobeats](https://github.com/kikobeats)
- [fainder](https://github.com/fainder)
- [Jeloi](https://github.com/Jeloi)
- [gwarnants](https://github.com/gwarnants)
- [michelegera](https://github.com/michelegera)
- [gwarnants](https://github.com/gwarnants)
- [xtream1101](https://github.com/xtream1101)
- [thecodechef](https://github.com/thecodechef)
- [diegorv](https://github.com/diegorv)
