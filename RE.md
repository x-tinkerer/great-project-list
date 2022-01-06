# The Best Reverse Engineering Projects


## tinygrad/accel/ane/
### https://github.com/geohot/tinygrad/tree/master/accel/ane

The Apple Neural Engine is a fancy DMA Engine that is based around convolutions. We don't have all the details worked out yet, but we can do some things with it. At its core, it runs through 0x300 ops in an hwx file. See aneregs for the registers used in each op.


## m1-gpu-re
### https://github.com/hthh/m1-gpu-re
Reversing the Apple M1 GPU ISA

## mtl-gpu-asmcheck
### https://github.com/tellowkrinkle/mtl-gpu-asmcheck
Tool for messing around with Apple GPU assembly.


## m1-gpu
### https://github.com/AsahiLinux/gpu
Dissecting the M1's GPU for 3D acceleration.

## ANETools
### https://github.com/antgroup-arclab/ANETools
CLI Tools For ANE(Apple Neural Engine).
- MLModelCToANECompiler
- ANECompiler
- ANEDisassembler

## coreml_to_ane_hwx
### https://github.com/freedomtan/coreml_to_ane_hwx
a quick and dirty little program to convert Apple CoreML model to ANE hwx file.

## ios-app-signer
### https://github.com/DanTheMan827/ios-app-signer
This is an app for OS X that can (re)sign apps and bundle them into ipa files that are ready to be installed on an iOS device.


## frida-ios-dump
### https://github.com/AloneMonkey/frida-ios-dump
pull decrypted ipa from jailbreak device.


## class-dump
### https://github.com/DerekSelander/dsdump
An improved nm + Objective-C & Swift class-dump

## dyld_cache_extract
### https://github.com/macmade/dyld_cache_extract
A macOS utility to extract dynamic libraries from the dyld_shared_cache of macOS and iOS.


## iOSAppHook
### https://github.com/Urinx/iOSAppHook
专注于非越狱环境下iOS应用逆向研究，从dylib注入，应用重签名到App Hook。