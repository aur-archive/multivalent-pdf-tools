# Maintainer: Olivier Mehani <shtrom-aur@ssji.net>
# $Id: PKGBUILD 351 2013-12-21 09:48:20Z shtrom $
pkgname=multivalent-pdf-tools
_arcname=Multivalent
pkgver=20060102
pkgrel=1
pkgdesc="PDF tools to compress, impose, decrypt/encrypt, split/merge from Multivalent"
arch=(any)
url="http://sourceforge.net/projects/multivalent/"
license=('GPL')
depends=("java-runtime")
# XXX: This version is no longer available from the upstream source, but newer
# versions do not ship the PDF tools
#source=(https://scm.narf.ssji.net/svn/archlinux-packages/export/350/multivalent-pdf-tools/Multivalent20060102.jar)
# XXX: My trac is currently broken
source=(https://scm.narf.ssji.net/Multivalent20060102.jar)

package() {
  install -D -m 644 $srcdir/$_arcname$pkgver.jar $pkgdir/usr/share/java/multivalent/$_arcname$pkgver.jar
}

# vim:set ts=2 sw=2 et:
md5sums=('813bb651a1cc6ea230f28aac47f78051')
