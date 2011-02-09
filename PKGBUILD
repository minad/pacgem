# Contributor: Daniel Mendler <mail@daniel-mendler.de>

pkgname=pacgem
pkgver=0.9.1
pkgrel=1
pkgdesc="Install Ruby Gems as Arch Linux packages"
arch=('any')
url="http://github.com/minad/pacgem"
license=('GPL')
depends=('ruby')
source=('pacgem' 'pacgem.8')
sha256sums=('34973fe5327396dc9f4571efe6d6643202f34483ee5be031d578a02a88851fd4'
            '50d70c1a35ffe9ea4157dc6d1245aa8b47e3aacb7dd1410ecebfa3ac8c746a2e')
conflicts=('pacgem-git')

build() {
  install -D -m755 $srcdir/pacgem $pkgdir/usr/bin/pacgem
  install -D -m644 $srcdir/pacgem.8 $pkgdir/usr/share/man/man8/pacgem.8
}
