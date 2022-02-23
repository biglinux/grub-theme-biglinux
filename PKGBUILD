# Maintainer: Bruno Goncalves <bigbruno@gmail.com>

pkgname=grub-theme-biglinux
pkgver=1.0.0
pkgrel=2
arch=('any')
license=('GPL')
url="https://github.com/biglinux/grub-theme-biglinux"
pkgdesc="Grub theme"
source=("git+https://github.com/biglinux/grub-theme-biglinux.git")
md5sums=(SKIP)


package() {
    cp -r "${srcdir}/grub-theme-biglinux/grub-theme-biglinux/boot/" "${pkgdir}/"
    cp -r "${srcdir}/grub-theme-biglinux/grub-theme-biglinux/usr/" "${pkgdir}/"
}
