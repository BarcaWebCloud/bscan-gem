# bscan-gem

### Building package

<br>

Run the following command below to compile the gem:

`gem build bscan.gemspec`

If you want to install the gem locally run the following command:

`gem install ./bwc-bscan-0.1.0.gem`

<br>

### Publishing

In this step you will be able to publish your own gem. 

It is necessary to authenticate your account before uploading your gem.

Run the command below to login:

`gem signin`

<br>

> If you're having problems with curl, OpenSSL or certificates, try simply entering the above URL into your browser's address bar. Your browser will prompt you to log in to RubyGems.org. Enter your username and password. Your browser will now attempt to download the api_key.yaml file. Save it to ~/.gem and call it 'credentials'

<br>

Once this has been setup, you can push out the gem:

`gem push bwc-bscan-0.1.0.gem`