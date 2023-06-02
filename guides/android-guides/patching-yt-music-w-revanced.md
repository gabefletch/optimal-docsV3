# 🔊 Patching YT Music w/ ReVanced

{% hint style="info" %}
This page assumes you aleady have [**ReVanced Manager**](installing-revanced-manager.md) installed.&#x20;
{% endhint %}

{% hint style="danger" %}
<mark style="color:red;">Make sure your device is ready to install unknown apps before following these steps. Otherwise you won't be able to install apps from Optimal!</mark> \
[**How to Install Unknown Apps**](installing-unknown-apps.md)
{% endhint %}

{% hint style="warning" %}
To avoid future headaches, you'll want to install a utility app called Vanced MicroG. You can download the APK from GitHub [**here**](https://github.com/TeamVanced/VancedMicroG/releases). Open it once downloaded to start your device's installation prompts. If your device is [**rooted**](../terminology.md#root-rooting-rooted), you can skip this.
{% endhint %}

<details>

<summary>See Available Patches for YT Music (12 Items)</summary>

ReVanced can modify YouTube Music to include 12 patches:

* **Background Play** 0.0.1\
  Enables playing music in the background&#x20;
* **Codecs Unlock** 0.0.1\
  Adds more audio codec options; the new audio codecs usually result in better audio quality&#x20;
* **Compact Header** 0.0.1\
  Hides the music category bar at the top of the homepage
* **Exclusive Audio Playback** 0.0.1\
  Enables the option to play music without video&#x20;
* **Hide Get Premium** 0.0.1\
  Removes all "Get Premium" evidences from the avatar menu&#x20;
* **Minimized Playback Music** 0.0.1\
  Enables minimized playback on "Kids" music&#x20;
* **Music MicroG Support** 0.0.1\
  Allows YouTube ReVanced to run without root and under a different package name
* **Music Video Ads** 0.0.1\
  Removes ads in the music player&#x20;
* **Predictive Back Gesture** 0.0.1\
  Enables the predictive back gesture introduced in Android 13
* **Remove Screenshot Restriction** 0.0.1\
  Removes the restriction of taking screenshots&#x20;
* **Tastebuilder Remover** 0.0.1\
  Removes the "Tell us which artists you like" card from the homescreen
* **Upgrade Button Remover** 0.0.1\
  Removes the upgrade tab from the pivot bar

</details>

### Before we start...

Make sure you already have ReVanced Manager installed. See how [**here**](installing-revanced-manager.md).&#x20;

We need to see what version of YouTube Music is installed on your device. \
On most Android devices this can be done by:

* Tapping and holding the YouTube Music app on your homescreen&#x20;
* Tapping the ⓘ that appears\
  (you may also have a button that simply says "app info"
* If the version is not displayed already, tap "Advanced" and then scroll to the bottom.

If your YouTube Music version is <mark style="color:red;">**`v5.39.52`**</mark> then skip to the <mark style="color:yellow;">yellow text</mark> at the bottom of this page.\
<mark style="color:red;">We need this exact version to be installed!</mark>&#x20;

If you have a different version, follow these steps:

* We'll need to uninstall all YouTube Music updates from your device using Google Play.&#x20;
* Use the link below to open YouTube Music in Google Play and tap "Uninstall" on the left.&#x20;

[**Tap to Open YouTube Music in Google Play**](market://details?id=com.google.android.apps.youtube.music)&#x20;

### Installing `v5.39.52`

Tap the link below to download the version of YouTube Music needed for patching:

[Download `v5.39.52` from Optimal's GitHub Repository](https://github.com/gabefletch/ReVanced-BaseApps/releases/download/M-v5.39.52/com.google.android.apps.youtube.music\_5.39.52-53952230\_minAPI21.armeabi-v7a.nodpi.\_apkmirror.com.apk)
