## Seedbox install script for Debian 8 (Jessie) 64-bit - clean install

![Travis CI](https://travis-ci.org/bbashy/seedbox.svg?branch=master)

#### Not yet ready for use

## Install
Make sure you have sudo installed already. `sudo -V` if not, install: `apt-get install sudo` as root.
First download the script to your machine. The Droplr link will always go to the master branch (install file).
You're welcome to check the redirect yourself. It's a simple URL shortener.
```
# curl
└> curl -L https://d.pr/1kfR4 > install_seedbox

# wget
└> wget -O install_seedbox https://d.pr/1kfR4
```
Then to install (check the contents before using sudo on a downloaded script).
```
chmod +x install_seedbox
sudo ./install_seedbox
```

### Notice
I've got a good understanding of bash/shell scripting and I'm testing this script heavily so it will be pretty stable once ready. If you see something wrong or a part that could be improved, please let me know in the issues or open a pull request fixing it (please explain the problem and how it improves it).

### Important
Although this is tested and doesn't do anything dangerous - I do not take responsibility if this script causes any system errors, loss of data or problems with your server or machine.
