# Censys recon-ng Modules

We have written several modules for [recon-ng](https://bitbucket.org/LaNMaSteR53/recon-ng) adding data via the Censys API. These were inspired by the work that @scumsec did on the original recon-ng additions from their add-on modules, and also from the subdomain enumeration techniques that use Censys data like from @christophetd. 

Where possible we attempt to minimize API hits. 

## Installation

We have provided two pieces you need to install these modules and begin using them.

* `requirements.txt` - Use this via `pip install -r requirements.txt` to install Python dependencies.
* `install.sh`- Run this script and it will both install the modules in your home directory (recon-ng supports modules added for the local user in ~/.recon-ng) and configures the database to add support for your Censys API ID and secret. See your Censys account for your credentials, and add them to the database as you would any other credential - `keys add ...`. 

One you have completed these you can fire up `recon-ng`.