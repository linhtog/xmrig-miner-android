# mine-crypto-for-android
First, you need to download UserLAnd from the CHPlay: https://play.google.com/store/apps/details?id=tech.ula&pcampaignid=web_share
Select Ubuntu to install.
Then, use the following commands in sequence to install:

    apt-get update -y
    apt-get upgrade -y
    sudo apt install ca-certificates
    sudo apt update -y && sudo apt install curl -y && curl https://raw.githubusercontent.com/HighVoltage557/XmrigOnAndroid/main/compile.sh| bash
    cd && cd xmrig/build
