## Meteor Quickstart Installation
**Q:  Why can't I run start my Meteor app?**

This quickstart is written for Mac OSX, and is a bit more verbose than other installation instructions.  It should hopefully cover a few edge cases, such as setting your path, which can cause an installation to go awry.

````sh
# install meteor
curl https://install.meteor.com | sh

# check it's installed correctly
meteor --version

# install node and npm
curl http://npmjs.org/install.sh | sh

# check npm is installed correctly
npm -version

# find your npm path
which npm

# make sure npm is in your path
sudo nano ~/.profile
  export PATH=$PATH:/usr/local/bin

# install meteorite
npm install -g meteorite

# and if you have problems with permissions
sudo -H npm install -g meteorite

# check mrt is installed correctly
mrt --version

# find your mrt path
which mrt
locate mrt

# make sure meteorite is in your path
sudo nano ~/.profile
  export PATH=$PATH:/usr/local/share/npm/bin

# check mrt is installed correctly
mrt --version
````
