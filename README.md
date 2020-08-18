# History of Git

As with many great things in life, Git began with a bit of creative destruction and fiery controversy.

The Linux kernel is an open source software project of fairly large scope. For most of the lifetime of the Linux kernel maintenance (1991–2002), changes to the software were passed around as patches and archived files. In 2002, the Linux kernel project began using a proprietary DVCS called BitKeeper.

In 2005, the relationship between the community that developed the Linux kernel and the commercial company that developed BitKeeper broke down, and the tool’s free-of-charge status was revoked. This prompted the Linux development community (and in particular Linus Torvalds, the creator of Linux) to develop their own tool based on some of the lessons they learned while using BitKeeper. Some of the goals of the new system were as follows:

- Speed

- Simple design

- Strong support for non-linear development (thousands of parallel branches)

- Fully distributed

- Able to handle large projects like the Linux kernel efficiently (speed and data size)

# What is Git?

Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed,efficiency and that facilitates GitHub activitieson your laptop or desktop.

# Installing Git

**Installing on Linux**

If you want to install the basic Git tools on Linux via a binary installer, you can generally do so through the package management tool that comes with your distribution. If you’re on Fedora (or any closely-related RPM-based distribution, such as RHEL or CentOS), you can use dnf:
```
sudo dnf install git
```
If you’re on a Debian-based distribution, such as Ubuntu, try apt:

```
sudo apt-get install git
```
<img src="https://www.cdn.geeksforgeeks.org/wp-content/uploads/har_4_1.png">

**Installing on macOS**

There are several ways to install Git on a Mac. The easiest is probably to install the Xcode Command Line Tools. On Mavericks (10.9) or above you can do this simply by trying to run git from the Terminal the very first time.

```
git --version
```
If you don’t have it installed already, it will prompt you to install it.

<img src="https://git-scm.com/book/en/v2/images/git-osx-installer.png">

**Installing on Windows**

There are also a few ways to install Git on Windows. The most official build is available for download on the Git website. Just go to                 **https://git-scm.com/download/win** and the download will start automatically.

<img src="https://phoenixnap.com/kb/wp-content/uploads/2019/12/download-git-for-windows.png">



