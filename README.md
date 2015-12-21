# rose-manifest

## Prepare

Download repo script:

    $ curl http://commondatastorage.googleapis.com/git-repo-downloads/repo > repo
    $ sudo mv repo /usr/local/bin/repo
    $ sudo chmod +x /usr/local/bin/repo

## Checkout

Create checkout directory:

    $ mkdir rose-project
    $ cd rose-project

To sync to the known stable and building version:

    $ repo init -u git@github.com:rose-project/rose-manifest.git -b master
    $ repo sync


To sync to bleeding edge of development:

    $ repo init -u git@github.com:rose-project/rose-manifest.git -b dev
    $ repo sync
