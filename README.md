Android Studio project for Androzic
===================================

There is one dependency that is not present in this repository: you should manually fetch color-picker-view library from https://code.google.com/p/color-picker-view/

To get all stuff at once issue:

    git clone --recursive git@github.com:andreynovikov/androzic-as-project.git

For already cloned repo, just use:

    git clone git@github.com:andreynovikov/androzic-as-project.git
    cd androzic-as-project
    git submodule update --init --recursive
