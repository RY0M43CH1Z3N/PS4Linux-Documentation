<p align="center"><img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fimage.flaticon.com%2Ficons%2Fpng%2F512%2F518%2F518713.png&f=1&nofb=1"...></p>
<h1 align="center">
Documentación de Linux en PS4
</h1>
<h2 align="center">
Documentación completa de Linux en PS4
</h2>

------

# Necesario.

## Archivos.

### Kernel.

| PS4       | Kernel     |
|--------------|-----------|
| Aeolia | [**4.14.93** (El más estable - Permite grabarse en el disco duro interno - Creado por Psxita)](https://mega.nz/file/EJhBzTIQ#rpbOcpIpulojUxRUiZjLQ7RqS6tlNc6JmcCrgSxyG-g) [**5.3.18** (BETA - Soporte de Vulkan - Permite grabarse en el disco duro interno - Creado por Mircoho)](https://github.com/ps4boot/ps4-linux/releases/download/v1/bzImageAeolia) [**5.15.12** (ALFA - NO ES ESTABLE - Soporte de Vulkan- NO permite grabarse en el disco duro interno - Creado por codedwrench)](https://mega.nz/file/0wgETIxI#2nzITm4YokEQXAmm5_lHcPXKotlr3Tj1qbHutKS9BqA)|
| Belize | [**4.14.93** (El más estable - Permite grabarse en el disco duro interno - Creado por tihmstar)](https://github.com/Nazky/ps4-linux/releases/download/4.19.93-belize/bzImage) [**5.3.18** (BETA - Soporte de Vulkan - Permite grabarse en el disco duro interno - Creado por Mircoho)](https://github.com/ps4boot/ps4-linux/releases/download/v1/bzImage) [**5.15.12** (ALFA - NO ES ESTABLE - Soporte de Vulkan - NO permite grabarse en el disco duro interno - Creado por codedwrench))](https://mega.nz/file/0wgETIxI#2nzITm4YokEQXAmm5_lHcPXKotlr3Tj1qbHutKS9BqA) |
| Baikal | [**4.14.93** (El más estable - NO permite grabarse en el disco duro interno - Creado por Psxita)](https://mega.nz/file/4FhBjbaS#zgy2TFTPN1fdWLyLZaJJBfIv2cZQOExdXvfYRVqIHNU) [**5.3.18** (BETA - Soporte de Vulkan - NO permite grabarse en el disco duro interno - Creado por Mircoho)](https://github.com/ps4boot/ps4-linux/releases/download/v1/bzImageBaikal) [**5.15.12** (ALPHA - NO ES ESTABLE - Soporte de Vulkan - NO permite grabarse en el disco duro interno - Creado por codedwrench)](https://mega.nz/file/Z1BywBxC#5HDoTE82zcaYdaCxlbuoNNzM4WJhdANriM0I4HEtmgs)  |

Aeolia, Belize y Baikal son modelos de PS4, para saber cuál es la tuya mira [aquí](https://www.psdevwiki.com/ps4/Southbridge#Southbridge_revisions) (gracias a [@Plattntektonik](https://twitter.com/Plattntektonik))

### Initramfs.cpio.gz.

| Autor        | Enlace    |
|--------------|-----------|
| [Psxita](https://www.psxita.it)  | [**MEGA**](https://mega.nz/file/IUBDiQKY#7WK2zFkUQbqJ02b9LTSAGug3NiL_8XPhprLcqVcfXxQ)
| [Hippie68](https://github.com/hippie68) | [**GitHub** ](https://github.com/hippie68/psxitarch-how-to/releases/tag/v1.00)
| [Nazky](https://twitter.com/NazkyYT) | [**MEGA**](https://mega.nz/file/E0wW3a6Y#IE9fvrjZ22Q2mJ6kM1uQaNctwj1-we4cV7xGqPBVV64) |

## Distribuciones de Linux.

### Creadas por otros (no están todas, sobre todo en el canal de ITMania tenéis MUCHÍSIMAS):

| Autor        | SO        |
|--------------|-----------|
| [Psxita](https://www.psxita.it) | [**Psxitarch**](https://www.psxita.it/distro/psxitarch.tar.xz)|
| [Mircoho](https://github.com/ps4gentoo)| [**Gentoo**](https://drive.google.com/uc?id=1o5zYErfHAeZnOR1beeN4syeuKW77VDjA&export=download) |
| [ItMania](https://www.youtube.com/channel/UCkVRqtCIS3Xj-E1HY4j9_EA)  | [**Fedora 32 edición Tron**](https://drive.google.com/file/d/1bwTtP8mzlAp_mDbS1EnaMfpWrZ7gC4HV/view)
| [Modded Warfare](https://www.youtube.com/channel/UCm9COMxXKm05BQWNv-IpyPg) | [**Fedora 32** ](https://anonfiles.com/Tdi5B458x6/PS4_Fedora32_MW_Itm.tar_xz)
| [Nazky](https://twitter.com/NazkyYT) | [**CuteFish OS**](https://mega.nz/file/lhhFCAzK#IMCOCXHihX49zjOr6_tWVXeRZehI89o4HNTUASKLsJE) |

### ¿Cómo actualizo Psxitarch?

Tienes un tutorial completo [aquí](https://github.com/hippie68/psxitarch-how-to).

### ¿Cómo actualizo Fedora?

Tienes un tutorial completo [aquí](https://youtu.be/WgukYE-2vx4?t=1029).

### ¿Cómo actualizo CuteFish OS?

##### Usando la terminal

```sudo pacman -Syyu```

Y actualizado :D (puede que tengas que reiniciar tu PS4).

##### Usando Pamac

- Abre la aplicación de la tienda (Añadir/quitar software).
- Ve a "Actualizar".
- Pulsa en "Aplicar".
- Espera...
- Y actualizado :D (puede que tengas que reiniciar tu PS4).

## ¿Cómo me creo mi propio Sistema operativo?

Lo que necesitas:

- Un SO (sistema operativo) compatible.
- Una máquina virtual (virtual box, VMware, qemu, ...) o un PC/Portátil dedicado.
- Los drivers de PS4 [aquí](https://github.com/Hakkuraifu/PS4Linux-ArchDrivers).
- Cerebro :p.

#### 1) El SO.

Necesitas un SO compatible, teóricamente todas las distribuciones de Linux pueden usarse en una PS4 si tienes o creas los drivers, ya que solo tenemos los drivers de arch, tendrás que usar una distribución basada en arch para ahorrarte esta parte. Te recomiendo Manjaro pero puedes intentarlo con otros.

#### 2) Instalando los drivers de PS4 usando drivers precompilados.

Tras instalar el SO en una mv (máquina virtual) o en un PC/Portátil, tendrás que añadir el repositorio de PS4Xploit.

```sudo echo -e "\n[ps4xploit-repo-arch]\nSigLevel = Optional TrustAll\nServer = https://PS4Xploit.zd.lu/Linux/Repo/x86_64" >> /etc/pacman.conf```

Tras esto, actualiza los repositorios.

```sudo pacman -Syyu```

E instala los drivers.

```sudo pacman -Syy mesa-ps4 lib32-libdrm-ps4 lib32-mesa-ps4 libdrm-ps4 xf86-video-amdgpu-ps4```

(Si quieres compilar cada driver de forma local mira [esto](https://github.com/Hakkuraifu/PS4Linux-ArchDrivers#how-i-install-the-drivers-), también es recomendable usar "Iniciar sesión automáticamente")

#### 3) Haz una copia de seguridad de tu SO.

Tras instalar los drivers y personalizar el SO como a ti te guste, puedes hacer una copia de seguridad del SO que vas a instalar en tu PS4.

Primero ve a la carpeta raíz.

```cd /```

Ahora ya puedes hacer una copia de seguridad de tu SO (el comando cambiará dependiendo del SO que uses).

(Reemplaza 'Nombre_Distro' por el nombre de tu distribución).

```sudo tar -cvf Nombre_Distro.tar.xz --exclude=/Nombre_Distro.tar.xz --exclude=/var/cache --one-file-system / -I "xz -9"```

 TAMAÑO MÁXIMO <=3.2GB.


#### 4) Instalando el SO.

⚠️ ¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡USA UN DISPOSITIVO DE 16GB o más y USB 3.0!!!!!!!!!!!!!!!!!!!!!! ⚠️

- Formateta el USB en fat32 (puedes usar [este software](http://ridgecrop.co.uk/index.htm?guiformat.htm)).

- Pon los archivos bzimage, initramfs.cpio.gz y el SO en la raíz de tu USB.

- Renombra el SO por 'psxitarch.tar.xz' (si usas el initramfs.cpio.gz de Nazky renombra el SO a arch.tar.xz).

- Lanza el payload de 1GB de Linux (los otros fallan más o son necesarios si usas algún emulador) usando algún enlace de los de abajo.

- Cuando rescushell arranque, lanza ```exec install-psxitarch.sh``` (si usas el initramfs.cpio.gz de Nazky lanza ```exec install-arch.sh```) y espera.

- Cuando acabe la instalación, el SO arrancará automáticamente, si el SO no arranca, lanza  ```exec start-psxitarch.sh``` (si usas el initramfs.cpio.gz de Nazky lanza ```exec start-arch.sh```) y espera (tendrás que lanzar ```exec start-arch.sh``` dos veces cada vez que inicies/reinicies el SO).

#### Opcional - Instalando el SO en el disco duro interno.

⚠️ ¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡Usa una PS4 compatible!!!!!!!!!!!!!!!!!!!!!! ⚠️

- Usa un cliente FTP y transfiere los archivos bzimage, el initramfs.cpio.gz de Nazky y el SO a /usr/system/boot.
- Lanza cualquier Linux GB usando alguno de los enlaces de abajo. 
- Cuando rescushell arranque, lanza ```exec install-HDD.sh``` y pon la cantidad de GB del disco duro que quieres dedicarle de tu disco duro.
- Espera...
- Cuando acabe la instalación, el SO arrancará automáticamente, si el SO no arranca, pulsa **CTRL + D** o lanza ```exec start-arch.sh```.

#### Opcional - Desinstalación.

Para desinstalar un SO de un dispositivo USB simplemente formatea el dispositivo USB.

#### Opcional - Desinstalar el SO del disco duro interno.
Para desinstalar un SO de un disco duro interno, borra el fichero **Arch.img** de /usr/home.

## Enlaces fiables.

Esta lista puede cambiar en el futuro.

- http://ps4xploit.zd.lu | Creado por [Nazky](https://twitter.com/NazkyYT)
- http://kmeps4.site | Creado por [Kameleon](https://twitter.com/KameleonRe)
- http://xperiments.in/xhost/ | Creado por [xps3riments](https://twitter.com/xps3riments)
- http://karo218.ir | Creado por [Karo](https://twitter.com/karo_sharifi)


## Pequeño P&R

### Solo aparece un pantallazo negro
Es un 'fallo' en el kernel 5.x tienes que refrescar tu HDMI, lo más fácil es esperar hasta que no recibas señal y luego mover el ratón o pulsar una tecla del teclado.

### Sigo teniendo el pantallazo negro aunque uso el kernel 4.14
Asegúrate que tu dispositivo es compatible con la resolución a 1080p, si sigues teniendo un pantallazo negro prueba con otros monitores.

### No tengo WIFI o Bluetooth
Esto es causado por el kernel o por la distribución, la única forma de arreglarlo es programando ese driver o usando un USB externo de wifi o de bluetooth.

### ¿Por qué algunas aplicaciones no funcionan?
Las aplicaciones FlatPak suelen fallar en PS4, y las aplicaciones Snaps directamente no funcionan, no hay forma de arreglarlo, usa AUR o instalación de otros paquetes.

### ¿Por quéo puedo usar mi controlador como ratón?
Algunas distribuciones no tienen preinstalado el driver ds4drv (Cutefish OS, por ejemplo) usa la tienda (pamac) para instalar ds4drv (es recomendable instalar el controlador de movimiento) tras instalarlo, abre una terminal, conecta tu DS4 por USB y lanza ```ds4drv --hidraw ```.
