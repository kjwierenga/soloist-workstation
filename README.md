
Automated workstation setup using soloist and librarian-chef.
---

This chef cookbook repo is used to setup a new workstation with all the necessary bits
for software development (ruby, rails, etc).

It uses soloist and pivotal_workstation to setup an development environment on a Mac OSX workstation.

Usage
---

Get the repo

    cd $HOME
    git clone https://github.com/kjwierenga/workstation.git

Install the gem bundle

    cd $HOME/workstation
    gem install bundler # if you don't have it already
    bundle

Create soloistrc configuration file in $HOME. This is where you list the recipes to run to install and configure software.

    ln -s $HOME/workstation/soloistrc $HOME/solistrc

Run soloist to apply the recipes specified in $HOME/soloistrc.

    soloist

References
---

Soloist: https://github.com/mkocher/soloist
Pivotal Workstation: https://github.com/pivotal/pivotal_workstation

