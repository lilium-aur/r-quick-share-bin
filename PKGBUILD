# Maintainer : Arman <me@slce.moe>

pkgname=r-quick-share-bin
pkgver=0.2.0
_glibcver=2.31
pkgrel=4
pkgdesc='Rust implementation of NearbyShare/QuickShare from Android for Linux.'
arch=('x86_64')
url='https://github.com/Martichou/rquickshare'
license=('AGPL-3.0-or-later')
depends=('webkit2gtk' 'gtk3')
provides=('r-quick-share')
conflicts=('r-quick-share')
source=("https://github.com/Martichou/rquickshare/releases/download/v${pkgver}/r-quick-share_${pkgver}_amd64_GLIBC-${_glibcver}.deb")
sha256sums=('62a53709ac4e0f31bb89151c4afcdb625ce186fc56633956269bf65aaa286989')

package() {
    bsdtar -xf "data.tar.gz" -C "$pkgdir"
}