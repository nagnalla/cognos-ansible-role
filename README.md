# Cognos playbook

## Scope

This is an opinionated and automated way to install IBM InformationServer which includes Cognos.

## Usage

1. `git clone` this repo and `cd` into it.

1. Create a `hosts` file at the top level, give it an IP address or FQDN.

   ```ini
   [hosts]
<IP>
   ```

1. Run the playbook

   ```bash
   ansible-playbook -i hosts -u root -k playbook/main.yaml
   ```

## Tested on

This has been tested and works on:

* RHEL 7.x



*add dummy2
