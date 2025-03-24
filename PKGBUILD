# Maintainer: Doridian <archlinux at doridian dot net>

# Make sure to put "sd-pcr7lock" in /etc/mkinitcpio.conf

pkgname=efi2
pkgver=1.0
pkgrel=1
pkgdesc='Copy /efi to /efi2 basically'
arch=('any')
url='https://aur.archlinux.org/mkinitcpio-cleviseal-hook'
license=('MIT')
depends=('bash')
source=(
  'initcpio.post'
)
md5sums=(
  'SKIP'
)

build() {
  echo 'No build step needed'
}

package() {
  install -Dm755 "${srcdir}/initcpio.post" "${pkgdir}/etc/initcpio/post/efi2"
}
