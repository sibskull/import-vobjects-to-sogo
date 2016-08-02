# import-contacts-to-sogo

Script for mass import contacts in vCard format to SOGo folders

(с) 2016 Andrey Cherepanov <cas@altlinux.org>

License: GPLv3

Script uses Python3 [module vobject](https://github.com/eventable/vobject), 
recommended version 1.9.2 built with upstream commit fe78218: 
"vcard: Fix ORG fields with multiple components"

### Usage example

    ./import-contacts-to-sogo -v \
        --db "postgresql://sogo@/sogo2" \
        --location "postgresql://sogo:1234@localhost:5432/sogo2" \
        user_dod
