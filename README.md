# mac-setup-script
Attempt at a single script to setup a new Mac nicely. 

Things TODO:

general:
can we run automatic checksum of each download to verify integrity? Is that overkill? Probably

script:
iCloud documents/screen shots created and set as screen shot save directory
install zsh
make zsh default shell
resart shell - can this be done, and does it have to be done in order to install zsh? IF we have to restart the shell, how can we continue this script? Output to a file, create a service that runs upon startup, and then restart the whole system, triggering the startup service that calls the output file which contains the rest of this script? 
Homebrew installed
brew wget installed
brew oh my zsh installed
brew ffmpeg installed
brew handbrake cli installed (can we install gui version from command line also?)
brew libdvdcss installed
cDocs alias generated in ~/.zshrc (cDocs = "cd cloud documents dir")
generate keys for github and login
github clone and install youtube-dl
install xcode command line tools


how to run the script:
is it possible to devise an easy to remember and succint memorizable command that could do all of this, with minimal dependencies? 
Yes - use curl, like hombrew: /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

but can we do this using zsh instead? 
