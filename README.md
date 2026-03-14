# MediaConch

___Implementation checker, policy checker, reporter, and fixer___

MediaConch is an implementation checker, policy checker, reporter, and fixer 
that targets preservation-level audiovisual files

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing.

```bash
flatpak install flathub net.mediaarea.MediaConch
flatpak run net.mediaarea.MediaConch
```

## Building

```bash
git clone git@github.com:flathub/net.mediaarea.MediaConch.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install net.mediaarea.MediaConch.json
```
