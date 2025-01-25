## QR code renderer

Based on https://github.com/bizzycola/qrcode-generator

Tag latest by date

```bash
TAG=v$(date -u +'%Y%m%d').1
git tag -a $TAG
git push origin $TAG
```