# Contributor: Daniel Mendler <mail@daniel-mendler.de>

pkgname=pacgem
pkgver=0.9
pkgrel=1
pkgdesc="Install Ruby Gems as Arch Linux packages"
arch=('any')
url="http://github.com/minad/pacgem"
license=('GPL')
depends=('ruby')
source=('pacgem' 'pacgem.8')
sha256sums=('4845544ff2ac74e7acf3f41e60f39cce5742c421b60288bea69e506322ebcc97'
            'd99542ba8b78e81bb04531e3b4885cbfca174f29b52ae7f7aa962d1d0e9ef94e')
conflicts=('pacgem-git')

build() {
  install -D -m755 $srcdir/pacgem $pkgdir/usr/bin/pacgem
  install -D -m644 $srcdir/pacgem.8 $pkgdir/usr/share/man/man8/pacgem.8
}
