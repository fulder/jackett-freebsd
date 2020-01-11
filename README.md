# Usage

## Pre-requirements

* `pkg install -y bash ca_root_nss jq jackett`
* `mv /usr/local/etc/rc.d/jackett /usr/local/etc/rc.d/jackett_old`

## Installation

* Place the `jackett` file inside `/usr/local/etc/rc.d/jackett`
* `sysrc "jackett_enable=YES"`
* `chmod +x /usr/local/etc/rc.d/jackett`

# References

Inspiration taken from https://digimoot.wordpress.com/2019/10/13/freenas-jackett-manual-install/