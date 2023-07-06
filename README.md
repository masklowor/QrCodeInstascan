# QrCodeRizkyNet
QR Code Using HTML5QrscannerCode.min.js
This is my QR Scanner Learning Project
## QR Code scanner for login hotspot MikroTik

### Cara pakai

1. Tambahkan button di login.html
```html
<button onclick="window.location='https://masklowor.github.io/myqr';">QR Code</button>
```
2. Tambahkan script berikut di MikroTik via Terminal.
```
/ip hotspot walled-garden ip

add action=accept comment="Mikhmon QR Code Scanner" disabled=no dst-host=masklowor.github.io
```

### Powered by rizkyNet
