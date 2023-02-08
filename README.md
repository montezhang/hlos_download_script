# hlos_download_script
this script is convenient to download LA image quickly, and you just need to enter your download path and your want tag.
For example:
mengdiz@jiacangl2-gv:/local3/mnt/workspace/mengdiz/test$ sh HLOS_DOWNLOAD.sh
Welcome to use HLOS code download script!



Have a nice day!

Enter your Download Path: (absolute path)
/local3/mnt/workspace/mengdiz/test

Enter the TAG you want:
AU_LINUX_ANDROID_LA.QSSI.14.0.11.00.00.993.111
Running QSSI download...
Download commnad is : (time python /local3/mnt/workspace/mengdiz/test/lint_tools/src/sync_scripts/sync.py /local3/mnt/workspace/mengdiz/test -p AU_LINUX_ANDROID_LA.QSSI.14.0.11.00.00.993.111 -t pineapple --skip-target-bins --skip-projects platform/vendor/partner_gms) |& tee qssi_sync_log_20230207_095444.txt
2023-02-07 09:54:50,562 INFO:MainThread:Initial sync workspace /local3/mnt/workspace/mengdiz/test
2023-02-07 09:54:50,564 INFO:MainThread:Preparing manifest src info for: ['AU_LINUX_ANDROID_LA.QSSI.14.0.11.00.00.993.111']


Enter the TAG you want:
AU_LINUX_ANDROID_LA.VENDOR.14.3.0.11.00.00.973.154
Running 8650 vendor download...
Download command is :( time python /local3/mnt/workspace/mengdiz/test/lint_tools/src/sync_scripts/sync.py /local3/mnt/workspace/mengdiz/test -p AU_LINUX_ANDROID_LA.VENDOR.14.3.0.11.00.00.973.154 -t qssi_64 -t pineapple -t display -t video -t camera -t audio -t cv -t sensor -t graphics -t xr --skip-target-bins --skip-projects platform/vendor/partner_gms) |& tee 8650_vendor_sync_log_20230207_095516.txt
2023-02-07 09:55:18,159 INFO:MainThread:Initial sync workspace /local3/mnt/workspace/mengdiz/test
