## Deprecated

BluetoothCompat
===============

Compatibility library back-porting the Android 5.0 Bluetooth LE Scanner api concepts to API 18+.


Gradle
------

```
dependencies {
    compile 'com.forkingcode.bluetoothcompat:bluetoothcompat:1.0.0'
}
```

Mapping of Classes
------------------

ScanFilterCompat - Add filters in a manner similar to ScanFilter

ScanSettingsCompat - Add settings in a manner similar to ScanSettings. Note: Power levels only honored at moment on 5.0 (API 21+)

ScanCallbackCompat - Compatible version of ScanCallback.

ScanResultCompat - Compatible version of the ScanResult.

ScanRecordCompat - Compatible version of the ScanRecord.


To Use
------

BluetoothLeScannerCompat.startScan(bluetoothAdapter, scanFilters, scanSettings, callback);

BluetoothLeScannerCompat.stopScan(bluetoothAdapter, callback);

License
-------

    Copyright (C) 2014 The Android Open Source Project
    Copyright (C) 2015 Joe Rogers

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
