# FOR MAC

## Installation steps

Installing Node via Homebrew

The quickest way to get Homebrew is to visit http://brew.sh and get hold of the installation script. It should look a little something like this:

```
/usr/bin/ruby -e "$(curl -fsSL 
```
https://raw.githubusercontent.com/Homebrew/install/master/install)"
Simply paste that into your Terminal and it'll download the Homebrew package manager to your Mac. We can then use brew install node to install Node on our system without any worries.

Once you've done that, check your Node installation works by typing node -v and npm -v. If you get two version numbers back (that is, one for each), then you’re ready to go ahead with the rest of the book!

In order to manage the different Node versions, we could also install the Node Version Manager (NVM). Do note however that this is currently only supported by Mac at present and not Windows. To install NVM, we can use Homebrew like so:

```

--use Brew to install the NVM
brew install nvm

--File directory
mkdir ~/.nvm

--Install latest version
nvm install --lts

--Ensure latest version is used
nvm use node

--Remember details across sessions
nano ~/.bash_profile

--Execute in every session
export NVM_DIR="$HOME/.nvm"
  . "$(brew --prefix nvm)/nvm.sh"

  ```
