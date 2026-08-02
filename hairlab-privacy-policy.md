---
layout: page
title: "HairLab Privacy Policy"
permalink: /hairlab-privacy-policy/
---

# Privacy Policy — HairLab

**Last Updated:** August 2, 2026

## Introduction

This Privacy Policy explains how the **HairLab** iOS app ("HairLab," "we," "us," or "our") handles information when you use its hairstyle and hair-color preview features.

## Summary

- HairLab does not require a user account and does not ask for your name, email address, or phone number.
- HairLab does not include advertising or analytics SDKs and does not sell personal information.
- Photos used for cloud hair editing are sent to **Perfect Corp.'s YouCam API** for processing. Do not use a cloud edit if you do not want the selected photo processed by Perfect Corp. and its service providers.
- Generated edit images and limited app state are stored locally on your device.
- HairLab does not request access to your location, contacts, or microphone.

## Information HairLab Handles

### Photos You Choose or Capture

You may select a photo through Apple's system photo picker or capture a portrait with the device camera. HairLab prepares a JPEG copy of that image for editing.

When you request a cloud hairstyle or hair-color edit, HairLab sends the prepared image and your selected edit options to Perfect Corp.'s YouCam API. Depending on the feature, those options may include a hairstyle template, color values, intensity, shine, blend strength, or placement.

Photos may contain a person's face. Perfect Corp. states that its AI and augmented-reality services may process facial geometry or similar biometric information to provide an effect, but that it does not use facial recognition or identification technology for this purpose. Only use photos of yourself or people who have authorized you to submit their images for cloud processing.

### Technical and Network Information

HairLab does not operate its own analytics service. However, when the app connects to Perfect Corp., Perfect Corp. and its infrastructure providers may automatically receive technical information such as your IP address, device or operating-system information, request timestamps, and service diagnostics. Their handling of this information is governed by the [Perfect Corp. YouCam SaaS Privacy Policy](https://www.perfectcorp.com/business/privacy).

### Information Stored on Your Device

HairLab stores limited information locally so the app can function:

- Whether onboarding has been completed.
- The date and number of cloud-edit credits used for the current day.
- Generated edit images in the app's cache so a result can be shown again without repeating the same cloud request.
- In development builds only, a developer-provided YouCam API key in the iOS Keychain.

The profile choice shown during onboarding is used only for the current onboarding flow and is not currently saved as a persistent preference or sent to HairLab servers.

## How Information Is Used

Information is used only to:

- Load a photo you choose for editing.
- Generate the hairstyle or hair-color preview you request.
- Download and display the generated result.
- Cache generated results on your device.
- Enforce the app's daily cloud-edit limit.
- Diagnose failures using sanitized operation status and error information.

HairLab does not use your photos for advertising, does not build advertising profiles, and does not sell your personal information.

## Third-Party Processing

### Perfect Corp. / YouCam API

Perfect Corp. provides the cloud image-processing service used for hairstyle and hair-color edits. A prepared portrait is uploaded to Perfect Corp. or storage infrastructure designated by Perfect Corp.; HairLab then submits an edit request and downloads the completed result.

Perfect Corp. may use affiliates and service providers, including cloud infrastructure providers, to deliver its service. Perfect Corp.'s current SaaS privacy policy states that photos submitted for cloud-computing features are deleted from its servers after use of the service is completed. Perfect Corp. independently controls its technical logs, service records, security records, and any legally required retention. Review the [Perfect Corp. YouCam SaaS Privacy Policy](https://www.perfectcorp.com/business/privacy) for its current practices and contact details.

### Apple

HairLab uses Apple's camera and system photo-picker technologies. Your photo library remains under your iOS privacy controls, and the system photo picker lets you choose the specific image made available to HairLab. Apple's handling of device and platform information is governed by [Apple's Privacy Policy](https://www.apple.com/legal/privacy/).

## Permissions

HairLab may request:

- **Camera access:** to capture a portrait when you choose **Take a Selfie**.
- **Photo access through the system picker:** to let you select a specific existing image.

You can decline camera access and use the system photo picker instead. You can review or revoke permissions in iOS Settings. HairLab does not request access to your location, contacts, or microphone.

## Data Retention and Deletion

- **Selected or captured photos:** HairLab keeps the active image in memory while you use the editor. The app does not create a permanent local copy of the original photo as part of the current editing flow.
- **Generated results:** Cached result images remain in HairLab's local cache until you select a replacement photo, iOS clears the cache, or you delete the app.
- **App state:** Onboarding and daily-credit information remains on the device until it is reset by the app or the app is deleted.
- **Development API key:** If a key was saved in a development build, it remains in the iOS Keychain until it is cleared from the development settings. Keychain data may not be removed automatically when the app is deleted.
- **Perfect Corp. data:** Retention is controlled by Perfect Corp. as described in its current privacy policy and any applicable service terms.

To remove HairLab's ordinary local app data, delete the app from your device. If you have a question or deletion request concerning data handled through HairLab, contact us using the details below. Requests concerning information controlled by Perfect Corp. may also need to be directed to Perfect Corp. at the contact address in its privacy policy.

## Security

HairLab uses encrypted HTTPS connections for cloud requests and stores development API credentials in the iOS Keychain. Cached result images are kept in the app's cache container and excluded from device backups. No transmission or storage method is completely secure, so avoid submitting a photo you are not comfortable processing in the cloud.

## International Data Transfers

Perfect Corp. and its service providers may process information in countries other than the one where you live. Those countries may have different data-protection laws. See Perfect Corp.'s privacy policy for information about its international processing practices.

## Your Choices and Rights

You may:

- Choose not to provide camera access.
- Choose a specific photo with Apple's system photo picker.
- Avoid cloud editing by not selecting a hairstyle or hair-color edit.
- Revoke app permissions in iOS Settings.
- Delete HairLab to remove ordinary locally stored app data.
- Contact us to ask about information handled through HairLab.

Depending on where you live, you may have rights to request access, correction, deletion, restriction, objection, or portability of personal information. Because HairLab has no user accounts, we may need enough information to locate a relevant request, and in some cases Perfect Corp. will be the appropriate party to handle it.

## Children's Privacy

HairLab is not directed to children under 16. We do not knowingly collect personal information from children. A parent or guardian who believes a child has submitted a photo or other personal information should contact us so we can review the request and coordinate with the relevant service provider where necessary.

## Changes to This Privacy Policy

We may update this Privacy Policy to reflect changes to HairLab, its service providers, or applicable requirements. The revised policy will be posted here with a new **Last Updated** date.

## Contact Us

For questions or privacy requests, contact:

- **Email:** [rahulbhalley@icloud.com](mailto:rahulbhalley@icloud.com)
- **GitHub Issues:** [github.com/RahulBhalley/HairLab/issues](https://github.com/RahulBhalley/HairLab/issues)
