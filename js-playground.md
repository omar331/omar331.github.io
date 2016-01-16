About a year ago I started playing around *node js**. Since then I've developed few applications. But they were too simple.
Now I decided to go further and deeper and publish my experience, step by step.

The aim of this series of articles is get the foot wet and teach myself about the ``node js`` architecure. And also share my experience.

I'm calling this experiment **The javascript playgound**.


## Setting up the enviroment

First of all I decided to run my javascript playground inside a VirtualBox hosted Ubuntu 14.04 distro.
To achieve that I used the fabulous vagrant. Vagrant is a very good tool for building an isolated development environment
for each of your projects. You install it, quickly set up a new box, ssh to it and do whatever you want without the risks of polute your machine
with project specific setup. Every dependency go inside the box. And everything gets perfectly portable. Awesome!



### Installing Node js

Configure your environment using a Launchpad PPA script

```
curl -sL https://deb.nodesource.com/setup_4.x | sudo -E bash -
sudo apt-get install -y nodejs
```

You can find more instructions and platform specific details at [Node js website](https://nodejs.org/en/download/package-manager/).

When `node js` is installed the `npm` package is installed as well. As you gonna see it's very pretty important and useful.
  
  
