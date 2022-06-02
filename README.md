# kopi installwr
kopi installer is an installer script that runs in magisk manager or recovery, which can be converted into a magisk module or kopi module.

# Variabel
- ``MODPATH`` directory where the module is edited
- ``MAGISKMOD`` magisk module directory after installing module (/data/adb/modules/"id name module")
- ``MAGISKUP`` magisk module directory before installing module (/data/adb/modules_update/"id name module")
- ``KOPIMOD`` kopi module directory (/data/kopi/modules/"id name modules")
- ``TYPEINSTALL`` Type install module (magisk,kopi,false)
- ``API`` Android SDK Code
- ``ARCH`` Architecture
- ``ID`` Id name module
- ``NAME`` Name module
- ``VERSION`` Version
- ``VERSIONCODE`` Version code
- ``DEVICE`` Device Name
- ``DATE`` Date module build
- ``AUTHOR`` Author Module

# Example script
[module.prop](https://github.com/litegapps/litegapps/blob/main/core/utils/kopi/module.prop)
 
[customize.sh](https://github.com/litegapps/litegapps/blob/main/core/utils/customize.sh)
 
[install.sh](https://github.com/litegapps/litegapps/blob/main/core/utils/install.sh)
 
[permissions.sh](https://github.com/litegapps/litegapps/blob/main/core/utils/kopi/permissions.sh)
 
[uninstall.sh](https://github.com/litegapps/litegapps/blob/main/core/utils/kopi/uninstall.sh)
 
