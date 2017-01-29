
# Archer T2U Ubuntu installer

Installation:

* Python2.7

`git clone https://github.com/ivannieto/archer-t2u-ubuntu-installer.git`

`cd archer-t2u-ubuntu-installer/ && python t2u-installer.py`

* Python3

`git clone https://github.com/ivannieto/archer-t2u-ubuntu-installer.git`

`cd archer-t2u-ubuntu-installer/ && python3 t2u-installer.py`

This script installs the driver for Archer T2U USB Wi-Fi adapter, and it's patched by:

* [chenhaiq](https://github.com/chenhaiq)
* [mt7610u_wifi_sta_v3002_dpo_20130916](https://github.com/chenhaiq/mt7610u_wifi_sta_v3002_dpo_20130916).

It works on systems using Ubuntu <=16.10. It should work for RaspberryPi3 (still not tested).

For more info configuring the adapter please refer to `CONFIGURATION.md`. Also reading the `README.md` included in `driver-files` will solve some possible runtime errors.

Just follow the instructions from the program prompt.

## **Restart your computer when the installation is finished** 

Once you had restarted, you can enable or disable the driver. Plug your USB dongle and run:

```
sudo t2u-driver
```

