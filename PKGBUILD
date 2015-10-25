# Maintainer: Chrysostomus @forum.manjaro.org

pkgname=mhwd-tui
pkgver=0.1
pkgrel=1
pkgdesc="An interactive mhwd interface using bash"
arch=(any)
url="https://github.com/Chrysostomus/$pkgname"
license=MIT
depends=('pmenu'
	'mhwd'
	'awk'
	'bash')
optdepends=('pacli: package management menu item'
makedepends=('git')
source=("git://github.com/Chrysostomus/$pkgname")
md5sums=('SKIP')

package () {
	cd "$srcdir"
        install -Dm755 "$srcdir/$pkgname/mhwd-tui" "$pkgdir/usr/bin/mhwd-tui"
}
