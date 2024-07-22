# Maintainer: GuestSneezeOSDev <github DOT com SLASH GuestSneezeOS>

pkgname=playtronOS-archiso-config
pkgver=0.14.5.35
pkgrel=1
pkgdesc="Custom Archiso configuration of PlaytronOS by GuestSneezeOSDev"
arch=('any')
url="https://playtron.one"
license=('GPL')
depends=('archiso')
source=("https://github.com/GuestSneezeOSDev/PlaytronOS-archiso-config/blob/main/playtron-os-files-main.tar.gz")
sha256sums=('SKIP')

package() {
  cd "$srcdir/playtron-os-files-main"

  # Install files
  install -dm755 "$pkgdir/usr/share/$pkgname"
  cp -r ./* "$pkgdir/usr/share/$pkgname/"
}
