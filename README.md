# lede-17.01.4-packages

1. Manually download the opkg_2017-03-23-9f61f7ac-1_mips_24kc.ipk and update in firmware.
1. Edit the /etc/opkg.conf and add "option no_check_certificate 1"
1. Edit the /etc/opkg/customfeeds.conf and add "src/gz master_feeds https://github.com/masterrd/lede-17.01.4-packages/releases/download/v1.1/"
1. Run opkg update 
