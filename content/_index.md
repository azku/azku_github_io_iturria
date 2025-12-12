---
title: Grafana
type: docs
---

# Sistemak eta Aplikazio Informatikoak
## Dokumentazio hau lokalki matxan jarri
### Kodea lortu
2 biltegi daude Githuben proiektu honekin erlazionaturik:
- azku_github_io_iturria: Hemen Hugo eduki dinammikoa dago.
- azku.github.io: Hau submodulo bat da eta aurreko eduki dinamikoa hugorekin konpilatutakoan sortzen den eduki estatikoa dauka.

Kode guztia pauso batean lortzeko
```bash { lineNos=inline tabWidth=2}
git clone --recurse-submodules -j8 git@github.com:azku/azku.github.io.git
```
### Hugo Instalatu
```bash { lineNos=inline tabWidth=2}
sudo snap install hugo
 ```
### Hugo exekutatu
```bash { lineNos=inline tabWidth=2}
hugo server --minify --theme hugo-book
```
