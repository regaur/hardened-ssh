# Maintainer: Jan Boelsche <jan@lagomorph.de>

pkgname='hardened-ssh'
pkgver=1.0
pkgrel=1
pkgdesc='Modifies /etc/ssh/sshd_config to, among other things, disallow password auth to heighten security.'
packager='Jan Boelsche'
arch=('any')
license=('GPL')
groups=()
depends=('openssh')
makedepends=()
checkdepends=()
optdepends=()
install=${pkgname}.install
source=(ssh_harden.sh )

sha256sums=('58ebe1f681cfdf81a1812be2d27e0bcfd0a6421b47967d86a3fb4a51e2cd89da')

package() {
	install -m 744 -t "${pkgdir}/usr/share/${pkgname}" harden_ssh.sh
}
