PostmarketOS rootfs build ci in GitHub
======
[![](https://img.shields.io/github/actions/workflow/status/sekaimoe/pmos_ci_build/main.yml?style=for-the-badge&color=fee4d0&logo=githubactions&logoColor=fee4d0)](https://github.com/sekaimoe/pmos_ci_build/actions/workflows/main.yml)
[![](https://img.shields.io/github/license/sekaimoe/pmos_ci_build?style=for-the-badge&color=fee4d0&logo=apache&logoColor=fee4d0)](https://github.com/sekaimoe/pmos_ci_build/blob/main/LICENSE)

## Supported device
- xiaomi-raphael
- xiaomi-lmi(Not add upstream yet)

> [!NOTE]
> 
> This root is not working stably at the moment.

## How to flash
- Make sure install [TWRP](https://twrp.me) first
- Reboot into recovery mode
- Enable sideload
- Download zip for your device
- Run adb sideload
- Reboot and have fun in linux

> [!IMPORTANT]
> 
> Before flashing in, please back up important data on your phone!

## License
GPL-3.0 license
