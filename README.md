# Flatpak for nomacs
This is my personal cheatsheet

*Build it*
```bash
flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
./build.sh
```

*Test it*
```bash
flatpak-builder --run build_x86_64 org.nomacs.ImageLounge.json nomacs
```