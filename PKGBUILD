# Maintainer: Jonathan Sanfilippo  <jonalinux dot uk at gmail dot com>

pkgname=architalia-fonts
pkgver=1.0
pkgrel=1
pkgdesc="Architalia-live fonts"
arch=('any')
license=('GPL')

package() {
   install -Dm755 *.eot "$pkgdir/$(eval echo ~${USER})/.local/share/fonts/"
   install -Dm755 *.otf "$pkgdir/$(eval echo ~${USER})/.local/share/fonts/"
   install -Dm755 *.ttf "$pkgdir/$(eval echo ~${USER})/.local/share/fonts/"
   install -Dm755 *.woff "$pkgdir/$(eval echo ~${USER})/.local/share/fonts/"
   install -Dm755 *.woff2 "$pkgdir/$(eval echo ~${USER})/.local/share/fonts/"
}
