<!---
    Licensed to the Apache Software Foundation (ASF) under one
    or more contributor license agreements.  See the NOTICE file
    distributed with this work for additional information
    regarding copyright ownership.  The ASF licenses this file
    to you under the Apache License, Version 2.0 (the
    "License"); you may not use this file except in compliance
    with the License.  You may obtain a copy of the License at

      http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing,
    software distributed under the License is distributed on an
    "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
    KIND, either express or implied.  See the License for the
    specific language governing permissions and limitations
    under the License.
-->

# com.danielluxemburg.cordova.manufacturer

This plugin defines a global `manufacturer` object, which provides the name of the device maker. It is not available until after the `deviceready` event.

This plugin draws *heavily* from [org.apache.cordova.device](https://github.com/apache/cordova-plugin-device).

## Purpose

To get the manufacturer name on Android.

## Usage

```
    document.addEventListener("deviceready", onDeviceReady, false);
    function onDeviceReady() {
        console.log(manufacturer.name);
    }
```

## Installation

    cordova plugin add https://github.com/matiboy/cordova-plugin-manufacturer.git

## Properties

- manufacturer.name

## manufactruer.name

Get the name of the device maker. Some examples are:

 - samsung

### Supported Platforms

- Android
