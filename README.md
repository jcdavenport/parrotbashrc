# parrotbashrc
.bashrc file for a parrot style command line


USAGE: \
*bash should already be installed on local machine.

#backup original .bashrc \
cd && cp .bashrc .bashrc_ORIG

#clone into home directory using git, and rename parrot.bashrc to .bashrc(i.e. ~/.bashrc) \
git clone https://github.com/jcdavenport/parrotbashrc.git \
cp parrotbashrc/parrot.bashrc .bashrc


then just restart bash by "source ./.bashrc" (or equivalent), or close and re-open the terminal.
