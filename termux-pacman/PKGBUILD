# Maintainer: Subuntu X <subuntux@github.com>
pkgname=pac-manager
pkgver=1.3
pkgrel=1
pkgdesc="Termux Menu"
arch=('aarch64') # 'any', weil ursprünglich "all" angegeben wurde
url="https://github.com/subuntux/term-master"
license=('unknown') # Die Lizenz wurde nicht angegeben. Bitte entsprechend anpassen.
depends=('python3')
source=("manager.py") # Lokale Datei direkt angeben
noextract=() # Da wir keine Archive haben, die extrahiert werden müssen
sha256sums=('SKIP') # 'SKIP', da lokale Dateien verwendet werden

package() {
  # Installationspfad anlegen
  install -dm755 "$pkgdir/data/data/com.termux/files/usr/bin"

  # Installieren der Datei mit den richtigen Berechtigungen
  install -Dm755 "$srcdir/manager.py" "$pkgdir/data/data/com.termux/files/usr/bin/pac-manager"
}
