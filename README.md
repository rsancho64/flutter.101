# flutter-101

## [MoureDev](https://www.youtube.com/watch?v=-pWSQYpkkjk)

### yt-dlp

<https://github.com/yt-dlp/yt-dlp/wiki/Installation>

tips para subtitulos:

```sh
--write-sub         Write subtitle file
--write-auto-sub    Write automatic subtitle file (YouTube only)
--all-subs          Download all the available subtitles of the video
--list-subs         List all available subtitles for the video
--sub-format FORMAT Subtitle format, accepts formats preference, 4xpl: "srt" or "ass/srt/best"
--sub-lang LANGS 
```

### flutter toolchain setup @ubuntu

`https://docs.flutter.dev/get-started/install/linux`

```sh
mkdir -p /home/ray/devel
cd /home/ray/devel
wget https://storage.googleapis.com/flutter_infra_release/releases/stable/linux/flutter_linux_3.16.9-stable.tar.xz # (628 Mb)
tar xf ./flutter_linux_3.16.9-stable.tar.xz
# export PATH="$PATH:`pwd`/flutter/bin" to ~/.bashrc: ++export PATH="/home/ray/devel/flutter/bin:$PATH"
# `source ~/.bashrc` if necessary
flutter precache
flutter doctor -v
```

- [x] vs.code plugin flutter @ `https://marketplace.visualstudio.com/items?itemName=Dart-Code.flutter`

```sh
flutter doctor -v # >> [✗] ... [!] ... [✓]
```

- [x] Install Android Studio:  

```sh
# @ https://www.makeuseof.com/install-android-studio-ubuntu/
# @ https://developer.android.com/studio?hl=es-419
# es el "Android Studio Hedgehog" 2023.1.1 Patch 2 para Linux (1.2 Gb)
wget https://redirector.gvt1.com/edgedl/android/studio/ide-zips/2023.1.1.28/android-studio-2023.1.1.28-linux.tar.gz
tar -xzvf android-studio-2023.1.1.28-linux.tar.gz # extract tarfile in ./android-studio
mv android-studio/ /home/ray/devel/

# EOF ~/.bashrc :
export PATH="$PATH:/home/ray/devel/flutter/bin"
export PATH="$PATH:/home/ray/devel/android-studio/bin"
```

`studio.sh &`  # run ... falta el android SDK, esta en /usr/lib/android-sdk/ y no lo ve. 

- [x] instalo android-sdk (28.0.2+9) via synaptic (++ muchos paquetes mas)
- No lo puedo indicar (el de sistema está en `/usr/lib/android-sdk/`)
- Descarga uno en `/home/ray/Android/Sdk`

[!] Android toolchain - develop for Android devices (Android SDK version 34.0.0)
    • Android SDK at /home/ray/Android/Sdk; ✗ cmdline-tools component is missing
Lo instalo en el SDK manager de android studio (LLnFrameworks/AndroidSDK/SDKTools/AndroidSDKCommandLineTools)

[!] Some Android licenses not accepted. To resolve this, run: `flutter doctor --android-licenses`

[!] `CHROME_EXECUTABLE` @ `~/.bashrc`:

```sh
CHROME_EXECUTABLE=/usr/bin/brave-browser
export CHROME_EXECUTABLE
# `source ~/.bashrc` if necessary
```

- [x] linux toolchain: `sudo apt install clang cmake ninja-build pkgconf libgtk-3-dev`

`flutter doctor -v` : • No issues found!

## flutter-project-in-vs-code

<https://www.youtube.com/watch?v=s7_Zj6y6bpw>
<https://medium.com/@kamranktk807/how-to-create-flutter-project-in-vs-code-step-by-step-complete-guide-466e22b235ef>

## flutter-docker

<https://medium.com/@codemax120/flutter-web-with-docker-06cee1839adb>

