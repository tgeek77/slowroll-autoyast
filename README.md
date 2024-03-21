# slowroll-autoyast

This AutoYaST file will install openSUSE Slowroll when used in addition with a openSUSE Tumblweed install. It will automate the installation process except for a couple of minor questions and at the end will leave you with a system that is running openSUSE Slowroll. This will be a terminal-only VM. When I have time, I will create a version for Gnome, KDE, and Mate. They will all have the same default username and password.

I suggest using the versions found in the stable directory for testing. These are the latest working versions of the files that I have created.

- Default Username used in this file: tux
- Default Password: linux

*Update*:

I have created an autoyast file for installing Slowroll to a system with a GUI with MATE installed. I chose MATE because it is simpler than Gnome or KDE with less dependencies. It almost works!

After installing Slowroll with this file, everything is installed except the display-manager service does not start automatically but it does start manually with `sudo systemctl start display-manager`.

This means that currently you will get just an terminal after installation and the GUI can be started by starting the service.







Help:
- What is [Slowroll](https://en.opensuse.org/openSUSE:Slowroll)?
- What is [AutoYaST](https://doc.opensuse.org/documentation/leap/autoyast/single-html/book-autoyast/index.html)?
- What is [openSUSE Tumbleweed](https://en.opensuse.org/Portal:Tumbleweed)?
