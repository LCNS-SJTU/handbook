# V2ray Client Setups

**Reference**: [从零开始：史上最详尽V2Ray搭建图文教程](https://www.4spaces.org/digitalocean-build-v2ray-0-1/)

## Installation

````{tab-set}
```{tab-item} Windows
:sync: key1

- Download [v2rayN-With-Core.zip](https://github.com/2dust/v2rayN/releases/latest)

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

    ```{note}
    If your v2rayU version is v3.8.0, please check this [issue](https://github.com/yanue/V2rayU/issues/1299#issue-1836601726) to manually update xray-core.
    ```

```
```{tab-item} iOS/iPadOS
:sync: key3
- [Download](https://apps.apple.com/us/app/v2box-v2ray-client/id6446814690) V2BOX app on your devices from App Store using an [Apple ID registered outside of mainland China](https://www.youtube.com/watch?v=BK_TT8zEuxU&t=0s).

    ```{figure} download_v2box.jpg
    ---
    scale: 25%
    align: center
    ---
    ```

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

    ```{figure} config_v2box.jpg
    ---
    scale: 25%
    align: center
    ---
    ```

2. Add new server and import settings with URL copied from administrator.

    ```{figure} after_config_v2box.jpg
    ---
    scale: 25%
    align: center
    ---
    ```

3. Turn VPN on.
    
    ```{figure} enable_v2box.jpg
    ---
    scale: 25%
    align: center
    ---
    ```

4. (Optional) Customize routing rules to selectivly proxy your data if needed.

    [V2BOX routing setup URL](https://gist.githubusercontent.com/vveg26/d856567e4964cc1fb6a20ed00124fccf/raw/d18d0ac58264c09ddcb02c33dde495b952bc27d3/v2boxroute.txt)

    ```{figure} setup_routing.jpg
    ---
    scale: 25%
    align: left
    ---
    ```
    ```{figure} import_routing_url.jpg
    ---
    scale: 25%
    align: right
    ---
    ```
    ```{figure} import_routing_url1.jpg
    ---
    scale: 25%
    align: left
    ---
    ```
    ```{figure} import_routing_url2.jpg
    ---
    scale: 25%
    align: right
    ---
    ```
```
````

**Enjoy yourself with Google, Youtube, Dropbox, Docker, and etc.**