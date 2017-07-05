# Setup

Applications, bash aliases and other settings.

## Install (Ubuntu)

```
sudo apt-get update
sudo apt-get upgrade -y
sudo apt-get install git -y
sudo chown $(whoami) /opt
git clone git@github.com:ivandokov/setup.git ~/.setup
cd ~/.setup
./install
```

## Install (Mac)

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew install git
sudo chown $(whoami) /usr/local/include
sudo chown $(whoami) /usr/local/lib/pkgconfig
sudo chown $(whoami) /opt
git clone git@github.com:ivandokov/setup.git ~/.setup
cd ~/.setup
./install
```
