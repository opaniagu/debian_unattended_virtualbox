# packer-virtualbox-debian
Crear imagen de  Debian (unattended) para utilizar en VirtualBox


## Introduccion

Este proyecto permite crear una imagen de Debian (actualmente la version 11.2), de manera **unattended** utilizando el archivo de 
**preseed.cfg**, para utilizar en VirtualBox.

Para ello, se utiliza la herramienta [Packer](https://www.packer.io/).


## Generando la imagen

### Requirementos

- [Packer](https://www.packer.io/)
- [VirtualBox](https://www.virtualbox.org/)

### Utilizando `packer`

Para generar la imagen de Debian

```
$ packer build debian-11.2-amd64.json
```

La imagen se guarda en el direcion build/

El usuario de linux es **info** y la contraseña **info** 


## Bugs and Issues

Por favor, utilice GitHub issues para reportar bugs, nuevas funcionalidades u otros problemas.

## Proyecto de referencia

Se utilizo como referencia el proyecto [bento org](https://app.vagrantup.com/bento).

