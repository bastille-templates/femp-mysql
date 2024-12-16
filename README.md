# FEMP (FreeBSD, Apache, MySQL, PHP/PHPMyAdmin)
## Now apply template to container
```sh
bastille create femp-mysql 14.1-RELEASE YourIP-Bastille
bastille bootstrap https://github.com/bastille-templates/femp-mysql
bastille template femp-mysql bastille-templates/femp-mysql
```

## License
This project is licensed under the BSD-3-Clause license.