pkgname=eblanfetch
pkgver=1.0
pkgrel=1
pkgdesc="Stoopid ahh Python fetch"
arch=('any')
url="https://github.com/dirolov/eblanfetch"
license=('MIT')
depends=('python')
source=("https://github.com/dirolov/eblanfetch/archive/refs/tags/v$pkgver.tar.gz"\)
sha256sums=('SKIP')

package() {
  install -Dm755 "$srcdir/$pkgname-$pkgver/eblanfetch.py" "$pkgdir/usr/bin/eblanfetch"
}
