# ansible-pdns: Ansible role for configuring PowerDNS

This role installs and configures PowerDNS authoritative and, optionally, the recursor.

* By default install and configure the PowerDNS authoritative server.
* Optionally can install and confgure the PowerDNS recursive server on the same server listening on TCP/UDP 53, and thusly the authoritative server will listen on another port (default TCP/UDP 5353).

## Requirements

This role should support most any *nix that PowerDNS supplies binaries for from https://repo.powerdns.com.

So far, it has been tested on:

* CentOS 7
* Debian jessie(8)

## Role variables


### OS specific vars files


### Supported Flags


## Dependencies

None

## Example Playbook


## License

BSD, 2-clause

## Author

Dave Heebner <dave@rockpenguin.com>

&copy; 2017, Rockpenguin Technology, LLC
