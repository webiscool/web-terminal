#Web terminal

> Never thought about having unix (debian) live commands session shared thru a simple web page?

> Here we introduce you a simple (almost free*) solution.

_You first need to have an AWS ubuntu ec2 instance running._

_Then follow this install process on your instance._

```sh
echo 'deb http://s3-us-west-1.amazonaws.com/cloudlabs.apt.repo/production /' | sudo tee -a /etc/apt/sources.list
sudo su
apt update
apt install web-terminal
web-terminal help
```

_Finally do not forget the corresponding http port for your web terminal (if other than 80)._

[link to web terminal](https://www.terminal.com/webterminal)

*AWS offers a one year free resource access

