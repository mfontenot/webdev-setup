# Brew Install

* `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

* said it was creating folders - may need to chown these?
```
/usr/local/bin/brew
/usr/local/share/doc/homebrew
/usr/local/share/man/man1/brew.1
/usr/local/share/zsh/site-functions/_brew
/usr/local/etc/bash_completion.d/brew
/usr/local/Homebrew
```

* `brew update`

* install nvm/node
  * `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash`
  * close and restart terminal to use next command
  * `nvm install stable`
  
* now npm install node-sass - should work
  * change into webdev folder
  * `npm i node-sass`
