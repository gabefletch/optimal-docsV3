# 📺 Patching YouTube w/ ReVanced

{% hint style="info" %}
This page assumes you already have [**ReVanced Manager**](installing-revanced-manager.md) installed.
{% endhint %}

{% hint style="danger" %}
<mark style="color:red;">Make sure your device is ready to install unknown apps before following these steps. Otherwise you won't be able to install apps from Optimal!</mark> <mark style="color:orange;"></mark> \
****[**How to Install Unknown Apps**](installing-unknown-apps.md)****
{% endhint %}

{% hint style="warning" %}
To avoid future headaches, you'll want to install a utility app called Vanced MicroG. You can download the APK from GitHub [**here**](https://github.com/TeamVanced/VancedMicroG/releases). Open it once downloaded to start your device's installation prompts. If your device is [**rooted**](../terminology.md#root-rooting-rooted), you can skip this.
{% endhint %}

<details>

<summary>See Available Patches for YouTube (52 Items)</summary>

ReVanced can modify YouTube to include 52 patches:

* **Always Autorepeat** 0.0.1\
  Always repeats the playing video again
* **Client Spoof** 0.0.1\
  Spoofs the YouTube or Vanced client to prevent playback issues
* **Comments** 0.0.1\
  Hides components related to comments&#x20;
* **Copy Video URL** 0.0.1\
  Adds buttons in the player to copy video links
* **Custom Branding** 0.0.1\
  Changes the YouTube launcher icon and name to your choice, defaults to ReVanced
* **Custom Video Buffer** 0.0.1\
  Lets you change the buffers of videos
* **Custom Video Speed** 0.0.1\
  Adds more video speed options
* **Debugging** 0.0.1\
  Adds debugging options
* **Disable Auto Captions** 0.0.1\
  Disable forced captions from being automatically enabled&#x20;
* **Disable Auto Player Popup Panels** 0.0.1\
  Disable automatic popup panels (playlist or live chat) on video player
* **Disable Fullscreen Panels** 0.0.1\
  Disables fullscreen video description and comments panel in fullscreen view
* **Disable Startup Shorts Player** 0.0.1\
  Disables playing YouTube Shorts when launching YouTube&#x20;
* **Disable Zoom Haptics** 0.0.1\
  Disable haptics (vibration) when zooming
* **Downloads** 0.0.1\
  Enables downloading music and videos from YouTube
* **Enable Wide Searchbar** 0.0.1\
  Replaces the search icon with a wide search bar. This will hide the YouTube logo when active.&#x20;
* **General Ads** 0.0.1\
  Removes general ads
* **HDR Auto Brightness** 0.0.1\
  Makes the brightness of HDR videos follow the system default
* **Hide Album Cards** 0.0.1\
  Hides the album cards below the artist description
* **Hide Artist Card** 0.0.1\
  Hides the artist card below the searchbar
* **Hide Autoplay Button** 0.0.1\
  Hides the autoplay button in the video player
* **Hide Breaking News Shelf** 0.0.1\
  Hides the breaking news shelf on the homepage tab
* **Hide Captions Button** 0.0.1\
  Hides the captions button in the video player
* **Hide Cast Button** 0.0.1\
  Hides the cast button in the video player&#x20;
* **Hide Create Button** 0.0.1\
  Hides the create button in the navigation bar&#x20;
* **Hide Crowdfunding Box** 0.0.1\
  Hides the crowdfunding box between the player and video description&#x20;
* **Hide Email Address** 0.0.1\
  Hides the email address in the account switcher&#x20;
* **Hide Endscreen Cards** 0.0.1\
  Hides the suggested video cards at the end of a video in fullscreen&#x20;
* **Hide Info Cards** 0.0.1\
  Hides info cards in videos&#x20;
* **Hide My Mix** 0.0.1\
  Hides mix playlists
* **Hide Shorts Button** 0.0.1\
  Hides the shorts button on the navigation bar
* **Hide Time and Seekbar** 0.0.1\
  Hides progress bar and time counter on videos&#x20;
* **Hide Video Buttons** 0.0.1\
  Adds options to hide action buttons under a video&#x20;
* **Hide Watch in VR** 0.0.1\
  Hides the Watch in VR option in the video settings flyout panel
* **Hide Watermark** 0.0.1\
  Hides creator's watermarks on videos&#x20;
* **MicroG Support** 0.0.1\
  Allows YouTube ReVanced to run without root and under a different package name with Vanced MicroG
* **Minimized Playback** 0.0.1\
  Enables minimized and background playback&#x20;
* **Old Quality Layout** 0.0.1\
  Enables the original video quality flyout in the video player settings
* **Open Links Directly** 0.0.1\
  Bypasses URL redirects and opens links directly inside the YouTube app
* **Predictive Back Gesture** 0.0.1\
  Enables the predictive back gesture introduced in Android 13
* **Premium Heading** 0.0.1\
  Shows Premium branding on the home screen&#x20;
* **Remember Playback Rate** 0.0.1\
  Adds the ability to remember the playback rate you chose in the video playback rate flyout&#x20;
* **Remember Video Quality** 0.0.1\
  Adds the ability to remember the video quality you chose in the video quality flyout
* **Remove Player Button Background** 0.0.1\
  Removes the background from the video player buttons&#x20;
* **Remove Screenshot Restriction** 0.0.1\
  Removes the restriction of taking screenshots&#x20;
* **Return YouTube Dislike** 0.0.1\
  Shows the dislike count of videos using the Return YouTube Dislike API
* **Seekbar Tapping** 0.0.1\
  Allows tap-to-seek on the seekbar of the video player
* **SponsorBlock** 0.0.1\
  Integrates SponsorBlock (API that detects and skips sponsored video segments)
* **Spoof App Version** 0.0.1\
  Tricks YouTube into thinking you are running an older version of the app. One of the effects also includes restoring an older UI version.&#x20;
* **Swipe Controls** 0.0.1\
  Adds volume and brightness swipe controls in the video player
* **Tablet Mini Player** 0.0.1\
  Enables the tablet version of the mini player layout&#x20;
* **Theme** 0.0.1\
  Applies a custom theme
* **Video Ads** 0.0.1\
  Removes ads in the video player&#x20;

</details>

### Before we start...

Make sure you already have ReVanced Manager installed. See how [**here**](installing-revanced-manager.md). \
\
We need to see what version of YouTube is installed on your device. \
On most Android devices this can be done by:

* Tapping and holding the YouTube app on your homescreen
* Tapping the ⓘ that appears\
  (you may also have a button that simply says "app info"
* If the version is not displayed already, tap "Advanced" and then scroll to the bottom.

If your YouTube version is <mark style="color:red;">**v17.49.37**</mark> then skip to the <mark style="color:yellow;">yellow text</mark> at the bottom of the page.\
<mark style="color:red;">We need this exact version to be installed!</mark>

If you have a different version, follow these steps:

* We'll need to uninstall all YouTube updates from your device using Google Play.&#x20;
* Use the link below to open YouTube in Google Play and tap the "Uninstall" button on the left.

****[**Tap to Open YouTube in Google Play**](market://details?id=com.google.android.youtube)****

### Installing v17.49.37:

This version of YouTube can be downloaded directly from APKMirror using the link below:\
\
[**Tap to Download** ](https://www.apkmirror.com/wp-content/themes/APKMirror/download.php?id=4256571\&key=e9217acf2eb6908ada874dc1f2b78d07f6acc894\&forcebaseapk=true)(from APKMirror)

* Follow your device's UI prompts to download and install the app.
* Whenever in doubt, tap "Install."

{% hint style="danger" %}
<mark style="color:red;">From this point onward, if your device attempts to automatically update YouTube to a newer version, you will have to follow the steps above to downgrade it once more.</mark>
{% endhint %}

<details>

<summary>How Can I Turn Off Auto-updating?</summary>

* Open Google Play
* Tap your profile picture in the upper-right
* Tap "Settings"
* Tap "Network preferences," then "Auto-update apps" and select "Don't auto-update apps."&#x20;

</details>

### <mark style="color:yellow;">You aren't done yet, we need to patch the app:</mark>

{% content-ref url="how-do-i-patch-w-revanced.md" %}
[how-do-i-patch-w-revanced.md](how-do-i-patch-w-revanced.md)
{% endcontent-ref %}

