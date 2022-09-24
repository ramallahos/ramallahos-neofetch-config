# Maintainer: Safwan Nayeem Yousuf <safwannayeemyousuf.com>
pkgname=ramallahos-neofetch-config
pkgver=1
pkgrel=1
pkgdesc="Neofetch config for RamallahOS"
arch=('any')
url="https://github.com/ramallahos/$pkgname"
license=('GPL3')
depends=('neofetch')
makedepends=('coreutils')
source=("$pkgname::git+$url.git")
sha256sums=('SKIP')

package() {
    cd "$pkgname"
    install -d "${pkgdir}/etc/skel/.config/neofetch"
    install -Dm 644 "config.conf" "${pkgdir}/etc/skel/.config/neofetch/config.conf"
}
