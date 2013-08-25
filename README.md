Phitext
=======

Phitext is the first rich text editor library for iOS developers - http://phiware.com.au/apps/phitext.

Getting Started
---------------

Clone, update submodules and open Xcode.

    git clone git@github.com:au-phiware/Phitext-workspace.git
    cd Phitext-workspace
    git submodule update --init
    open -a Xcode Phitext.xcworkspace

To get a feel of what the library is capable of run the PhitextSampler app in the iPad Simulator.

### Seeing Red?

If the projects in Xcode's Project Navigator are red, this means that the submodules failed to download (see above). Try downloading manually: [Phitext](https://github.com/au-phiware/Phitext), [PhitextSampler](https://github.com/au-phiware/PhitextSampler), [PhitextDeveloper](https://github.com/au-phiware/PhitextDeveloper).

Contributing
------------

Contributions to the submodules of this project are welcome (see the GitHub project pages, resp.) but please do not submit pull requests to this project.

Having said that submodules aren't as nasty as you might have heard; just try this from your working directory:

    cd Phitext
    git checkout master
    git remote set-url origin git@github.com:your-fork/Phitext.git

Substituting *your-fork* with your GitHub username in the URL. 

License
-------

[Apache](NOTICE)
