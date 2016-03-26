---
layout: post
title: Tutorial Dasar Setup JDK dan Android Studio
---
![Banner](https://twentyfoursevensupport.com/images/android.png)
Untuk dasar-dasar sebelum membangun sebuah aplikasi android, maka perlu tool-tool pendukung, diantaranya adalah sebuah IDE (Integrated Development Enviroment) Android Studio yang di siapkan oleh Google untuk membantu para developernya dalam mempermudah membangun aplikasi. Berikut adalah Tutorial untuk setup tool-tool pendukungnya.

## Download dan Install JDK

* Platform Windows :
Buka Link Berikut [Hasil pencarian dari Internet](http://www.caratutorial.com/2015/02/install-dan-setting-java-development-kit-jdk-di-windows.html)

* Platform Linux :
Buka Link Berikut [Hasil pencarian dari Internet](http://www.pintarkomputer.com/cara-mudah-install-oracle-java-jdk-di-linux-ubuntu/)

* Platform OSX :
Buka Link Berikut untuk install oracle JDK 8 [Hasil pencarian dari Internet](http://computechtips.com/781/install-oracle-jdk-8-mac-os-x-10-10-yosemite)

## Install Android Studio dan SDK

## To set up Android Studio on Windows:

1. Launch the .exe file you downloaded.
2. Follow the setup wizard to install Android Studio and any necessary SDK tools.
On some Windows systems, the launcher script does not find where the JDK is installed. If you encounter this problem, you need to set an environment variable indicating the correct location.
Select Start menu > Computer > System Properties > Advanced System Properties. Then open Advanced tab > Environment Variables and add a new system variable JAVA_HOME that points to your JDK folder, for example 

```
C:\Program Files\Java\jdk1.7.0_21.
```

The individual tools and other SDK packages used by Android Studio are installed in a separate directory. If you need to access the tools directly, use a terminal to navigate to the location where they are installed. For example:

```
\Users\<user>\sdk\
```

## To set up Android Studio on Mac OSX:

1. Launch the .dmg file you downloaded.
2. Drag and drop Android Studio into the Applications folder.
3. Open Android Studio and follow the setup wizard to install any necessary SDK tools.
If you need to use the Android SDK tools from a command line, you can access them at:

```
/Users/<user>/Library/Android/sdk/
```

## To set up Android Studio on Linux:

1. Unpack the .zip file you downloaded to an appropriate location for your applications.
2. To launch Android Studio, open a terminal, navigate to the android-studio/bin/ directory, and execute studio.sh.
3. You may want to add android-studio/bin/ to your PATH environmental variable so that you can start Android Studio from any directory.
If the SDK is not already installed, follow the setup wizard to install the SDK and any necessary SDK tools.

Note: To support 32-bit apps on a 64-bit machine, you will need to install the ia32-libs, lib32ncurses5-dev, and lib32stdc++6 packages.

Copy dari : [Developer Android](http://developer.android.com/sdk/installing/index.html?pkg=studio)

