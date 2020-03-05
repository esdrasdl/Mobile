<div align="center">
  
  [<img width="400px" src="https://github.com/combateafraude/android-sdk/blob/master/resources/logo_black.png?raw=true">](https://combateafraude.com)

  # Combate a Fraude - Android SDKs
</div>

<hr>

This repository contains realeases and documentation of Combate a Fraude's Android SDKs.

For more information about a specific topic, please check [our wiki](https://github.com/combateafraude/android-sdk/wiki) or [create an issue](https://github.com/combateafraude/android-sdk/issues).

These are the current avaliable modules:

#### CAF_Onboarding

Provides an interface used to scan a document and capture a real selfie of the user, used for registration process. It uses `CAF_DocumentDetector` + `CAF_FaceLiveness`

[Full documentation for CAF_Onboarding](https://github.com/combateafraude/android-sdk/wiki/CAF_Onboarding)

#### CAF_DocumentDetector

Provides an interface used to scan and validate documents. Ensures that the scanned document has enough quality to facilitate the process of Optical Character Recognition (OCR).

[Full documentation for CAF_DocumentDetector](https://github.com/combateafraude/android-sdk/wiki/CAF_DocumentDetector)

#### CAF_FaceAuthenticator

Provides an interface used to capture a selfie and compare it with a server-stored image, making sure they are the same person.

[Full documentation for CAF_FaceAuthenticator](https://github.com/combateafraude/android-sdk/wiki/CAF_FaceAuthenticator)

#### CAF_FaceLiveness

Provides an interface used to make sure that the person in front of the device is a live person and not a photo or recording.

[Full documentation for CAF_FaceLiveness](https://github.com/combateafraude/android-sdk/wiki/CAF_FaceLiveness)

#### CAF_Security

Provides an interface to get a fingerprint and check the security of the current device.

[Full documentation for CAF_Security](https://github.com/combateafraude/android-sdk/wiki/CAF_Security)


## Changelog

Take a look at the [changelog](https://github.com/combateafraude/android-sdk/wiki/Changelog) page.
