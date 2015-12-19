#Device tree for OnePlus X

###Syncing repo
Add this to your localmanifest
```xml
<manifest>
  <project name="MasterAwesome/android_device_oneplus_onyx" path="device/oneplus/onyx" remote="github" revision="master"/>
  <project name="CyanogenMod/android_device_oppo_common" path="device/oppo/common" remote="github" />
  <project name="MasterAwesome/android_kernel_oneplus_msm8974" path="kernel/oneplus/onyx" remote="github" revision="5.1.1" />
  <project name="MasterAwesome/android_vendor_oneplus_onyx" path="vendor/oneplus/onyx" remote="github" revision="master" />
  <project name="CyanogenMod/android_device_qcom_common" path="device/oppo/common" remote="github" revision="cm-12.1" />
</manifest>
```

###Building
```bash
. build/envsetup.sh
lunch cm_onyx-(eng|userdebug|user)
make #recipe
```
