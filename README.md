# slowroll-autoyast

This AutoYaST file will install openSUSE Slowroll when used in addition with a openSUSE Tumblweed install. It will automate the installation process except for a couple of minor questions and at the end will leave you with a system that is running openSUSE Slowroll. This will be a terminal-only VM. When I have time, I will create a version for Gnome, KDE, and Mate. They will all have the same default username and password.

I suggest using the versions found in the stable directory for testing. These are the latest working versions of the files that I have created.

- Default Username used in this file: tux
- Default Password: linux

*Update*:

New AutoYaST files are available to install KDE, Mate, Budgie, and Sway in the "stable" directory. They have been testing in KVM VMs and not on physical servers since my homelab is poor and VMs are the best I can do at this time.
Each AutoYaST file will install Slowroll by default. You will not need to add more repositories later.

When Slowroll becomes an official project, the URL for the repositories will be updated.

Help:
- What is [Slowroll](https://en.opensuse.org/openSUSE:Slowroll)?
- What is [AutoYaST](https://doc.opensuse.org/documentation/leap/autoyast/single-html/book-autoyast/index.html)?
- What is [openSUSE Tumbleweed](https://en.opensuse.org/Portal:Tumbleweed)?
