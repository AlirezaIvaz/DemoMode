# Demo Mode

[![Apache2](http://img.shields.io/badge/license-APACHE2-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)
[![Issues](https://img.shields.io/github/issues/AlirezaIvaz/DemoMode)](https://github.com/AlirezaIvaz/DemoMode/issues)

A simple tool presented as a Quick settings tile to simplify the process of setting up and activating **Demo Mode**.

It's already pre-configured out of the box with perfect 7:00 clock, full WiFi, full signal and full battery icons for stunning clutter-free screenshots.

You can download the app from [releases page](https://github.com/AlirezaIvaz/DemoMode/releases).

## How to use

In order for this app to work, you must grant it **Dump** and **Write Secure Settings** permissions. If your device is rooted, you can instantly grant these permissions from within the app; Otherwise, you must grant thiese permissions to the app via the `adb shell` command on your PC:

```
adb shell pm grant ir.alirezaivaz.demo_mode android.permission.DUMP
adb shell pm grant ir.alirezaivaz.demo_mode android.permission.WRITE_SECURE_SETTINGS
```

The `WRITE_SECURE_SETTINGS` is required for this app to actually work, and the `DUMP` is necessary for the quick settings tile to read the settings and present the correct icon depending on its state.

## License

    Copyright 2016-2020 Francisco Franco
    Copyright 2017-2023 Alireza Ivaz

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
