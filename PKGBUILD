# Maintainer: Jonathan Sanfilippo  <jonalinux dot uk at gmail dot com>
# PKGBUILD per il pacchetto core-theme

pkgname=core-gtk-theme
pkgver=1.9
pkgrel=1
pkgdesc="official Gnome theme Core Linux"
arch=('any')
url=""

# dipendenze necessarie
depends=('gtk-update-icon-cache')

# comandi di installazione
package() {
    # crea la directory di destinazione
    mkdir -p "${pkgdir}/usr/share/themes/"
    # copia i file nella directory di destinazione
    cp -r Core "${pkgdir}/usr/share/themes/Core"
    # crea la directory di destinazione
    mkdir -p "${pkgdir}/etc/gtk-4.0"
    cp -rp gtk-4.0 "${pkgdir}/etc/"
    


    
}
