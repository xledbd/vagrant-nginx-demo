vagrant-nginx-demo
===

Creates a Vagrant VM, installs nginx and serves static pages from web directory

## Prerequisites

* Vagrant
* Virtualbox

## Usage

1. Clone the repository
2. `cd` into the repository
3. `vagrant up`

The server can be reached at `localhost:8080` (only from host machine)

The changes inside the `web` directory are automatically synced with the guest VM
