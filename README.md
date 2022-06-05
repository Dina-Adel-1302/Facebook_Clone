![alt license](https://img.shields.io/badge/license-GPL%20V3.0-green "GNU GPL")
![alt language](https://img.shields.io/badge/language-Ruby%20On%20Rails-blue "Ruby On Rails")

README
======

Facebook_Clone
---------------

### Description

Ruby On Rails - simple program to make primitive operations on the tables users and posts: 

*   Create. 
*   Update.
*   Destroy.
*   Show.

### Installation guide
#### Install Ruby 
*   [Ubuntu](https://www.ruby-lang.org/en/documentation/installation/#package-management-systems "Ruby on Ubuntu"). 
*   [Windows](https://www.ruby-lang.org/en/documentation/installation/#rubyinstaller).    
*   [Mac](https://stackify.com/install-ruby-on-your-mac-everything-you-need-to-get-going/). 

#### Install Ruby On Rails 
*   [Ubuntu](https://www.howtoforge.com/tutorial/ubuntu-ruby-on-rails/). 
*   [Windows](https://gorails.com/setup/windows/10).    
*   [Mac](https://gorails.com/setup/osx/11-big-sur). 

#### Install sqlite 
*   [Ubuntu](https://linuxhint.com/install-sqlite-ubuntu-linux-mint/). 
*   [Windows](https://www.sqlitetutorial.net/download-install-sqlite/).    
*   On macOS, you don’t need to do anything to install sqlite. It’s preinstalled in all modern versions of macOS
All you need to do is to open a terminal and run the `sqlite3`

#### Install visual studio code 
*   [Ubuntu](https://linuxize.com/post/how-to-install-visual-studio-code-on-ubuntu-20-04/). 
*   [Windows](https://code.visualstudio.com/docs/?dv=win).    
*   [Mac](https://code.visualstudio.com/docs/?dv=osx). 

#### Install Node js and NPM
*   [Ubuntu](https://linuxize.com/post/how-to-install-node-js-on-ubuntu-18.04/). 
*   [Windows](https://phoenixnap.com/kb/install-node-js-npm-on-windows).    
*   [Mac](https://www.newline.co/@Adele/how-to-install-nodejs-and-npm-on-macos--22782681). 

#### Let's get started 

``` bash

$ rails new Facebook_Clone #rails creates a lot of files and folders for you automatically (Controllers - Models - Views - Tests)

$ cd Facebook_Clone  #cd: Change working Directory - move to the project directory.

$ rails s  #s: for server - This will get the server up and running on http://127.0.0.1:3000 

$ rails g scaffold user name email age gender #g: for generate - This command generates crud operations (create - update - destroy - show) for the table user.

$ rails g scaffold post user_id title description #g: for generate - This command generates crud operations (create - update - destroy - show) for the table post.

```

#### [Screen Shots](https://github.com/Dina-Adel-1302/Facebook_Clone/blob/main/screen_shots.pdf)


