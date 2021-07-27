# Maintainer: Baran Karaaslan <barankaraaslan_06@hotmail.com>
pkgname=baran-nginx-package-repo
pkgver=0.1.0
pkgrel=1
pkgdesc="an nginx site for serving packages"
arch=(any)
url=""
license=('GPL')
depends=('nginx' 'baran-nginx')
install=
changelog=
source=("${pkgname}-${pkgver}::git+https://github.com/barankaraaslan/conf-nginx-package-repo.git")

package() {
	cd "$pkgname-$pkgver"
	# echo $pkgdir
	make DESTDIR="$pkgdir" install
}
