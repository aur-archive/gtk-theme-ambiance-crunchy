pkgname=gtk-theme-ambiance-crunchy
pkgver=1397966229
pkgrel=1
pkgdesc='Ambiance like Theme for Openbox, Xfce, Gnome2/3, Unity/Gnome-Shell.'
arch='any'
url='http://box-look.org/content/show.php/?content=136162'
license=GPL
depends=('gtk-engine-murrine')
optdepends=('gtk-engine-unico')
source='http://box-look.org/CONTENT/content-files/136162-Crunchy-themes.tar.gz'
md5sums='8b4f4129b1a1980f6014e91674af31d0'

pkgver() {
	echo $(stat -c %Y 136162-Crunchy-themes.tar.gz)
}

package() {
  cd "${srcdir}/themes"

  mkdir -p ${pkgdir}/usr/share/themes/
  cp -R * ${pkgdir}/usr/share/themes/
}
