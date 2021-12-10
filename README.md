## tabbed - generic tabbed interface
pinosaur's patched version of **tabbed**, a simple tabbed X window container.

the following patches are applied:
- [xresources](https://tools.suckless.org/tabbed/patches/xresources/)

### Requirements
In order to build tabbed you need the Xlib header files.

### Installation
Edit config.mk to match your local setup (tabbed is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install tabbed
(if necessary as root):
```
make clean install
```
