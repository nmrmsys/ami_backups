ami_backups - AWS EC2 AMI Backup Tool
====

## Usage
 ami_backups [--profile &lt;prof&gt;] [--all | &lt;inst&gt;] [--dry-run] [--reboot] [--oneshot [suffix]] [--no-wait]

Tag Setting Backup Mode

    > # Setting Backup Instance Tag 
    > # Backup:on, Generation:3, Reboot:off (optional) 
    > ami_backups --profile prof1 --all 

Single Instance Backup Mode

    > ami_backups --profile prof1 inst1 

First time running recommended to add --dry-run option.

## Requirement
- aws-cli version 1.6.x or later
- jq 

## Licence

[MIT](http://opensource.org/licenses/mit-license.php)

## Author

[nmrmsys](https://github.com/nmrmsys)
