# ResPinGuy - The Kompiler
## Créer une image ISO de son système Linux.

⚠!!! ResPinGuy ne fonctionne pas encore !!!⚠

![ResPinGuy](http://respinguy.tk/logo-img-theme/logo/ResPinGuy-BF.png)

### Dépendance :
- git
- wget
- sudo
- bash
- sh
- nano
- uname (avec prise en charge de -r et -m)
- mksquashfs (avec prise en charge de -comp xz, la dépendance est généralement appelée: squashfs-tools)
- dracut
- xorriso


### Simple utilisateur :
Install Command:

```bash
wget respinguy.tk/FTP/file-respinguy/Install-ResPinGuy && sudo bash Install-ResPinGuy
```

### Forkeur :
Fork Command:
```bash
  mkdir respinguy-fork && cd respinguy-fork && git clone https://github.com/ResPinGuy/ResPinGuy.git && cd ResPinGuy && bash ./build
```

&copy; 2021 [ResPinGuy](http://respinguy.tk)
