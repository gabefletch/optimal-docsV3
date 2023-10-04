# 🔵 Docs v3

{% hint style="info" %}
This page includes documentation for Optimal Docs v3, powered by GitBook.\
For documentation on Docs v2 and below see [Legacy Docs](legacy-v0-v9/legacy-docs.md).
{% endhint %}

## Differences from Docs v2

Docs v2 was powered by You Need A Wiki by developer Grant Kiely. It was used because not many sites were made using YNAW at the time that Docs v2 was being built and it offered a simple UI editable via a Google Drive directory.&#x20;

See [Legacy Docs](legacy-v0-v9/legacy-docs.md) for more about Docs v2.&#x20;

## v3 Frontend

v3 is powered by GitBook, the same documentation site framework used by AltStore developer Riley Testut. It was through Optimal's integration of AltStore apps that GitBook became a good framework for its documentation/wiki solution, Optimal Docs.&#x20;

## Simplicity&#x20;

v3 is easily edited by [Optimal Team](../optimal-team.md) directly via GitBook's editing UI. It is also possible to dump the contents of a GitBook site to a GitHub repository, but we don't have plans to do this since most the editing happens in a simple markdown-style layout.&#x20;

{% hint style="info" %}
Learn more about GitBook [here](https://gitbook.com).
{% endhint %}

## Embedded Google Play Links

Certain guide pages on Docs v3 use an embedded link system to open a specific app in Google Play when tapped on an Android device. The following is a table showing apps and their respective market links used by Docs v3.&#x20;

Market links use the following syntax:\
<mark style="color:green;">market://details?id=</mark><mark style="color:blue;">com.google.android.youtube</mark>\
\
Where <mark style="color:green;">green text</mark> tells Google Play to show an app and <mark style="color:blue;">blue text</mark> is that app's store ID.&#x20;

| App            | Market Link                                               |
| -------------- | --------------------------------------------------------- |
| YouTube        | market://details?id=com.google.android.youtube            |
| YouTube Music  | market://details?id=com.google.android.apps.youtube.music |
| TikTok         | market://details?id=com.zhiliaoapp.musically              |
| Reddit         | market://details?id=com.reddit.frontpage                  |

Other app IDs can be found by going to the app's respective page on the Google Play site (play.google.com) and finding the id=\<appid> flag in its URL. [**ReVanced Manager**](../guides/android-guides/installing-revanced-manager.md) also displays the app IDs of the apps it supports in the Patcher menu.&#x20;

## Optimal Archive Links

Certain guide pages on Docs v3 refer to downloading an app from "Optimal Archive" which is Optimal Team's official Google Drive directory that includes archives of the recommended versions of apps that are needed for patching apps with[ **ReVanced Manager**](../guides/android-guides/installing-revanced-manager.md) on Android.&#x20;

Optimal Archive links are powered by dub.sh, like all links for Optimal made after v10. \
They use the following syntax:\
dub.sh/optdocs-get-\<app>

Optimal Archive links update their app target version automatically should the recommended version displayed by [**ReVanced Manager**](../guides/android-guides/installing-revanced-manager.md) change.&#x20;

| App                      | Optimal Archive Link                                             |
| ------------------------ | ---------------------------------------------------------------- |
| YouTube _v17.49.37_      | [dub.sh/optdocs-get-yt](https://dub.sh/optdocs-get-yt)           |
| YouTube Music _v5.39.52_ | [dub.sh/optdocs-get-ytmusic](https://dub.sh/optdocs-get-ytmusic) |
| TikTok vXXX              | dub.sh/optdocs-get-tik                                           |
| Reddit vXXX              | dub.sh/optdocs-get-reddit                                        |

