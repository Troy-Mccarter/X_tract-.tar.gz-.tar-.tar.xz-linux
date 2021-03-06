# Extracting tar.xz file in Linux
Extracting a tar xz file is fairly simple. You just need to make sure that you have support for xz compression utility on your Linux distribution.

xz compression tool is available through xz-utils package in most Linux distributions. Most of the time, you’ll already have the xz-utils installed by default.

But you should still ensure that it is installed on your system. You can use your Linux distribution’s package manager to install it.

On Debian or Ubuntu, you can install xz-utils with the following command:

sudo apt install xz-utils
Once you have the xz compression support on your Linux distribution, you can extract the tar.xz file using the standard tar command:

tar -xf <file>.tar.xz
In here:

-x means extract the archived file
-f means following is the archived file name
Why did you need to specify x (extract ) here? Because tar can also be used for creating (compressing) files.

So you need to specify which operation you are performing with tar command, compression (c) or extraction (x).

#source - https://linuxhandbook.com/extract-tar-xz/
