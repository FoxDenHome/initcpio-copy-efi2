# Maintainer: Doridian <archlinux at doridian dot net>

pkgname=initcpio-copy-efi2
pkgver=1.1
pkgrel=1
pkgdesc='Copy /efi to /efi2 basically'
arch=('any')
url='https://github.com/FoxDenHome/initcpio-copy-efi2'
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
  install -Dm755 "${srcdir}/initcpio.post" "${pkgdir}/etc/initcpio/post/99-efi2"
}
