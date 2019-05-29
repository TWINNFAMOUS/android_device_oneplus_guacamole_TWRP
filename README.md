# Device Tree for OnePlus 7 Pro (guacamole)

The OnePlus 7 Pro (codenamed _"guacamole"_) is a flagship smartphone from OnePlus.
It was released in May 2019.
# device info
#cat /proc/partitions
major minor  #blocks  name

   1        0       8192 ram0
   1        1       8192 ram1
   1        2       8192 ram2
   1        3       8192 ram3
   1        4       8192 ram4
   1        5       8192 ram5
   1        6       8192 ram6
   1        7       8192 ram7
   1        8       8192 ram8
   1        9       8192 ram9
   1       10       8192 ram10
   1       11       8192 ram11
   1       12       8192 ram12
   1       13       8192 ram13
   1       14       8192 ram14
   1       15       8192 ram15
 254        0    2150400 zram0
   8       48      32768 sdd
   8       49        104 sdd1
   8       50        128 sdd2
   8       51       1024 sdd3
   8       52       1024 sdd4
   8        0  245637120 sda
   8        1          8 sda1
   8        2      32768 sda2
   8        3       1024 sda3
   8        4       1024 sda4
   8        5        512 sda5
   8        6        512 sda6
   8        7     262144 sda7
   8        8      10240 sda8
   8        9      10240 sda9
   8       10       1024 sda10
   8       11       1024 sda11
   8       12        512 sda12
   8       13    3555328 sda13
   8       14    3555328 sda14
   8       15     102400 sda15
 259        0     102400 sda16
 259        1      16384 sda17
 259        2     131072 sda18
 259        3  237853132 sda19
   8       32       8192 sdc
   8       33       3584 sdc1
   8       34        128 sdc2
   8       64    4194304 sde
   8       65        512 sde1
   8       66       4096 sde2
   8       67       8192 sde3
   8       68     307200 sde4
   8       69       1024 sde5
   8       70       4096 sde6
   8       71      32768 sde7
   8       72       8192 sde8
   8       73      65536 sde9
   8       74        512 sde10
   8       75      98304 sde11
   8       76        512 sde12
   8       77        512 sde13
   8       78        128 sde14
   8       79         80 sde15
 259        4    1048576 sde16
 259        5         64 sde17
 259        6      24576 sde18
 259        7       2048 sde19
 259        8       2048 sde20
 259        9     174080 sde21
 259       10      16384 sde22
 259       11       2048 sde23
 259       12       2048 sde24
 259       13       2048 sde25
 259       14       2048 sde26
 259       15       2048 sde27
 259       16         32 sde28
 259       17        512 sde29
 259       18       4096 sde30
 259       19       8192 sde31
 259       20     307200 sde32
 259       21       1024 sde33
 259       22       4096 sde34
 259       23      32768 sde35
 259       24       8192 sde36
 259       25      65536 sde37
 259       26        512 sde38
 259       27      98304 sde39
 259       28        512 sde40
 259       29        512 sde41
 259       30        128 sde42
 259       31         80 sde43
 259       32    1048576 sde44
 259       33         64 sde45
 259       34      24576 sde46
 259       35       2048 sde47
 259       36       2048 sde48
 259       37      16384 sde49
 259       38       2048 sde50
 259       39       2048 sde51
 259       40       2048 sde52
 259       41       2048 sde53
 259       42       2048 sde54
 259       43         32 sde55
 259       44      65536 sde56
 259       45      32768 sde57
 259       46     307200 sde58
 259       47          4 sde59
 259       48       1024 sde60
 259       49        256 sde61
 259       50        256 sde62
 259       51       8192 sde63
 259       52      33424 sde64
 259       53          4 sde65
 259       54       1024 sde66
 259       55       8192 sde67
 259       56       2048 sde68
 259       57      65536 sde69
 259       58        128 sde70
 259       59        512 sde71
 259       60         28 sde72
 259       61        512 sde73
 259       62       1024 sde74
 259       63       8096 sde75
 259       64      16192 sde76
 259       65      16192 sde77
 259       66      16192 sde78
 259       67       1024 sde79
 259       68        128 sde80
   8       80      32768 sdf
   8       81        104 sdf1
   8       82       2048 sdf2
   8       83       2048 sdf3
   8       84       2048 sdf4
   8       85        128 sdf5
   8       86       1024 sdf6
   8       87       1024 sdf7
   8       88       1024 sdf8
   8       89          4 sdf9
   8       16       8192 sdb
   8       17       3584 sdb1
   8       18        128 sdb2
 252        0    1031948 dm-0
 252        1  237853132 dm-1


# cat /proc/filesystems
nodev	sysfs
nodev	rootfs
nodev	ramfs
nodev	bdev
nodev	proc
nodev	cpuset
nodev	cgroup
nodev	cgroup2
nodev	tmpfs
nodev	configfs
nodev	debugfs
nodev	tracefs
nodev	sockfs
nodev	dax
nodev	bpf
nodev	pipefs
nodev	devpts
	ext3
	ext2
	ext4
	vfat
	msdos
nodev	ecryptfs
nodev	sdcardfs
	ntfs
	fuseblk
nodev	fuse
nodev	fusectl
	f2fs
nodev	pstore
	exfat
nodev	selinuxfs
nodev	functionfs
OnePlus7ProTMO:/ $ cd dev/block/platform/soc/1d84000.ufshc/by-name
OnePlus7ProTMO:/dev/block/platform/soc/1d84000.ufshc/by-name $ ls -al
total 0
drwxr-xr-x 2 root root 2360 1970-01-02 10:47 .
drwxr-xr-x 3 root root 2500 1970-01-02 10:47 ..
lrwxrwxrwx 1 root root   15 1970-01-02 10:47 ALIGN_TO_128K_1 -> /dev/block/sdd1
lrwxrwxrwx 1 root root   15 1970-01-02 10:47 ALIGN_TO_128K_2 -> /dev/block/sdf1
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 LOGO_a -> /dev/block/sde22
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 LOGO_b -> /dev/block/sde49
lrwxrwxrwx 1 root root   15 1970-01-02 10:47 abl_a -> /dev/block/sde8
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 abl_b -> /dev/block/sde36
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 aging -> /dev/block/sde56
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 aging_mod -> /dev/block/sde57
lrwxrwxrwx 1 root root   15 1970-01-02 10:47 aop_a -> /dev/block/sde1
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 aop_b -> /dev/block/sde29
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 apdp -> /dev/block/sde61
lrwxrwxrwx 1 root root   15 1970-01-02 10:47 bluetooth_a -> /dev/block/sde5
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 bluetooth_b -> /dev/block/sde33
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 boot_a -> /dev/block/sde11
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 boot_b -> /dev/block/sde39
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 catecontentfv -> /dev/block/sde74
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 catefv -> /dev/block/sde73
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 cateloader -> /dev/block/sde68
lrwxrwxrwx 1 root root   15 1970-01-02 10:47 cdt -> /dev/block/sdd2
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 cmnlib64_a -> /dev/block/sde13
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 cmnlib64_b -> /dev/block/sde41
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 cmnlib_a -> /dev/block/sde12
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 cmnlib_b -> /dev/block/sde40
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 config -> /dev/block/sda12
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 core_nhlos_a -> /dev/block/sde21
lrwxrwxrwx 1 root root   15 1970-01-02 10:47 ddr -> /dev/block/sdd3
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 devcfg_a -> /dev/block/sde14
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 devcfg_b -> /dev/block/sde42
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 devinfo -> /dev/block/sde59
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 dip -> /dev/block/sde60
lrwxrwxrwx 1 root root   15 1970-01-02 10:47 dsp_a -> /dev/block/sde9
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 dsp_b -> /dev/block/sde37
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 dtbo_a -> /dev/block/sde18
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 dtbo_b -> /dev/block/sde46
lrwxrwxrwx 1 root root   15 1970-01-02 10:47 frp -> /dev/block/sda6
lrwxrwxrwx 1 root root   15 1970-01-02 10:47 fsc -> /dev/block/sdf5
lrwxrwxrwx 1 root root   15 1970-01-02 10:47 fsg -> /dev/block/sdf4
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 fw_ufs1_a -> /dev/block/sde23
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 fw_ufs1_b -> /dev/block/sde50
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 fw_ufs2_a -> /dev/block/sde24
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 fw_ufs2_b -> /dev/block/sde51
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 fw_ufs3_a -> /dev/block/sde25
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 fw_ufs3_b -> /dev/block/sde52
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 fw_ufs4_a -> /dev/block/sde26
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 fw_ufs4_b -> /dev/block/sde53
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 fw_ufs5_a -> /dev/block/sde27
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 fw_ufs5_b -> /dev/block/sde54
lrwxrwxrwx 1 root root   15 1970-01-02 10:47 hyp_a -> /dev/block/sde3
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 hyp_b -> /dev/block/sde31
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 imagefv_a -> /dev/block/sde20
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 imagefv_b -> /dev/block/sde48
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 keymaster_a -> /dev/block/sde10
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 keymaster_b -> /dev/block/sde38
lrwxrwxrwx 1 root root   15 1970-01-02 10:47 keystore -> /dev/block/sda5
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 limits -> /dev/block/sde65
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 logdump -> /dev/block/sde69
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 logfs -> /dev/block/sde67
lrwxrwxrwx 1 root root   15 1970-01-02 10:47 mdm1m9kefs1 -> /dev/block/sdf7
lrwxrwxrwx 1 root root   15 1970-01-02 10:47 mdm1m9kefs2 -> /dev/block/sdf8
lrwxrwxrwx 1 root root   15 1970-01-02 10:47 mdm1m9kefs3 -> /dev/block/sdf6
lrwxrwxrwx 1 root root   15 1970-01-02 10:47 mdm1m9kefsc -> /dev/block/sdf9
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 mdm1oemnvbktmp -> /dev/block/sde79
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 mdm_oem_dycnvbk -> /dev/block/sda10
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 mdm_oem_stanvbk -> /dev/block/sda11
lrwxrwxrwx 1 root root   15 1970-01-02 10:47 mdmddr -> /dev/block/sdd4
lrwxrwxrwx 1 root root   15 1970-01-02 10:47 mdtp_a -> /dev/block/sde7
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 mdtp_b -> /dev/block/sde35
lrwxrwxrwx 1 root root   15 1970-01-02 10:47 mdtpsecapp_a -> /dev/block/sde6
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 mdtpsecapp_b -> /dev/block/sde34
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 metadata -> /dev/block/sda17
lrwxrwxrwx 1 root root   15 1970-01-02 10:47 misc -> /dev/block/sda3
lrwxrwxrwx 1 root root   15 1970-01-02 10:47 modem_a -> /dev/block/sde4
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 modem_b -> /dev/block/sde32
lrwxrwxrwx 1 root root   15 1970-01-02 10:47 modemst1 -> /dev/block/sdf2
lrwxrwxrwx 1 root root   15 1970-01-02 10:47 modemst2 -> /dev/block/sdf3
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 msadp -> /dev/block/sde62
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 multiimgoem_a -> /dev/block/sde28
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 multiimgoem_b -> /dev/block/sde55
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 odm_a -> /dev/block/sda15
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 odm_b -> /dev/block/sda16
lrwxrwxrwx 1 root root   15 1970-01-02 10:47 oem_dycnvbk -> /dev/block/sda8
lrwxrwxrwx 1 root root   15 1970-01-02 10:47 oem_stanvbk -> /dev/block/sda9
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 op1 -> /dev/block/sde58
lrwxrwxrwx 1 root root   15 1970-01-02 10:47 op2 -> /dev/block/sda7
lrwxrwxrwx 1 root root   15 1970-01-02 10:47 param -> /dev/block/sda4
lrwxrwxrwx 1 root root   15 1970-01-02 10:47 persist -> /dev/block/sda2
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 qupfw_a -> /dev/block/sde15
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 qupfw_b -> /dev/block/sde43
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 rawdump -> /dev/block/sda18
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 reserve1 -> /dev/block/sde75
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 reserve2 -> /dev/block/sde76
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 reserve3 -> /dev/block/sde77
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 reserve4 -> /dev/block/sde78
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 secdata -> /dev/block/sde72
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 splash -> /dev/block/sde64
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 spunvm -> /dev/block/sde63
lrwxrwxrwx 1 root root   15 1970-01-02 10:47 ssd -> /dev/block/sda1
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 storsec_a -> /dev/block/sde70
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 storsec_b -> /dev/block/sde80
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 system_a -> /dev/block/sda13
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 system_b -> /dev/block/sda14
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 toolsfv -> /dev/block/sde66
lrwxrwxrwx 1 root root   15 1970-01-02 10:47 tz_a -> /dev/block/sde2
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 tz_b -> /dev/block/sde30
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 uefisecapp_a -> /dev/block/sde19
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 uefisecapp_b -> /dev/block/sde47
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 uefivarstore -> /dev/block/sde71
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 userdata -> /dev/block/sda19
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 vbmeta_a -> /dev/block/sde17
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 vbmeta_b -> /dev/block/sde45
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 vendor_a -> /dev/block/sde16
lrwxrwxrwx 1 root root   16 1970-01-02 10:47 vendor_b -> /dev/block/sde44
lrwxrwxrwx 1 root root   15 1970-01-02 10:47 xbl_a -> /dev/block/sdb1
lrwxrwxrwx 1 root root   15 1970-01-02 10:47 xbl_b -> /dev/block/sdc1
lrwxrwxrwx 1 root root   15 1970-01-02 10:47 xbl_config_a -> /dev/block/sdb2
lrwxrwxrwx 1 root root   15 1970-01-02 10:47 xbl_config_b -> /dev/block/sdc2


## Compile

First download omni-9.0 tree:

```
repo init --depth=1 -u https://github.com/omnirom/android.git -b android-9.0
```
Then add these string to .repo/manifests/remove.xml

```
<remove-project name="platform/bootable/recovery" />
```

Then add these projects to .repo/local_manifests/roomservice.xml (If you don't have it, you can add them to .repo/manifest.xml): 

```xml
<project name="mauronofrio/android_device_oneplus_guacamole_TWRP" path="device/oneplus/guacamole" remote="github" revision="android-9.0" />
<project name="mauronofrio/android_bootable_recovery" path="bootable/recovery" remote="github" revision="android-9.0" />
<project name="android_external_busybox" path="external/busybox" remote="TeamWin" revision="android-9.0" />
```

Now you can sync your source:

```
repo sync
```

To auotomatic make the twrp installer, you need to import this commit in the build path: https://gerrit.omnirom.org/#/c/android_build/+/33182/


To make all works you need to modify the buildinfo.sh in build/tools
echo "ro.build.version.release=$PLATFORM_VERSION"
echo "ro.build.version.security_patch=$PLATFORM_SECURITY_PATCH"
to
echo "ro.build.version.release_orig=$PLATFORM_VERSION"
echo "ro.build.version.security_patch_orig=$PLATFORM_SECURITY_PATCH"

And you need to increase the PLATFORM_VERSION to 16.1.0 in build/core/version_defaults.mk to override Google's anti-rollback features (This actually i don't know if is always needed)

Finally execute these:

```
. build/envsetup.sh
export ALLOW_MISSING_DEPENDENCIES=true
export LC_ALL=C
lunch omni_guacamole-eng 
mka adbd recoveryimage 
```

To test it:

```
fastboot boot out/target/product/guacamole/recovery.img
```

Kernel Source: using precompiled kernel
## Credits
I want to say a big thanks to @twinnfamous
