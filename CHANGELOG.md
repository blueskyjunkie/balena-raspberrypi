Change log
-----------

# v2.29.0+rev1
## (2018-12-19)

* Update meta-resin from v2.28.0 to v2.29.0 [Sebastian Panceac]
* Update balena-yocto-scripts submodule to v1.0.1 [Sebastian Panceac]

# v2.28.0+rev1
## (2018-12-06)

* Update meta-resin from v2.27.0 to v2.28.0 [Alexandru Costache]

<details>
<summary> View details </summary>

## meta-resin-2.28.0
### (2018-12-05)

* Update os-config to 1.0.0 [Zahari Petkov]
* Update libqmi to version 1.20.2 [Florin Sarbu]
* Update libmbim to version 1.16.2 [Florin Sarbu]
* kernel-modules-headers: Add basic sanity test [Zubair Lutfullah Kakakhel]
* Fix kernel module header generation [Zubair Lutfullah Kakakhel]
* image-resin.bbclass: Fix config.json pretty format [Andrei Gherzan]
* Allow supervisor update on unmanaged devices [Andrei Gherzan]
* Update resin-supervisor to v8.6.3 [Cameron Diver]
</details>

* Switch from resin-yocto-scripts to balena-yocto-scripts [Alexandru Costache]

# v2.27.0+rev2
## (2018-12-05)

* Updated firmware to v20180924 [Alexandru Costache]

# v2.27.0+rev1
## (2018-11-26)

* Update meta-resin from v2.26.0 to v2.27.0 [Florin Sarbu]

<details>
<summary> View details </summary>

## meta-resin-2.27.0
### (2018-11-23)

* Expose randomMacAddressScan config.json knob [Andrei Gherzan]
* Move modemmanager udev rules in /lib/udev/rules.d [Andrei Gherzan]
* Fix modemmanager bbappend files [Andrei Gherzan]
* dnsmasq: Define 8.8.8.8 as a fallback nameserver [Andrei Gherzan]
* Increase timeout for filesystem label [Vicentiu Galanopulo]
* Add support for Huawei ME936 modem in MBIM mode [Florin Sarbu]
* Backport systemd sd-shutdown improvements for sumo versions [Florin Sarbu]
* Include avahi d-bus introspection files in rootfs [Andrei Gherzan]
* Fix custom udev rules when rule is removed from config.json [Zubair Lutfullah Kakakhel]
* resin-mounts: Add NetworkManager conf.d bind mounts [Zubair Lutfullah Kakakhel]
* Add support to pass custom configuration to NetworkManager [Zubair Lutfullah Kakakhel]
* README.md: Add info about SSH and Avahi services [Andrei Gherzan]
* Avoid xtables lock in resin-proxy-config [Andrei Gherzan]
* Migrate the supervisor to balena repositories [Florin Sarbu]
* Update balena-supervisor to v8.3.5 [Cameron Diver]
* Update supported modems list [Florin Sarbu]

## meta-resin-2.26.0
### (2018-11-05)

* Rename resin-unique-key to balena-unique-key [Andrei Gherzan]
* Don't let resin-unique-key rewrite config.json [Andrei Gherzan]
</details>

# v2.26.0+rev4
## (2018-11-19)

* Set autoboot with no delay, with no check for abort [Florin Sarbu]

# v2.26.0+rev3
## (2018-11-15)

* Clean-up old bcm2708_wdog watchdog module [Florin Sarbu]

# v2.26.0+rev2
## (2018-11-07)

* Use new balena source repo for SRC_URI [Florin Sarbu]

# v2.26.0+rev1
## (2018-11-06)

* Update meta-resin from v2.25.0 to v2.26.0 [Florin Sarbu]

<details>
<summary> View details </summary>

## meta-resin-2.26.0
### (2018-11-05)

* Rename resin-unique-key to balena-unique-key [Andrei Gherzan]
* Don't let resin-unique-key rewrite config.json [Andrei Gherzan]

## meta-resin-2.25.0
### (2018-11-02)

* Generate ssh host key at first boot (not at first connection) [Andrei Gherzan]
* Fix extraneous space in kernel-resin.bbclass config [Florin Sarbu]
* Drop obsolete eval from kernel-resin's do_kernel_resin_reconfigure [Florin Sarbu]
* Add SyslogIdentifier for balena and resin-supervisor healthdog services [Matthew McGinn]
</details>

* Update the resin-yocto-scripts submodule to master HEAD [Florin Sarbu]

# v2.25.0+rev1
## (2018-11-05)

* Update meta-resin from v2.24.0 to v2.25.0 [Florin Sarbu]

<details>
<summary> View details </summary>

## meta-resin-2.25.0
### (2018-11-02)

* Generate ssh host key at first boot (not at first connection) [Andrei Gherzan]
* Fix extraneous space in kernel-resin.bbclass config [Florin Sarbu]
* Drop obsolete eval from kernel-resin's do_kernel_resin_reconfigure [Florin Sarbu]
* Add SyslogIdentifier for balena and resin-supervisor healthdog services [Matthew McGinn]

## meta-resin-2.24.1
### (2018-11-01)

* Update resin-supervisor to v8.0.0 [Pablo Carranza Velez]

## meta-resin-2.24.0
### (2018-10-24)

* resin-info: Small tweak for balenaCloud product [Andrei Gherzan]
* Update resin-supervisor to v7.25.8 [Pablo Carranza Velez]
* Rename resinOS to balenaOS [Andrei Gherzan]
</details>

# v2.24.0+rev1
## (2018-10-24)

* Update meta-resin submodule from v2.22.1 to v2.24.0 [Sebastian Panceac]

# v2.22.1+rev1
## (2018-10-20)

* Update meta-resin from v2.22.0 to v2.22.1 [Andrei Gherzan]

<details>
<summary> View details </summary>

## meta-resin-2.22.1
### (2018-10-20)

* Update resin-supervisor to v7.25.3

## meta-resin-2.22.0
### (2018-10-19)

* Update resin-supervisor to v7.25.2
* Include a CONTRIBUTING.md file
* Update to ModemManager v1.8.2
* Updates on contributing-device-support.md
</details>

* Disable rollbacks [Andrei Gherzan]

# v2.22.0+rev1
## (2018-10-19)

* Update meta-resin from v2.21.0 to v2.22.0 [Andrei Gherzan]

<details>
<summary> View details </summary>

## meta-resin-2.22.0
### (2018-10-19)

* Update resin-supervisor to v7.25.2
* Include a CONTRIBUTING.md file
* Update to ModemManager v1.8.2
* Updates on contributing-device-support.md

## meta-resin-2.21.0
### (2018-10-18)

* Improve systemd service ordering in rollbacks
* Update resin-supervisor to v7.24.1
</details>

# v2.21.0+rev1
## (2018-10-19)

* Update meta-resin from v2.19.0 to v2.21.0 [Florin Sarbu]

<details>
<summary> View details </summary>

## meta-resin-2.21.0
### (2018-10-18)

* Improve systemd service ordering in rollbacks
* Update resin-supervisor to v7.24.1

## meta-resin-2.20.0
### (2018-10-18)

* Avoid expander on flasher based on root kernel argument
* Resin-vars: Implement custom ssh keys service
* Fix redsocks interface creation when no proxy configured
* Replace NM's DHCP request option "Client indentifier" with udhcpc style option
* Fix for rollbacks in case of old balenaOS version
* Update resin-supervisor to v7.21.4
* Warn if rules are found in /etc/udev/rules.d
* Add support to load custom udev rules from config.json
* Aufs-util: Package auplink separately
* Enable kernel config dependencies for MBIM and QMI
* Set UPX to use LZMA compression by default
* Downgrade UPX to 3.94 for ARM
* Balena update for rollbacks. mobynit can now mount rootfs from sysroot.
* Fix proxy when using containers over bridge network
* Add support for aufs 4.9.9+, 4.9.94+, 4.18
* Add rollback-altboot service before balena service
* Add Automated Rollback recipe
* Add Automated Rollback support in u-boot env_resin.h
* Add a hook to support Automated Rollbacks
* Update HUP grub hook to support Automated Rollbacks
* Update HUP u-boot hook to support Automated Rollbacks
* Move kernel-image-initramfs from resin-image recipe to packagegroup-resin.inc
* Have 99-resin-grub hostapp-update-hook decide which grub to use

## meta-resin-2.19.0
### (2018-09-23)

* Update Balena to fix tty console hanging in some cases
* Pin down cargo deps (using Cargo.lock) to versions known working with rust 1.24.1 (for sumo)
* Remove duplicate packaging of bcm43143
* Set ModemManager to ignore Inca Roads Serial Device
* Add support for aufs 4.14.56+
* Update resin-supervisor to v7.19.7
</details>

* Disable u-boot autoboot delay option and enable CTRL^C autoboot stop feature [Florin Sarbu]

# v2.19.0+rev3
## (2018-10-19)

* Add hook to remove kernel from boot parition after a HUP [Zubair Lutfullah Kakakhel]
* Add Automated Rollback support [Zubair Lutfullah Kakakhel]
* Remove the kernel from the boot partition [Zubair Lutfullah Kakakhel]
* Load the kernel from the rootfs [Zubair Lutfullah Kakakhel]

# v2.19.0+rev2
## (2018-10-11)

* Move udev rules from /etc to /lib [Zubair Lutfullah Kakakhel]

# v2.19.0+rev1
## (2018-10-01)

* Update meta-resin from v2.15.1 to v2.19.0 [Florin Sarbu]

<details>
<summary> View details </summary>

## meta-resin-2.19.0
### (2018-09-23)

* Update Balena to fix tty console hanging in some cases
* Pin down cargo deps (using Cargo.lock) to versions known working with rust 1.24.1 (for sumo)
* Remove duplicate packaging of bcm43143
* Set ModemManager to ignore Inca Roads Serial Device
* Add support for aufs 4.14.56+
* Update resin-supervisor to v7.19.7

## meta-resin-2.18.1
### (2018-09-14)

* Add a parsable representation of the changelog

## meta-resin-v2.18.0
### (2018-09-12)

* Update grub hooks to prepare to load kernel from root [Zubair Lutfullah Kakakhel]
* Update resin-supervisor to v7.19.4 [Cameron Diver]
* Kernel-resin.bbclass: Enable CONFIG_IP_NF_TARGET_LOG as a module [John (Jack) Brown]
* Balena: Update to current HEAD of 17.12-resin [Andrei Gherzan]
* Compress os-config with UPX on arm64 too [Andrei Gherzan]
* Update upx to 3.95 [Andrei Gherzan]
* Add support to skip flasher detection in env_resin.h [Zubair Lutfullah Kakakhel]
* Add the kernel to the rootfs [Zubair Lutfullah Kakakhel]
* Rework resin-supervisor systemd dependency on balena [Florin Sarbu]
* Enhanced security options for dropbear - sumo [Andrei Gherzan]
* Enhanced security options for dropbear - rocko [Andrei Gherzan]
* Enhanced security options for dropbear - pyro [Andrei Gherzan]
* Enhanced security options for dropbear - morty [Andrei Gherzan]
* Enhanced security options for dropbear - krogoth [Andrei Gherzan]

## meta-resin-2.17.0
### (2018-09-03)

* Resin-proxy-config: The no_proxy file fails to parse when missing EOL [Rich Bayliss]

## meta-resin-2.16.0
### (2018-08-31)

* Os-config: UPX is broken on aarch64 [Theodor Gherzan]
* Allow flasher types to pin preloaded devices [Theodor Gherzan]
* Disable PIE for go [Zubair Lutfullah Kakakhel]
* Disable PIE for balena [Zubair Lutfullah Kakakhel]
</details>

* Change u-boot's CONFIG_AUTOBOOT_DELAY_STR to 'pause' [Florin Sarbu]

# v2.15.1+rev3
## (2018-09-14)

* Add repo and changelog yml files [Giovanni Garufi]

# v2.15.1+rev2
## (2018-09-08)

* Set Huawei 12d1:1506 modems back to NCM mode [Florin Sarbu]

# v2.15.1+rev1
## (2018-08-30)

* Update the meta-resin submodule to version v2.15.1 [Florin Sarbu]

# v2.14.3+rev5
## (2018-08-28)

* Backport "media: uvcvideo: Fix driver reference counting" patch [Florin Sarbu]

# v2.14.3+rev4
## (2018-08-27)

* Switch the Balena Fin wifi and bluetooth driver to the proprietary one [Florin Sarbu]

# v2.14.3+rev3
## (2018-08-27)

* Enable kernel I2C and GPIO support for Kontron PLD devices [Florin Sarbu]

# v2.14.3+rev2
## (2018-08-26)

* Add versionist support [Florin Sarbu]

* Use the DTB loaded by the pi firmware in u-boot [ZubairLK]

# v2.14.3+rev1
## (2018-08-14)

* Update the meta-resin submodule to version v2.14.3 [Florin]
* Add u-boot v2018.07 recipe and use that [ZubairLK]

# v2.14.1+rev1
## (2018-08-03)

* Update the meta-resin submodule to version v2.14.1 [Florin]
* Fix qmi_wwan patch name in linux-raspberrypi [Andrei]
* Add u-boot in the bootchain [ZubairLK]
* Update the resin-yocto-scripts submodule to 8312741e13604a9d166370349061876afb22c0fa (on master branch) [Florin]
* Backport kernel qmi fix for supporting SIMCOM SIM7600E-H modem [Florin]

# v2.14.0+rev1
## (2018-07-18)

* Update the meta-resin submodule to version v2.14.0 [Florin]

# v2.13.6+rev1
## (2018-07-13)

* Update the meta-resin submodule to version v2.13.6 [Florin]

# v2.13.5+rev1
## (2018-07-09)

* Update the meta-resin submodule to version v2.13.5 [Florin]
* Update the resin-yocto-scripts submodule to 59ccd8558435ff6424827fb36ccb43b14650f4d4 (on master branch) [Florin]

# v2.13.3+rev1
## (2018-07-05)

* Update the meta-resin submodule to version v2.13.3 [Florin]

# v2.13.2+rev1
## (2018-06-28)

* Update the meta-resin submodule to version v2.13.2 [Florin]
* Update the resin-yocto-scripts submodule to 6eddcc9a637e00dbca94815f9af0f2b7bf61eb88 (on master branch) [Florin]
* Disable WiFi power saving mode on the Balena Fin board [Florin]
* Fix bluetooth on rpi zero wireless [Florin]
* modemmanager: fix support for Huawei MS2372 modem [Sebastian]

# v2.13.1+rev1
## (2018-06-18)

* Update the meta-resin submodule to version v2.13.1 [Florin]
* Update to yocto sumo and matching dependencies [Andrei]

# v2.13.0+rev1
## (2018-06-11)

* Update the meta-resin submodule to version v2.13.0 [Florin]
* Remove subtype_of from fincm3.coffee [Florin]
* Cleanup bcm2835-bootfiles and fix fincm3 build [Andrei]
* Update fincm3 icon [Andrei]
* Update the BSP to include the latest changes in rocko branch (fixes MAC address for ethernet on RaspberryPi 3B+ [Andrei]
* Remove superfluous wait instruction from the fincm3.coffee file [Florin]

# v2.12.7+rev1
## (2018-05-04)

* Update the meta-resin submodule to version v2.12.7 [Andrei]
* Add Balena Fin device type and support [Andrei]
* Backport Balena Fin overlay patch which adds the correct overlay source [Florin]

# v2.12.6+rev1
## (2018-04-30)

* Update the meta-resin submodule to version v2.12.6 [Florin]
* Update the resin-yocto-scripts submodule to f7718efbbf53369aaacb7eb54e707ee8a5d4fc4b (on master branch) [Florin]
* Modify the 99-rpi-bootloader hostapp hook use filesystem label instead of physical partition number [TheOnlyZby]
* Use filesystem label instead of physical partition number for the kernel cmdline root parameter [TheOnlyZby]
* Include balena fin dtbo in OS [Andrei]
* Update warning in the dashboard regarding the RPi3 wifi connectivity [Gergely]

# v2.12.5+rev2
## (2018-04-03)

* Add udev rule and systemd service to switch U-Blox modem from RNDIS to ECM mode [Sebastian]

# v2.12.5+rev1
## (2018-03-27)

* Update the meta-resin submodule to version v2.12.5 [Florin]
* Add boot firmware and WiFi firmware for Raspberry Pi 3 B+ [Florin]
* Update the resin-yocto-scripts submodule to 9cecb1ca4d9d4713dd337148b7d04a17afdba772 (on master branch) [Florin]

# v2.12.3+rev1
## (2018-03-15)

* Update the meta-resin submodule to version v2.12.3 [Florin]

# v2.12.2+rev1
## (2018-03-14)

* Update the meta-resin submodule to version v2.12.2 [Florin]

# v2.12.1+rev1
## (2018-03-12)

* Update the meta-resin submodule to version v2.12.1 [Andrei]

# v2.12.0+rev1
## (2018-03-09)

* Update the meta-resin submodule to version v2.12.0 [Theodor]

# v2.11.2+rev1
## (2018-03-08)

* Update the meta-resin submodule to version v2.11.2 [Andrei]

# v2.11.1+rev1
## (2018-03-08)

* Update the meta-resin submodule to version v2.11.1 [Andrei]

# v2.11.0+rev1
## (2018-03-08)

* Update the meta-resin submodule to version v2.11.0 [Theodor]

# v2.10.1+rev1
## (2018-02-28)

* Update the meta-resin submodule to version v2.10.1 [Florin]
* Update the resin-yocto-scripts submodule to dc9dfe466e48d934e55fb20a05156886873b1ab1 (on master branch) [Florin]

# v2.10.0+rev1
## (2018-02-27)

* Update the meta-resin submodule to version v2.10.0 [Andrei]
* Update to rocko [Andrei]

# v2.9.7+rev1
## (2018-02-07)

* Update the meta-resin submodule to version v2.9.7 [Florin]
* Update the resin-yocto-scripts submodule to d209b8c9c797ebd52a0f5ce404ea2420c248724c (on master branch) [Florin]
* Revert patch which disables memory cgroup controller by default [Andrei]

# v2.9.6+rev1
## (2018-01-13)

* Update the meta-resin submodule to version v2.9.6 [Florin]

# v2.9.5+rev1
## (2018-01-11)

* Update the meta-resin submodule to version v2.9.5 [Florin]
* Blacklist the upstream rtl8192cu wifi driver in favour of the out of tree 8192cu wifi driver [Florin]

# v2.9.4+rev1
## (2018-01-10)

* Update the meta-resin submodule to version v2.9.4 [Florin]

# v2.9.3+rev1
## (2018-01-10)

* Update the meta-resin submodule to version v2.9.3 [Florin]
* Update the resin-yocto-scripts submodule to 6f7a9ab326bb822196e3e48b08ef1d73d08caec6 (on master branch) [Florin]
* Make bluetooth be enabled by default in the host OS [Florin]
* Add the latest SD8887 Marvel Wi-Fi firmware from linux-firmware git into image [Sebastian]

# v2.9.1+rev1
## (2017-12-12)

* Update the meta-resin submodule to version v2.9.1 [Florin]
* Make the 99-rpi-bootloader hostapp hook detect where it is run from [Florin]
* Bump kernel to version 4.9.59 [Florin]

# v2.7.8+rev1
## (2017-11-17)

* Update the meta-resin submodule to version v2.7.8 [Florin]
* Increase initramfs maximum size to 12 MB (12288 KB) [Florin]

# v2.7.5+rev2
## (2017-11-04)

* Update the resin-yocto-scripts submodule to c4db082fd2d5a3b4857035264c1e726962d7b826 (on master branch) [Florin]
* Default to compressed kernel image [Andrei]

# v2.7.5+rev1
## (2017-11-01)

* Update the meta-resin submodule to version v2.7.5 [Florin]
* Exclude from resinOS the debug versions of boot firmware [Florin]
* Fix obsolete reference to older debug-image [Florin]
* Fix typo in enabling support for PCA955 GPIO expander [Florin]

# v2.7.4+rev1
## (2017-10-25)

* Update the meta-resin submodule to version v2.7.4 [Florin]
* Update the meta-raspberrypi BSP layer to revision 40447de4782d76f1e23e67ba05e272c27f6ec250 (pyro branch) [Florin]
* Enable PCA955x IO expander in kernel config [Florin]
* Update the resin-yocto-scripts submodule to e3a06d48a2f8b7e32d3047c33066a5b896e6ae93 [Florin]
* Update layers to Yocto Pyro [Will]
* Update meta-openembedded to latest morty branch [Will]
* Update poky to latest morty branch [Will]

# v2.7.2+rev1
## (2017-10-08)

* Update the meta-resin submodule to version v2.7.2 [Florin]
* Update the resin-yocto-scripts submodule to HEAD of master [Florin]
* Enabled always overcommit VM mode [Yossi]
* Add meta-rust submodule [Will]
* Update resin-yocto-scripts to include deployment of docker images [Andrei]

# v2.6.0+rev1
## (2017-09-20)

* Update the meta-resin submodule to version v2.6.0 [Andrei]
* Integrate with hostapps [Andrei]
* Update the resin-yocto-scripts again to fix Pyro build [Will]
* Update the resin-yocto-scripts to fix Pyro build [Will]
* Update the resin-yocto-scripts submodule to HEAD of master [Will]

# v2.3.0+rev1
## (2017-08-17)

* Update the meta-resin submodule to version v2.3.0 [Florin]

# v2.2.0+rev1
## (2017-07-30)

* Update the meta-resin submodule to version v2.2.0 [Florin]
* Update the resin-yocto-scripts submodule to HEAD of master [Florin]

# v2.1.0+rev1
## (2017-07-20)

* Update the meta-resin submodule to version v2.1.0 [Michal]
* Update the resin-yocto-scripts submodule to HEAD of master [Michal]
* Add WiFi 5GHz connectivity warning for RPi 3 & Zero W [Thodoris]

# v2.0.8+rev1
## (2017-07-04)

* Update the meta-resin submodule to version v2.0.8 [Florin]
* Update the resin-yocto-scripts submodule to HEAD of master [Florin]

# v2.0.7+rev1
## (2017-06-29)

* Update the meta-resin submodule to version v2.0.7 [Florin]
* Update the getting started links in the .coffee files [Florin]
* Update the resin-yocto-scripts submodule to HEAD of master [Florin]
* Add support for bluetooth on the Raspberry Pi Zero WiFi [Michal]

# v2.0.6+rev1
## (2017-06-06)

* Update the meta-resin submodule to version v2.0.6 [Andrei]

# v2.0.5+rev1
## (2017-06-05)

* Update the meta-resin submodule to version v2.0.5 [Florin]
* Update the resin-yocto-scripts submodule to HEAD of master [Florin]
* Update the resin-yocto-scripts submodule [Florin]
* Update resin-yocto-scripts to master [Will]

# v2.0.3+rev1
## (2017-05-12)

* Update the meta-resin submodule to version v2.0.3 [Florin]

# v2.0.2+rev2
## (2017-05-01)

* Bump resin-yocto-scripts to fix Jenkins deployment [Andrei]

# v2.0.2+rev1
## (2017-04-24)

* Use aliases for serial devices [Andrei]
* Add support for Raspberry Pi Zero WiFi [Andrei]
* Add support for 64bit Raspberry Pi 3 [Andrei]
* Update the meta-resin submodule to version v2.0.2 [Andrei]

# v2.0.0+rev3
## (2017-04-13)

* Bump resin-yocto-scripts to include deployment routine [Andrei]

# v2.0.0+rev2
## (2017-04-04)

* Bump resin-yocto-scripts to fix resinOS docker registry push [Andrei]

# v2.0.0+rev1
## (2017-04-03)

* Fix OS version to be semver compliant [Andrei]

# v2.0.0.rev1
## (2017-04-01)

* Update the meta-resin submodule to version v2.0.0 [Andrei]

# v2.0.0-rc6.rev1
## (2017-03-31)

* Update the meta-resin submodule to version v2.0.0-rc6 [Andrei]
* Enable audio by default [Andrei]

# v2.0.0-rc5.rev1
## (2017-03-26)

* Re-add console=null for production builds [Florin]
* Update meta-resin to v2.0.0-rc5 [Florin]
* Avoid cursor on virtual terminal in production [Andrei]
* Enable AutoHAT tests through Jenkins [Praneeth]

# v2.0.0-rc4.rev1
## (2017-03-20)

* Update meta-resin to v2.0.0-rc4 [Andrei]

# v2.0.0-rc3.rev1
## (2017-03-14)

* Update meta-resin submodule to version v2.0.0-rc3 [Florin]

# v2.0.0-rc1.rev2
## (2017-03-10)

* Temporary fix for boot fail on production images [Andrei]

# v2.0.0-rc1.rev1
## (2017-03-10)

* Fix dtb deployment when using initramfs [Andrei]
* Load the i2c-dev kernel module at startup [Michal]

# v2.0.0-beta13.rev3
## (2017-03-03)

* Deploy all available overlay dt files for Raspberry Pi [Michal]

# v2.0.0-beta13.rev2
## (2017-03-01)

* Include linux-firmware-bcm43430 for all RaspberryPi boards [Andrei]

# v2.0.0-beta13.rev1
## (2017-02-28)

* Update to Morty [Michal]

# v2.0.0-beta12.rev1
## (2017-02-27)

* Bump resin-yocto-scripts to current HEAD [Andrei]
* Update meta-resin to v2.0.0-beta.12 [Andrei]
* Don't load audio module (snd_bcm2835) automatically [Andrei]

# v2.0.0-beta11.rev1
## (2017-02-15)

* Update meta-resin to v2.0.0-beta.11 [Andrei]

# v2.0.0-beta10.rev1
## (2017-02-14)

* Update meta-resin to v2.0.0-beta.10 [Andrei]

# v2.0.0-beta.9
## (2017-02-08)

* Update meta-resin to v2.0-beta.9 [Andrei]

# v2.0.0-beta.8
## (2017-01-29)

* Update meta-resin to v2.0-beta.8 [Andrei]
* Update resin-yocto-scripts to HEAD of the master branch [Florin]
* Update the bootloader to the latest version, this adds support for rpi2 rev1.2 [Michal]

# v2.0.0-beta.7
## (2016-12-05)

* Update meta-resin to v2.0-beta.7 [Florin]

# v2.0.0-beta.6
## (2016-12-05)

* Update meta-resin to v2.0-beta.6 [Andrei]

# v2.0.0-beta.5
## (2016-11-30)

* Update meta-resin to v2.0-beta.5 [Andrei]
* Autoload the rpi watchdog kernel module (bcm2708_wdog) [Florin]

# v2.0.0-beta.3
## (2016-11-07)

* Update meta-resin to v2.0-beta.3 [Andrei]
* Cleanup docker-resin-supervisor-disk of unneeded variables [Andrei]
* Update resin-yocto-scripts to fix logging in container builds

# v2.0.0-beta.2
## (2016-11-01)

* Update meta-resin to v2.0-beta.2 [Florin]
* Don't compress kernel modules [Michal]

# v2.0.0-beta.1
## (2016-10-11)

* Update meta-resin to v2.0-beta.1 [Andrei]
* Add meta-filesystem as we need aufs-utils [Andrei]
* Add build support for resinos [Andrei]
* Update resin-yocto-script to include changes in our image types [Theodor]
* Replace the concept of a debug image with a development image [Theodor]
* Update meta-resin to include avahi [Florin]
* Update resin-yocto-scripts to include kernel headers handling as gzip [Florin]

# v1.16.1
## (2016-10-01)

* Update meta-resin to include supervisor v2.5.0 [Pablo]

# v1.16.0
## (2016-09-27)

* Update meta-resin to v1.16 [Florin]

# v1.15.0
## (2016-09-24)

* Update meta-resin to v1.15 [Florin]

# v1.14.0
## (2016-09-23)

* Update meta-resin to v1.14 [Florin]

# v1.13.0
## (2016-09-23)

* Update meta-resin to v1.13 [Florin]

# v1.12.0
## (2016-09-21)

* Update meta-resin to v1.12 [Florin]
* Update resin-yocto-scripts to include resinhup upload to dockerhub [Florin]
* Update meta-resin [Florin]
* Change .coffee to announce partition 1 now holds config.json and also introduce versioning (v1) [Florin]

# v1.11.0
## (2016-08-31)

* Update meta-resin to v1.11 [Florin]

# v1.10.0
## (2016-08-24)

* Update meta-resin to v1.10 [Florin]

# v1.9.0
## (2016-08-24)

* Update meta-resin to v1.9 [Florin]
* Update resin-yocto-scripts for including kernel modules headers deploy [Florin]
* Update yocto-resin-scripts for host nodejs detection improvements [Florin]

# v1.8.0
## (2016-08-02)

* Bump meta-resin to v1.8 [Andrei]
* Disable firmware splash and firmware related warnings [Theodor]
* Fix kernel log messages over HDMI (i.e. device connected to tty1) [Theodor]
* Bump resin-device-types to include partial manifest support [Andrei]
* No more debug images in staging

# v1.7.0
## (2016-07-14)

* Update meta-resin to v1.7

# v1.6.0
## (2016-07-06)

* Update meta-resin to v1.6 [Florin]

# v1.5.0
## (2016-07-04)

* Update meta-resin to v1.5 [Florin]

# v1.5.0rc4
## (2016-06-29)

* Update meta-resin to include supervisor update to v1.11.6 [Florin]

# v1.5.0rc3
## (2016-06-29)

* Update meta-resin to include openvpn-resin.service refactoring [Florin]

# v1.5.0rc2
## (2016-06-28)

* Update meta-resin to include docker key.json fix [Florin]
* Update meta-resin to include flasher fixes [Florin]

# v1.4.0
## (2016-06-27)

* Update meta-resin to v1.4 [Florin]
* Update meta-resin to allow let error out [Florin]
* Update meta-resin to allow patching of kernel-modules-headers [Florin]
* Bump meta-resin to fix various issues [Andrei]
* Fix a small syntax error in meta-resin [Andrei]
* Fix automation fix for debug image [Andrei]
* Replace RESIN_STAGING_BUILD by DEBUG_IMAGE [Andrei]

# v1.3.0
## (2016-06-24)

* Update meta-resin to v1.3 [Florin]
* Update meta-resin to include kernel modules compress support [Andrei]
* Compress kernel modules [Andrei]
* Replace SUPERVISOR_TAG by TARGET_TAG [Andrei]
* Custom docker images in connectable builds [Andrei]
* Bump meta-resin to include connectable builds [Andrei]
* Remove RPI_FIX_VCHIQ workaround as fix is included in our base images [Andrei]
* Add support for optional supervisor image [Andrei]

# v1.2.1
## (2016-06-18)

# v1.2.0
## (2016-06-10)

* Mask brcm43438.service [Florin]
* Update meta-resin to v1.2 [Andrei]
* Bump meta-resin to HEAD [Andrei]
* Bump yocto-resin-scripts to bring in improvements for in-docker builds [Andrei]
* Configure builds with RM_OLD_IMAGE [Theodor]
* Bump meta-raspberypi to include bluetooth support for raspberypi3 [Andrei]
* Bump meta-resin to include switch from rce to docker [Andrei]
* Update meta-raspberrypi BSP layer to pick up changes and set console=tty1 in production [Andrei]

# v1.1.4
## (2016-04-16)

* Be able to workaround the issues with egl apps in containers using RPI_FIX_VCHIQ [Andrei]

# v1.1.1
## (2016-03-16)

* Add support for Raspberrypi 3 [Theodor]
* Change revision of meta-raspberrypi to the current HEAD of the jethro branch [Theodor]
* Transition from fido -> jethro [Theodor]
