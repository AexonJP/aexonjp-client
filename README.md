# AexonJP client

Game client for **AexonJP**, a Growtopia private server. Download page: <https://growtopia.aexonjp.net>

| Platform | File | Size |
|---|---|---|
| Windows | [AexonJP-Windows.rar](https://github.com/AexonJP/aexonjp-client/releases/latest/download/AexonJP-Windows.rar) | 280 MB |
| Android | [AexonJP-Android.apk](https://github.com/AexonJP/aexonjp-client/releases/latest/download/AexonJP-Android.apk) | 238 MB |

The files are attached to the [latest release](https://github.com/AexonJP/aexonjp-client/releases/latest),
not stored in the repository. `SHA256SUMS` lists their checksums.

## Windows

1. Extract `AexonJP-Windows.rar` with WinRAR or 7-Zip, anywhere you like.
2. Open the `AexonJP` folder and run `Growtopia.exe`.
3. Create a GrowID on the login screen.

## Android

1. Uninstall the Play Store version of Growtopia. This build is signed with a different key, so
   Android refuses to install it over the official one.
2. Open `AexonJP-Android.apk` and allow "Install unknown apps" when asked.
3. Open Growtopia and create a GrowID on the login screen.

Needs a 64-bit (arm64) phone. The APK is Growtopia 5.59 with the server address changed

## Checking a download

```sh
sha256sum -c SHA256SUMS      # Linux, in the folder with the downloaded files
```

On Windows: `certutil -hashfile AexonJP-Windows.rar SHA256` and compare with `SHA256SUMS`.

---

AexonJP is run by fans. It is not affiliated with or endorsed by Ubisoft or Growtopia.
