# Maintainer: lishengming.zju <lishengming.zju@gmail.com>
pkgname=xbmc-addon-repo-hdpfans
pkgver=1.0.0
pkgrel=1
pkgdesc="Download and install add-ons for HDPfans addon repository."
arch=('any')
url="http://www.hdpfans.com/forum-801-1.html"
license=('unknown')
depends=('xbmc')
install=install
source=('http://xbmc.hdpfans.com/repository.hdpfans.xbmc-addons.zip')
md5sums=('46c0629afae7b9cd9801271fec7dbcea')

package() {
    cd ${srcdir}
    find . -type f -exec install -Dm644 {} ${pkgdir}/usr/share/xbmc/addons/{} \;
}
