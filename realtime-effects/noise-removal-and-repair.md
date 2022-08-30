# Noise Removal and Repair

## MuseFX Noise Gate

A noise gate. Part of the [#muse-fx](plugin-suites.md#muse-fx "mention") pack.

<details>

<summary>Details</summary>

See the pack for installation instructions.

A noise gate keeps noise in quiet parts out while not affecting the audio you want at all.

![](<../.gitbook/assets/image (5).png>)

</details>

## MuseFX De-Ess

An easy to use de-esser. Part of the [#muse-fx](plugin-suites.md#muse-fx "mention") pack.

<details>

<summary>Details</summary>

See the pack for installation instructions.

Has presets for female and male voices, harshness, sibilance, steel guitar and strings rosin.

![](<../.gitbook/assets/image (2).png>)

</details>

## ReaFIR

A multi-purpose dynamics processor, can be used for EQ, compressor, gate and noise reduction purposes. Part of ReaPlugs.

{% embed url="https://www.reaper.fm/reaplugs" %}
Download page
{% endembed %}

{% hint style="info" %}
Hint: ReaFIR in Subtract mode can be used to remove noise.
{% endhint %}

<details>

<summary>Details</summary>

Copyright (C) 2006-2016, Cockos Incorporated VST PlugIn Technology by Steinberg Media Technologies GmbH

Information from the vendor:

* FFT based dynamics processor
* Supports FFT sizes of 128-32768
* Useful in/out frequency response display
* Supports defining response curves both using any number of points, or freehand mouse
* EQ - can be used as a linear phase mastering EQ, or as a super-effective surgical EQ
* Compressor - can compress at a fixed ratio with a per-band threshold
* Gate - can gate with per-band threshold
* Subtract - can build noise profiles and subtract noise from the signal

![](../.gitbook/assets/reafir.png)

</details>

## NVIDIA Broadcast

A virtual device that sits between your microphone and Audacity and other programs which allows you to use an AI denoiser.

{% hint style="warning" %}
**Caution:** NVIDIA Broadcast only works on Windows machines with a NVIDIA RTX GPU.

Further, it only works on spoken word content; musical content is treated as noise and filtered out.&#x20;
{% endhint %}

{% embed url="https://www.nvidia.com/en-gb/geforce/broadcasting/broadcast-app/" %}
Download page
{% endembed %}

<details>

<summary>Details</summary>

Copyright © 2022 NVIDIA Corporation

Requires NVIDIA GeForce RTX 2060, Quadro RTX 3000, TITAN RTX or higher

Full setup guide: [https://www.nvidia.com/en-gb/geforce/guides/broadcast-app-setup-guide/](https://www.nvidia.com/en-gb/geforce/guides/broadcast-app-setup-guide/)

Technically, NVIDIA Broadcast isn't a plugin but a virtual device. You will find it in Audacity's audio settings as an input. It does not show up in the Plugin Manager.

</details>