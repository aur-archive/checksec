# Maintainer: Lubomir Krajcovic <lubomir.krajcovic(AT)gmail(DOT)com>

pkgname='checksec'
pkgver='1.5'
pkgrel=2
pkgdesc='Tool designed to test what standard Linux OS and PaX security features are being used.'
url='http://www.trapkit.de/tools/checksec.html'
arch=('any')
license=('BSD')
depends=()
makedepends=()
source=("http://www.trapkit.de/tools/checksec.sh")
md5sums=('075996be339ab16ad7b94d6de3ee07bd')

package() {
	install -m755 -oroot -D "${srcdir}/checksec.sh" "${pkgdir}/usr/bin/checksec.sh" || return 1
}
