# V2ray Client Setups

**Reference**: [从零开始：史上最详尽V2Ray搭建图文教程](https://www.4spaces.org/digitalocean-build-v2ray-0-1/)

## Installation

````{tab-set}
```{tab-item} Windows
:sync: key1

- Download [v2rayN-Core.zip](https://github.com/2dust/v2rayN/releases/latest)

```
```{tab-item} macOS
:sync: key2

- Install [V2rayU](https://github.com/yanue/V2rayU/tree/master)

    **Install from homebrew**

    ```bash
    brew install --cask v2rayu
    ```

    **Install from package** 

    Download the [latest version](https://github.com/yanue/V2rayU/releases/latest)

```
```{tab-item} iOS/iPadOS
:sync: key3
- [Download](https://apps.apple.com/us/app/v2box-v2ray-client/id6446814690) V2BOX app on your devices from App Store using an Apple ID registered outside of mainland China.

    ![download_v2box](download_v2box.png)

```
````

## Configuration

````{tab-set}
```{tab-item} Windows
:sync: key1
1. Run `V2RayN.exe` to configure.

    ![dir](v2rayN_client_dir.jpg)

2. Add new server.

    Copy the URL from the administrator, and import it through the option below.

    ![import server](import_url.png)

3. Right-click to **activate** imported server (only required once).

    ![activate server](activate_server.png)

4. Choose proxy mode

    Right click the icon of **v2rayN** in the taskbar, and switch the setting as shown below.
    ![enable proxy](enable.png)

```

```{tab-item} macOS
:sync: key2

1. Run V2rayU from the Launchpad, then open configure.

    ![mac config](v2rayu.jpg)

2. Add new server and import settings with URL copied from administrator.

    ![mac url](mac-import.jpg)

3. Turn v2ray-core on and switch to PAC mode.

    ![open](open.jpg)

4. (Optional) Customize PAC rules if needed.

    ![pac](pac_setting.png)
```
```{tab-item} iOS/iPadOS
:sync: key3
1. Run V2BOX app on your devices, and open configure.

    ![config_v2box](config_v2box.png)

2. Add new server and import settings with URL copied from administrator.

    ![after_config_v2box](after_config_v2box.png)   

3. Turn VPN on.
    
    ![enable_v2box](enable_v2box.png)
```
````

**Enjoy yourself with Google, Youtube, Dropbox, Docker, and etc.**