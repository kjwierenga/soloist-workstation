
Automated workstation setup using soloist and librarian-chef.
---

This chef cookbook repo is used to setup a new workstation with all the necessary bits
for software development (ruby, rails, etc).

It uses soloist and pivotal_workstation to setup an development environment on a Mac OSX workstation.

Usage
---

Get the repo

    git clone https://github.com/kjwierenga/workstation.git

Install the gem bundle

    cd workstation
    gem install bundler # if you don't have it already
    bundle

Create soloistrc configuration file in $HOME

    ln -s workstation/soloistrc $HOME/solistrc
    soloist

References
---

Soloist: https://github.com/mkocher/soloist
Pivotal Workstation: https://github.com/pivotal/pivotal_workstation

