# T4n OS Dotfiles

Dotfiles T4n OS untuk setup desktop yang **ringan, terkendali, dan minimal**. Ditujukan untuk user yang paham Linux dan tidak bergantung pada GUI berlebihan.

## Lingkungan

* **BSPWM** — Tiling X11, keyboard-centric
* **XFCE4** — Desktop ringan & stabil
* **KDE Plasma** — Desktop lengkap tanpa efek berlebihan
* **RiverWM** — Tiling Wayland, modern & eksperimental

## Struktur Singkat

```text
BSPWM → branch bspwm
RiverWM → branch riverwm
XFCE4 → branch xfce4
KDE Plasma → branch KDE
```

## Penggunaan

> **Peringatan:** Bisa menimpa konfigurasi lama.

```bash
git clone -b bspwm https://github.com/<username>/t4n-dotfiles.git
cp -r bspwm ~/.config/
```

Disarankan pakai `stow` jika paham.

## Catatan

- **BSPWM & RiverWM** → cepat & ringan, tapi perlu adaptasi.
- **XFCE & KDE** → lebih nyaman, tapi lebih berat.

Repo ini tidak untuk user yang ingin klik-klik dan animasi.

## Lisensi

Mengikuti lisensi bebas sesuai masing-masing komponen.

**T4n OS — Control over convenience.**
