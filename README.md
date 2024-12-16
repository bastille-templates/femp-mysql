# FAMP (FreeBSD, Apache, MySQL, PHP/PHPMyAdmin)
## Now apply template to container
```sh
bastille create famp-mysql 14.1-RELEASE YourIP-Bastille
bastille bootstrap https://github.com/bastille-templates/famp-mysql
bastille template famp-mysql bastille-templates/famp-mysql
```

## License
This project is licensed under the BSD-3-Clause license.