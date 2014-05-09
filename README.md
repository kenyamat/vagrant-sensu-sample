# vagrant-sensu-sample

## Installation

You need to install some plugins or gems as follows

```
gem install berkshelf
vagrant plugin install vagrant-omnibus
```

## How to run virtual machines 

First, you need to run berkshelf as follows.

```
berks vendor cookbooks
```

Then, you can run vagrant as follows.

```
vagrant up --provision
```

After that, 4 virtual machines will be booted.

You can access 

* Sensu-dashboard at http://192.168.33.10:8080
* Graphite at http://192.168.33.101
