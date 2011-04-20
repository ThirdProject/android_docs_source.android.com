<!--
   Copyright 2010 The Android Open Source Project 

   Licensed under the Apache License, Version 2.0 (the "License"); 
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
-->

# Android Technical Information #
Welcome to the Android technical documentation section of the site. Here you
can find technical information useful to people and organizations who are
looking to modify, contribute to, or port the Android software. This is "under
the hood" information intended for engineers.

## Dalvik Technical Information ##
The Dalvik Virtual Machine is the heart of Android. It's a fast, just-in-time
compiled, optimized bytecode virtual machine. Android applications are
compiled to Dalvik bytecode and run on the Dalvik VM. This section includes
detailed information such as the Dalvik bytecode format specification,
design information on the VM itself, and so on.

[&raquo; Dalvik Information](/tech/dalvik/index.html)


## Bluetooth Technical Information ##
The Android Open-Source Project includes a bluetooth subsystem currently based
on the upstream bluez project. Android then layers various IPC and similar
libraries to link the bluez library with the Android Bluetooth stack and API.

[&raquo; Bluetooth Information](/tech/bluetooth/index.html)


## NFC Technical Information ##
The Android Open-Source Project also includes an NFC implementation. Unlike
the Android Bluetooth stack, much of the Android NFC stack is new code
originally contributed to the Android Open-Source Project. This code links the
Android NFC API to a device's NFC hardware. This section also includes
information on related Android technologies, such as the simple NDEF Push
Protocol.

[&raquo; NFC Information](/tech/nfc/index.html)

## Encryption Technical Information ##
The Android Open-Source Project includes the ability to encrypt the user's data.
This document is written for 3rd parties developing Android devices who want to
include support for encryption on their device.  It covers the few things that
must be done so encryption will work.

[&raquo; Encryption Information](/tech/encryption/index.html)
