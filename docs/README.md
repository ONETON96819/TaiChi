## Introduction 

TaiChi is a framework to use Xposed module with or **without** Root/Unlock bootloader, it currently supports Android 5.0 ~ **10.0**.

In simple words, TaiChi is a **Xposed-Styled** Framework, it can load Xposed modules, do hooks and so on.

## Features

TaiChi is Xposed-Styled, but it has no relation with Xposed. The only relevance is that TaiChi can load Xposed modules, the implementation of TaiChi and Xposed Framework is very different.

Here are some features of Taichi:

1. TaiChi **fully supports Android Pie**.
2. TaiChi can run in a **non-root environment**.
3. TaiChi does not affect the android system and it does not hook all apps in system. Only the apps that you want to apply Xposed modules are hooked. Other apps in your system will run in a completely intact environment, which means TaiChi can **pass SafetyNet easily**.
4. TaiChi **doesn't need to reboot** system in most cases.
5. TaiChi is **hard to be detected**. TaiChi doesn't modify the libart and app_process, thus it has nearly no noticeable characteristics.

## Usage

TaiChi has two operating mode: magisk mode and non-root mode. If you don't want to unlock the bootloader/flash system images, you can use the non-root mode, but if you prefer more powerful functions, you will need to go for the magisk mode.

Please refer [**Guide**](/getting_started).

## For Developers 

TaiChi is a framework, and developers are welcomed to write xposed modules with hooks based on TaiChi Framework. Module written based on TaiChi framework is fully compatible with Xposed Framework, so contrary a Xposed Framework-based module will work well with the TaiChi framework too. 

But before that, we need to clarify that there's still some differences between TaiChi Framework and Xposed Framework, please refer [For Xposed Developers](https://github.com/taichi-framework/TaiChi/wiki/For-Xposed-developer) for further details. 

## Discussion

- [Telegram Group](https://t.me/vxp_group)
- QQ Group: 729163976

## Contact me

[email](mailto:twsxtd@gmail.com)