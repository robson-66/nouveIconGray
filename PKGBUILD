pkgname=nouveicongray
pkgver=1.0
pkgrel=1
pkgdesc="Icons adapted to the following environments: KDE, GNOME, Xfce4"
arch=('any')
url="https://www.deviantart.com/tsujan/art/nouveGnomeGray-300365158"
license=('GPL')
source=("nouveIconGray.tar.gz")
sha256sums=('SKIP')

package() {
  install -d -m755 $pkgdir/usr/share/icons

  cd $srcdir
  mv nouveIconGray $pkgdir/usr/share/icons/
  
  find $pkgdir/usr -type f -exec chmod 644 {} \;
  find $pkgdir/usr -type d -exec chmod 755 {} \;
  find $pkgdir/usr -type f -name '.directory' -delete
}
