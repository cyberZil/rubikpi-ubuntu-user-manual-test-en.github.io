# Update Software

After completing the setup and once the device has successfully booted, verify the OS version by running the following commands in the device shell:

        ```shell
        cat /etc/os-release 
        ```
    Output: 
        ```json
    NAME="Ubuntu"
    VERSION_ID="24.04"
    VERSION="24.04.2 LTS (Noble Numbat)"
    VERSION_CODENAME=noble
    ID=ubuntu
    ID_LIKE=debian
    HOME_URL="https://www.ubuntu.com/"
    SUPPORT_URL="https://help.ubuntu.com/"
    BUG_REPORT_URL="https://bugs.launchpad.net/ubuntu/"
    PRIVACY_POLICY_URL="https://www.ubuntu.com/legal/terms-and-policies/privacy-policy"
    UBUNTU_CODENAME=noble
    LOGO=ubuntu-logo
    ```

Based on the OS version, follow one of the path below to upgrade or flash your software.  
|Path to choose| Purpose           | Links|
|--------------|-------------------|------|
|Upgrade Preinstalled Ubuntu to Latest Canonical Build (Without Reflashing)|If your Rubik Pi already runs Ubuntu and you just want to upgrade it cleanly with all the latest tools and fixes — without starting from scratch — this is your go-to path.|[**🔗Upgrade Canonical Ubuntu to Latest Build**](https://hongyang-rp.github.io/rubikpi-ubuntu-user-manual-test-en.github.io/docs/Document%20Home/Update-Software/3.1.upgrade-ubuntu)|
|Flash Canonical Ubuntu 24.04 Over Android/QLI (For Fresh Ubuntu Setup)|Use this path if your device is currently running Android or Qualcomm Linux (QLI) and you want to completely switch to Canonical Ubuntu 24.04 for development.|[**🔗 Flash images using Qualcomm Launcher**](https://hongyang-rp.github.io/rubikpi-ubuntu-user-manual-test-en.github.io/docs/Document%20Home/Update-Software/3.4.Flash-using-Qualcomm-Launcher)|
|Reset to Factory Ubuntu Image (Recovery or Clean Start)|If your Ubuntu setup is messed up or you want a clean slate — use this to reset everything.|[**🔗 Flash Canonical Ubuntu 24.04 Over Android/QLI**](https://hongyang-rp.github.io/rubikpi-ubuntu-user-manual-test-en.github.io/docs/Document%20Home/Update-Software/3.3.Reset-system-image)|