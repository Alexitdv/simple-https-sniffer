## Simple Https Sniffer (CLI version)
It's a simple https sniffer (cli version) that I have made for [this task](task.md).

### Getting started
__eth0__ - Example of device name from __sniffer list__ command.

```bash
$ docker build -t sniffer
$ docker run -it --net="host" --privileged sniffer /bin/bash
# sniffer list 
# sniffer run eth0
```