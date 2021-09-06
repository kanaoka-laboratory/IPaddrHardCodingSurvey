Description of Androzoo data
====

## Data Overview
Androzoo provides a list of collected APKs and their respective APK files, which are downloaded by using the hash value of the APK file in the list.

The list file is comma-separated text data. Each line contains information for one application. 
The information in each column is as follows

```sha256,sha1,md5,dex_date,apk_size,pkg_name,vercode,vt_detection,vt_scan_date,dex_size,markets```

Hash values are written in HEX.

## Data used in this study
The list data used in this study for analysis was as of February 17, 2020.
The list had 14,413,248 files listed.


## list of applications surveyd for IPv4/v6 hardcoding
We analyzed 492,979 Android applications. We provide the list at [Data](/data/) directory. This list file is compressed into an applist_ipaddrhardcode_202108.zip file. The hash value listed is the hash value of the application used for the analysis, which is the application included in the Androzoo list above.