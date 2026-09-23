# shadowrocket-modules

Shadowrocket modules converted from the AppTesters Egern configuration.

Upstream configuration: https://apptesters.org/egern.yaml

Each module is kept separate and uses the original AppTesters script URL. No JavaScript files are mirrored in this repository.

## Modules

- RevenueCat
- Adapty
- Facemoji
- Readdle
- iTunes
- MuslimPro
- Grammarly
- eSound
- Purchasely
- Vaia
- Qonversion
- edjingMix
- VivaCut
- Carrot
- KineMaster
- PicsArt
- AlightMotion
- SandBox
- SongShift
- AdblockPro
- AdGuardPro

The three placeholder entries that use `ILoveDevTheDev.com` and `URL2Script.com` are intentionally not included.

## Notes

HTTPS response/request scripting requires Shadowrocket HTTPS decryption to be enabled and its CA certificate to be installed and trusted.

The modules add only the MITM hostname needed by that module by using `%APPEND%`, so they do not replace the existing hostname list.
