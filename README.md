![](https://raw.githubusercontent.com/balena-io-projects/balena-sound/master/images/balenaSound-logo.png)

**Starter project enabling you to add multi-room audio streaming via Bluetooth, Airplay or Spotify Connect to any old speakers or Hi-Fi using just a Raspberry Pi.**

# Highlights

- **Bluetooth, Airplay and Spotify Connect**: Stream audio from your favourite music services or directly from your smartphone/computer using bluetooth.
- **Multi-room synchronous playing**: Play perfectly synchronized audio on multiple devices all over your place.
- **Extended DAC support**: Upgrade your audio quality with one of our supported DACs

# Installation

1. Clone the code from github:

    ```
    git clone https://github.com/balenalabs/balena-sound.git
    ```

2. Go into the code directory:

    ```
    cd balena-sound
    ```

3. Push code to your fleet of audio streamers:

    ```
    balena push my-balena-sound
    ```

# Documentation 

Head over to our [docs](https://landr-balenalabs-repo-balena-sound.netlify.com/docs) for detailed usage instructions, customization options and more!

# Motivation

![](https://raw.githubusercontent.com/balenalabs/balena-sound/landr/images/sound.png)

There are many commercial solutions out there that provide functionality similar to balenaSound. 
Most of them though come with a premium price tag and are riddled with privacy concerns. balenaSound is an open source project that allows you to build your own DIY audio streaming platform without compromises. Why spend big money on hardware that might be deemed obsolete by the vendor as they see fit? With balenaSound you are in control, bring your old speakers back to life!

This project is in active development so if you have any feature requests or issues please submit them here on GitHub. PRs are welcome, too.

# Hardware required

* Raspberry Pi 3A+/3B/3B+/4B/Zero W
* SD Card (we recommend 8GB Sandisk Extreme Pro)
* Power supply (We recommend the official ones of the Raspberry Pi Foundation)
* 3.5mm audio cable to the input on your speakers/Hi-Fi (usually 3.5mm or RCA). Alternatively you can use the HDMI port to get digital audio out.

# Software required

* A download of this project (of course)
* Software to flash an SD card ([balenaEtcher](https://balena.io/etcher))
* A free [balenaCloud](https://balena.io/cloud) account
* The [balena CLI tools](https://github.com/balena-io/balena-cli/blob/master/INSTALL.md)

# Getting Help

If you're having any problem, please [raise an issue](https://github.com/balenalabs/balena-sound/issues/new) on GitHub and we will be happy to help.

# Contributing

Do you want to help make balenaSound better? Take a look at our [Contributing Guide](https://landr-balenalabs-repo-balena-sound.netlify.com/contributing). Hope to
see you around!

# License

balenaSound is free software, and may be redistributed under the terms specified in the [license](https://github.com/balenalabs/balena-sound/blob/master/LICENSE).
