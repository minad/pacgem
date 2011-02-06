# Contributor: Daniel Mendler <mail@daniel-mendler.de>

pkgname=pacgem
pkgver=0.1
pkgrel=2
pkgdesc="Install Ruby Gems as Arch Linux packages"
arch=('any')
url="http://github.com/minad/pacgem"
license=('Ruby')
depends=('ruby')
source=('pacgem')
sha256sums=('b6980d92b20ad61248d262a0083e39f7e213e2e73bdf3a0ba41ae315fbb676f6')

build() {
  install -D -m755 $srcdir/pacgem $pkgdir/usr/bin/pacgem
}
