# Maintainer: Jonathan Sanfilippo  <jonalinux dot uk at gmail dot com>

pkgname=architalia-fonts
pkgver=1.0
pkgrel=1
pkgdesc="Architalia-live fonts"
arch=('any')
license=('GPL')
#source=(' Architalia-Mono.eot, Architalia-Mono.woff2, Architalia-Regular.woff,  ArchitaliaTextMedium-Regular.ttf, Architalia-Mono.otf,  Architalia-Regular.otf,  Architalia-Regular.woff2, ArchitaliaTextMedium-Regular.woff, ArchitaliaTextMedium-Regular.otf,  ArchitaliaTextMedium-Regular.woff2, Architalia-Mono.ttf,  Architalia-Regular.ttf')

package() {
   install -Dm755 *.eot "$pkgdir/usr/share/fonts"
    install -Dm755 *.otf "$pkgdir/usr/share/fonts"
     install -Dm755 *.ttf "$pkgdir/usr/share/fonts"
      install -Dm755 *.woff "$pkgdir/usr/share/fonts"
       install -Dm755 *.woff2 "$pkgdir/usr/share/fonts"
}

