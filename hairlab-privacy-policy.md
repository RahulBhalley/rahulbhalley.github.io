---
layout: page
title: "HairMirror Privacy Policy"
permalink: /hairlab-privacy-policy/
---

# Privacy Policy — HairMirror

**Last Updated:** August 12, 2026

## HairMirror Legal Links

- **Privacy Policy:** [https://rahulbhalley.github.io/hairlab-privacy-policy/](https://rahulbhalley.github.io/hairlab-privacy-policy/)
- **Terms of Use:** [https://rahulbhalley.github.io/hairlab-terms-of-use/](https://rahulbhalley.github.io/hairlab-terms-of-use/)

## Introduction

This Privacy Policy explains how the **HairMirror** iOS app ("HairMirror," "we," "us," or "our") handles information when you use its hairstyle and hair-color preview features.

## Summary

- HairMirror does not require a user account and does not ask for your name, email address, or phone number.
- HairMirror does not include advertising or analytics SDKs and does not sell personal information.
- Photos used for cloud hair editing are sent to **Perfect Corp.'s YouCam API** for processing. Do not use a cloud edit if you do not want the selected photo and its face data processed by Perfect Corp. and its service providers.
- Generated edit images are stored locally in a replaceable cache and in an on-device history containing up to 20 results.
- HairMirror does not request access to your location, contacts, or microphone.

## Information HairMirror Handles

### Photos You Choose or Capture

You may select a photo through Apple's system photo picker or capture a portrait with the device camera. HairMirror prepares a normalized JPEG copy, with its longest side limited to 1,024 pixels, for editing.

When you request a cloud hairstyle or hair-color edit, HairMirror sends the prepared image and your selected edit options to Perfect Corp.'s YouCam API. Depending on the feature, those options may include a hairstyle template, color values, intensity, shine, blend strength, or placement.

Photos may contain a person's face. Only use photos of yourself or people who have authorized you to submit their images for cloud processing.

### Face Data

For this policy, **face data** means the following information handled when a submitted photo contains a face:

- The visible face pixels in the selected or captured portrait and in the generated result.
- Facial geometry or facial feature vectors that Perfect Corp. may derive temporarily from the uploaded portrait to position and render the requested hairstyle or hair-color effect.

HairMirror receives a photo only when you deliberately choose one with Apple's system photo picker or camera. It uploads the prepared copy only after you request a cloud edit. HairMirror itself does not extract or create a face template, faceprint, facial feature vector, or identity profile. It does not collect TrueDepth depth data or Face ID authentication data and does not perform facial recognition, identification, identity verification, surveillance, advertising, or user profiling.

The face data is used only to prepare the portrait, send the requested edit to Perfect Corp., align and render the hairstyle or hair-color effect, return the generated image, display it, and store the result locally as described below. If you apply hair color to a generated hairstyle result, HairMirror prepares and uploads that intermediate face-containing result to Perfect Corp. as the source image for the second edit. Perfect Corp. states that it detects facial feature vectors to apply AR and AI effects and does not use facial recognition or identification technology to provide these services. HairMirror does not sell face data or use it for advertising.

### Technical and Network Information

HairMirror does not operate its own analytics service. However, when the app connects to Perfect Corp., Perfect Corp. and its infrastructure providers may automatically receive technical information such as your IP address, device or operating-system information, request timestamps, and service diagnostics. Their handling of this information is governed by the [Perfect Corp. YouCam SaaS Privacy Policy](https://www.perfectcorp.com/business/privacy).

### Information Stored on Your Device

HairMirror stores limited information locally so the app can function:

- Whether onboarding has been completed.
- Your hairstyle catalog audience preference.
- The date and number of cloud-edit credits used for the current day.
- Generated edit images in the app's cache so a result can be shown again without repeating the same cloud request.
- Up to 20 generated edit images, their creation dates, and the hairstyle or hair-color choice in the app's on-device History.
- A SHA-256 digest of the prepared JPEG, used locally to match cached results to the source photo. The digest is not a face template and is not uploaded to Perfect Corp.; the cache stores only a further hashed form in its file name.
- In development builds only, a developer-provided YouCam API key in the iOS Keychain.

The hairstyle catalog audience preference is stored only on your device to choose which hairstyle catalog the app displays. It is not inferred from the photo and is not sent with the photo to Perfect Corp. or to HairMirror servers.

## How Information Is Used

Information is used only to:

- Load a photo you choose for editing.
- Generate the hairstyle or hair-color preview you request.
- Download and display the generated result.
- Cache generated results on your device.
- Keep up to 20 generated results in on-device History so you can view or save them again.
- Enforce the app's daily cloud-edit limit.
- Diagnose failures using sanitized operation status and error information.

HairMirror does not use your photos for advertising, does not build advertising profiles, and does not sell your personal information.

## Third-Party Processing

### Perfect Corp. / YouCam API

Perfect Corp. provides the cloud image-processing service used for hairstyle and hair-color edits. A prepared portrait or intermediate generated result, together with the edit settings, is uploaded to Perfect Corp.; HairMirror then submits the edit request and downloads the completed result. HairMirror does not disclose face data to any other third party for its own purposes.

Perfect Corp. may disclose face data to its affiliates and service providers to operate the requested service and for the ordinary business purposes described in its policy, or where legally required. Its current policy identifies **Amazon Web Services (AWS)** as its server infrastructure provider. Perfect Corp. states that these providers act on its instructions, are subject to strict contractual security requirements, and are required to safeguard information consistently with its policy. HairMirror relies on those published commitments to provide the same or equivalent protection required by this policy and [Apple's App Review Guidelines](https://developer.apple.com/app-store/review/guidelines/).

Provider references:

- [Perfect Corp. YouCam SaaS Privacy Policy](https://www.perfectcorp.com/business/privacy), including its biometric-information and service-based retention sections.
- [Perfect Corp. YouCam Online Editor API Terms](https://www.perfectcorp.com/perfectbeauty/youcam/terms-of-service-api), including its facial-geometry provision.
- [AWS Privacy Notice](https://aws.amazon.com/privacy/). AWS acts as Perfect Corp.'s infrastructure provider; Perfect Corp., not HairMirror, controls that provider relationship and the retention configuration for submitted content.

### Apple

HairMirror uses Apple's camera and system photo-picker technologies. Your photo library remains under your iOS privacy controls, and the system photo picker lets you choose the specific image made available to HairMirror. Apple's handling of device and platform information is governed by [Apple's Privacy Policy](https://www.apple.com/legal/privacy/).

## Permissions

HairMirror may request:

- **Camera access:** to capture a portrait when you choose **Take a Selfie**.
- **A photo through the system picker:** to let you select a specific existing image without giving HairMirror general access to your photo library.
- **Add-only photo-library access:** only when you choose **Save Photo** or **Save Again**, so iOS can add the generated result to your library.

You can decline camera access and use the system photo picker instead. You can review or revoke permissions in iOS Settings. HairMirror does not request access to your location, contacts, or microphone.

## Data Retention and Deletion

- **Selected or captured photos on the device:** HairMirror keeps the active original and prepared JPEG in memory during the current app session. They are released when you replace the photo or the app process ends. The app does not create a permanent local copy of the original photo as part of the editing flow.
- **Face geometry or facial feature vectors:** HairMirror does not create or retain these. Perfect Corp. states that applicable facial feature vectors are no longer retained once the requested service is complete.
- **Uploaded portraits and cloud-generated results:** HairMirror uses a self-service developer API key, and no separate product-specific retention schedule has been provided to us. Under Perfect Corp.'s June 2026 YouCam Online Editor API Terms, uploaded User Submissions are stored for one day and then automatically deleted, and AI-generated Content is retained for 30 days and then automatically removed. Perfect Corp. controls and performs this cloud retention and deletion.
- **Local result cache:** A generated result and its source-digest-derived cache file name remain in HairMirror's cache until you select a replacement photo, iOS clears the cache, or you delete the app.
- **Local edit history:** HairMirror stores the 20 most recent successful generated results in Application Support on your device. When a twenty-first result is added, the oldest history image is deleted. The remaining history is deleted when you delete the app.
- **Photos you save:** If you choose **Save Photo** or **Save Again**, iOS adds a separate copy to your photo library. That copy remains until you delete it using Photos and is controlled by you and your Apple photo-library settings.
- **App state:** Onboarding, hairstyle catalog audience, and daily-credit information remains on the device until it is changed or reset by the app or the app is deleted.
- **Development API key:** If a key was saved in a development build, it remains in the iOS Keychain until it is cleared from the development settings. Keychain data may not be removed automatically when the app is deleted.

To remove HairMirror's cache and edit history, delete the app from your device. Delete any separately saved result from the Photos app. Because HairMirror has no account and does not operate a server that stores your photos, it cannot remotely identify or delete an anonymous device's local files.

If you have a question or deletion request concerning face data handled through HairMirror, contact us using the details below. For data still controlled by Perfect Corp., you may also contact [privacyteam@perfectcorp.com](mailto:privacyteam@perfectcorp.com). Perfect Corp. may need information about the request to locate any data that remains within the applicable retention period.

## Security

HairMirror uses encrypted HTTPS connections for cloud requests and stores development API credentials in the iOS Keychain. Cached results and edit-history files are kept inside the app's private container and excluded from device backups. HairMirror's diagnostics do not log submitted images, generated images, facial feature vectors, credentials, or raw service responses. No transmission or storage method is completely secure, so avoid submitting a photo you are not comfortable processing in the cloud.

## International Data Transfers

Perfect Corp. and its service providers may process information in countries other than the one where you live. Those countries may have different data-protection laws. See Perfect Corp.'s privacy policy for information about its international processing practices.

## Your Choices and Rights

You may:

- Choose not to provide camera access.
- Choose a specific photo with Apple's system photo picker.
- Avoid cloud editing by not selecting a hairstyle or hair-color edit.
- Revoke app permissions in iOS Settings.
- Delete HairMirror to remove its local cache and edit history, and use Photos to delete any result you separately saved there.
- Contact us to ask about information handled through HairMirror.

Depending on where you live, you may have rights to request access, correction, deletion, restriction, objection, or portability of personal information. Because HairMirror has no user accounts, we may need enough information to locate a relevant request, and in some cases Perfect Corp. will be the appropriate party to handle it.

## Children's Privacy

HairMirror is not directed to children under 16. We do not knowingly collect personal information from children. A parent or guardian who believes a child has submitted a photo or other personal information should contact us so we can review the request and coordinate with the relevant service provider where necessary.

## Changes to This Privacy Policy

We may update this Privacy Policy to reflect changes to HairMirror, its service providers, or applicable requirements. The revised policy will be posted here with a new **Last Updated** date.

## Contact Us

For questions or privacy requests, contact:

- **Email:** [rahulbhalley@icloud.com](mailto:rahulbhalley@icloud.com)
