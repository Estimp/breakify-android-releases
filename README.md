# Breakify - Android Releases

Official repository for compiled APK releases of the Breakify Android app.

## Download Latest Version
1. Go to the [Releases section](https://github.com/Estimp/breakify-android-releases/releases).
2. Download the APK file from the latest release.
3. Enable "Unknown sources" in Android settings.
4. Install the APK.

> **Note:** This repository contains only release binaries, not source code.
>
> **Security notice:** On some Android versions, features like notifications may be restricted when installing via APK. For full functionality, use an emulator or device without security restrictions.

## Project Architecture
Breakify consists of multiple independent services:

| Component       | Repository                          | Description                  |
|-----------------|-------------------------------------|------------------------------|
| **Android App** | **This repository**                 | Compiled APK releases        |
| API Service     | [breakify-service](https://github.com/Estimp/breakify-service) | Back-end RESTful API             |
| MQTT Message Consumer | [breakify-mqtt](https://github.com/Estimp/breakify-mqtt) | Subscribes and processes MQTT messages |