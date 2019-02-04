# Maintainer: Lutfa Ibtihaji Ilham <lutfailham96 at gmail dot com>

pkgname=dalisha-icon
pkgver=3.0
pkgrel=1
pkgdesc="Dalisha Icon Pack"
arch=('any')
license=('GPL3')
depends=('gtk-update-icon-cache'
    'hicolor-icon-theme')
source=("${pkgname}"::git+https://github.com/ccsysadmin/dalisha-icon.git)
sha256sums=('SKIP')
options=('!strip')

package() {
  #cd "${srcdir}"/"${pkgname}"
  #rm -rf "${srcdir}"/"${pkgname}"/.git
  install -dm 755 "${pkgdir}"/usr/share/icons/Dalisha
  cp -r "${srcdir}"/"${pkgname}"/* "${pkgdir}"/usr/share/icons/Dalisha
  #install -m755 google-chrome-$_channel.sh "$pkgdir"/usr/bin/google-chrome-$_channel
}
