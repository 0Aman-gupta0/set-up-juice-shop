# set-up-juice-shop
Prosses to set a Dame Vgurnable Most  Integrated Application

 The first thing first is to select a correct plateform or the host 
 Here I am using a fresh Debian Always go with the Genome
 
After successfull installation 

follow the git repository

https://github.com/juice-shop/juice-shop?tab=readme-ov-file#nodejs-version-compatibility    <<<cheeak compatibility

juice shop work on nodejs 
Install node.js 
select nodejs-version-compatibility ( Always use stable version )

 Now on your host decide a location where to deploy the application Here i deploed on /opt on my Debian
 
https://github.com/nodesource/distributions/blob/master/README.md
Follwo up the above repo

we need Wget or Curl command for the above Packages

then after this go to your /opt folder

Run git clone https://github.com/juice-shop/juice-shop.git --depth 1 (or clone your own fork of the repository)

Go into the cloned folder with cd juice-shop

Run npm install (only has to be done before first start or when you change the source code)

sudo npm start

Browse to http://localhost:3000
Done


 
