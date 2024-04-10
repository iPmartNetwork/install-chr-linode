# install-chr-linode


## Description

نصب میکروتیک روی سرور لینود


How to use this:

(Note this script assumes you are using linode Ubuntu server)

## 1. Download chr on server

```bash
wget https://cdn.mikrotik.com/routeros/7.14.2/chr-7.14.2.img.zip

```

## 1.unzip chr

```bash
unzip chr-7.14.2.img.zip

```

## 3.Run chr

```bash
dd if=chr-7.14.2.img of=/dev/sda bs=1M iflag=fullblock

```
