# Flatpak for nomacs
![nomacs screenshot](https://nomacs.org/wp-content/uploads/2020/03/img-2020-03-18-11.49.26-1.png)
This is my personal flathub cheatsheet

*Build it*
```bash
flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
./build.sh
```

*Test it*
```bash
flatpak-builder --run build_x86_64 org.nomacs.ImageLounge.json nomacs
```

## Update
push a commit with `Update org.nomacs.ImageLounge.json` to update the package on flathub
