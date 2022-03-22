pkgname=nouvegnomegray
pkgver=1.0
pkgrel=2
pkgdesc="Icons theme GNOME"
arch=('any')
url="https://www.deviantart.com/tsujan/art/nouveGnomeGray-300365158"
license=('GPL')
source=("nouveGnomeGray.tar.gz")
sha256sums=('SKIP')

package() {
  install -d -m755 $pkgdir/usr/share/icons

  cd $srcdir
  mv nouveGnomeGray $pkgdir/usr/share/icons/
  
  find $pkgdir/usr -type f -name '.directory' -delete
}
