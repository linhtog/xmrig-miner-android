# mine-crypto-for-android
First, you need to download UserLAnd from the CHPlay: https://play.google.com/store/apps/details?id=tech.ula&pcampaignid=web_share
Select Ubuntu to install.
Then, use the following commands in sequence to install:
1,

    apt-get update -y
2,

    apt-get upgrade -y
3,

    sudo apt install ca-certificates
4,

    sudo apt update -y && sudo apt install curl -y && curl https://raw.githubusercontent.com/HighVoltage557/XmrigOnAndroid/main/compile.sh| bash
5,

    cd && cd xmrig/build
6,This is the command to start mining, I will take an example with Unmineable pool

    ./xmrig -o rx.unmineable.com:3333 -a rx -k -u COIN:YOUR_ADDRESS.WORKER_NAME -p x pause

   Replace "rx.unmineable.com:3333" with any pool you need. 
   You must change COIN, YOURADDRESS and WORKER_NAME

   OR  set it up according to the official XMRIG website : https://xmrig.com/wizard


DONATIONS  XMR: 4DSQMNzzq46N1z2pZWAVdeA6JvUL9TCB2bnBiA3ZzoqEdYJnMydt5akCa3vtmapeDsbVKGPFdNkzqTcJS8M8oyK7WGm3TmXEP4G3V9Qx3H
           BnB: 0xab5122c4e645fbe270cb21f82e7d59c9cb6f9492
