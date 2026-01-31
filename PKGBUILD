# Maintainer: Gia Phu <crystalforceix@gmail.com>
pkgname="ros-helper-scripts"
pkgver="1.0.0"
pkgrel="1"
pkgdesc="Include ros-installer, ros-reborn, ros-reborn-system-ota"
arch=("x86_64")
depends=(
  "wget"
  "dialog"
)
url="https://github.com/RengeOS/ROS-Helper-Scripts"
package() {
	install -d "${pkgdir}/usr/local/bin"
    install -Dm755 "${srcdir}/usr/local/bin/"* "${pkgdir}/usr/local/bin/"
}
