### Node.js {#Node-js}

Install from [https://nodejs.org/en/download/](https://nodejs.org/en/download/)

> Encounter 2503/2502 error on win10,
>
> msiexec /package node-v10.16.0-x64.msi

To install the most recent LTS version of Node 10.x on e.g. ubuntu 18.04 , you need to use the [package manager](https://nodejs.org/en/download/package-manager/#debian-and-ubuntu-based-linux-distributions) to get it from the Ubuntu \_binary distributions \_repository.

```
curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash - 
sudo apt-get install -y nodejs
```



