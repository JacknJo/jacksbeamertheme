# jacksbeamertheme

This is my first try to realize a 'as easy as possible' solution for a nice designed beamer theme in LaTeX.
This is an early release of my work and i'm not shure if i'll find time to maintain all of your wishes.
But don't be afraid to ask! I'm happy for all of your criticism.
Anyways i wish you a lot of fun and good luck for all your presentations created with this template!


# Requirements
This template needs some additional packages. It will definitly work if you installed the
texlive-full package by:

    sudo apt-get install texlive-full

The texlive-full download will take ~3GB of space and will bring many packages you won't need.
If you stick with your tex installation you may need to install some of the missing packages. 
They can be found at https://www.ctan.org/.

# HowTo
Using this template is really easy. 
Just clone the repository to your location by using:
    git clone https://github.com/JacknJo/jacksbeamertheme.git

change to the directory jacksbeamertheme by:
    cd jacksbeamertheme

compile the example by:
    sh makeall.sh

if you wanna clear your project use:
    sh clearall.sh


Notice: The example contains a source code section that is commented out at the moment.
		If you want to use the source code highlighting, you have to uncomment

		\usepackage{minted} and
		\input{var/mintedExample.tex}

in main.tex. Also you need to compile with the -shell-escape flag (which makeall.sh uses as default).

Best Wishes 
JacknJo