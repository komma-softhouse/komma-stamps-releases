# Komma Stamps

The phone of **Komma Stamps**. It certifies photos, videos and documents the
moment they are taken: the phone computes their SHA-256 fingerprint and only
that fingerprint is anchored on Arbitrum One, so the file never leaves the
device. It follows every anchor until it is confirmed, signs the contracts
waiting for you and checks any certificate by its QR or by its file. It keeps
working when the network drops.

## Download

| System | Download |
| --- | --- |
| **Android 13 or later** | [Latest version](https://github.com/komma-softhouse/komma-stamps-android-releases/releases/latest): the `.apk` file |

Every published version is listed under
[Releases](https://github.com/komma-softhouse/komma-stamps-android-releases/releases).
Each version also carries its `.sha256` file to check that the `.apk` has not
been altered. The easiest way is to download it from the panel itself, in
**Stamps → Apps**, which always links the latest version.

## What it does

- **Certify at capture.** Take a photo or record a video from the app, or choose
  a document of the phone. The fingerprint is computed on the phone and shown
  before anything is sent; you give it a title and anchor it with one credit.
- **Only the fingerprint travels.** The photo, the video or the document never
  leaves the phone. When the camera gives the place of a photo, you decide photo
  by photo whether it goes with the certification.
- **R&D notebooks.** With a plan, a certification can be chained as the next
  version of a notebook of your workspace.
- **Certificates.** Each certification shows its steps (fingerprint, Merkle
  batch, block), its public certificate with QR, the PDF to share and the
  evidence pack.
- **Contracts.** The contracts waiting for your signature open in the signing
  portal inside the app.
- **Verify.** Read the QR of any Komma Stamps certificate, or choose the file you
  were sent and check whether its fingerprint is anchored.
- **Without network.** What you certify waits on the phone, in order, and goes
  out by itself when there is network; a retry never spends a second credit. The
  date that counts is the one of the anchor.
- **Notifications.** A notification arrives when an anchor is confirmed or fails.
- **Lock.** Optionally, the app asks for your fingerprint or your face when it
  opens.
- **Updates itself.** From **Account → Updates**, without Google Play.

## Install

1. On the phone, open the
   [latest version](https://github.com/komma-softhouse/komma-stamps-android-releases/releases/latest)
   and download the `.apk` file.
2. Open it. If Android asks for permission to install apps from this source,
   allow it for the browser and go back.
3. Tap **Install**. Komma Stamps appears in the app drawer.

## Getting started

1. **In the panel** of your workspace, go to **Stamps → Apps → Pair an app**. A
   code and its QR appear, valid for 15 minutes and for a single use.
2. **On the phone**, tap **Read the QR of the panel** and point at the QR (or type
   the address of your workspace and the code), name this phone and tap **Pair**.
3. **Certify.** From **Home**, choose *Photo*, *File* or *Verify*. The phone
   certifies with the credits of your plan, as the user who made the code.

## Requirements

- Android 13 or later.
- Rear camera for photos, videos and reading QR codes.
- Wi-Fi or mobile data to reach your workspace. Certifying works without network:
  the fingerprint waits on the phone until it can be sent.

## Updates

In **Account → Updates** tap **Check for updates**. If there is a new version,
**Download and install** fetches it, checks that it arrived complete and opens
the Android installer. The first time, Android asks to allow installing from
Komma Stamps. The phone keeps its pairing and everything still waiting to be
sent.

## If something fails

When the app meets an unexpected error it shows an incident code and a button to
report it. The report reaches Komma with the code, the version and the screen,
never a file or a fingerprint of yours. If you call support, have the code at
hand.

## Support

Komma SoftHouse · [stamps.kommasofthouse.com](https://stamps.kommasofthouse.com) · info@kommasofthouse.com
