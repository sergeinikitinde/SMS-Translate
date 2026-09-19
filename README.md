# SMS Translate
<img alt="Logo" src="graphics/icon.png" width="120" />

SMS Translate is a messaging app that will translate incoming SMS and MMS while keeping the familiar conversation UI.

This project is a fork of [Fossify Messages](https://github.com/FossifyOrg/Messages).  
**Based on Fossify Messages, GPL-3.0.**

The original Fossify Messages source remains available at https://github.com/FossifyOrg/Messages. This repository keeps that history and adds a new application identity: name, package id, and icon.

## License

SMS Translate is free software licensed under the [GNU General Public License v3.0](LICENSE). Because it is based on Fossify Messages (GPL-3.0), the whole app — including new translation features — stays under GPL-3.0. If you distribute an APK, the corresponding source must stay available.

Fossify name, logo, and trademarks are not used here and are not licensed by the GPL.

## Current status

The first changes only rebrand the fork. Incoming-message translation is the next feature, not in this tree yet.

## Build

Android Studio or:

```bash
./gradlew assembleCoreDebug
```

Application id: `com.sergeinikitinde.smstranslate`
