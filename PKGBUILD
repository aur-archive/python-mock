# Contributor: Felix Kaiser <felix.kaiser@fxkr.net>

pkgname=python-mock
pkgver=1.0.1
pkgrel=1
pkgdesc="A Python Mocking and Patching Library for Testing"
url='http://www.voidspace.org.uk/python/mock/'
license=('BSD')
depends=('python')
arch=('i686' 'x86_64')
source=("http://pypi.python.org/packages/source/m/mock/mock-$pkgver.tar.gz")
md5sums=('c3971991738caa55ec7c356bbc154ee2')

build() {
  cd "$srcdir/mock-$pkgver"
  python setup.py install --optimize=1 --root="$pkgdir"
}
