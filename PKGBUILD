# Contributor: Daniel Mendler <mail@daniel-mendler.de>

pkgname=pacgem
pkgver=0.1
pkgrel=1
pkgdesc="Install Ruby Gems as Arch Linux packages"
arch=('any')
url="http://github.com/minad/pacgem"
license=('Ruby')
depends=('ruby')
source=('pacgem')
sha256sums=('f87d4443ee830beedad8c57e693429f34b90ecc71785d1a74101d5306d1a9cac')

build() {
  install -D -m755 $srcdir/pacgem $pkgdir/usr/bin/pacgem
}
