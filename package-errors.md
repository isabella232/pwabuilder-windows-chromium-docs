# Fixing common errors in Microsoft Store app submissions

This guide describes how to fix errors you may receive when uploading your PWA app package.

- [Invalid package publisher name](#invalid-package-publisher-name)
- [Invalid package identity name](#invalid-package-identity-name--invalid-package-family-name)
- [Invalid package family name](#invalid-package-identity-name--invalid-package-family-name)
- [This package's manifest uses a display name that you have not reserved](#this-packages-manifest-uses-a-display-name-that-you-have-not-reserved)

Be aware most of these issues are due to using the incorrect publisher information. [Get the correct publisher info](/find-publisher.md).

## "Invalid package publisher name"

<img src="/images/invalid-publisher-id.png" />

This error indicates that you need to rebuild your PWA app package with the correct `publisher`. [How can I find my publisher ID?](/find-publisher.md)

## "Invalid package identity name" / "Invalid package family name"

<img src="/images/invalid-package-id.png" />

These two combined errors, `Invalid package identity name` and `Invalid package family name`, can be fixed by rebuilding your PWA app package on PWABuilder with the correct package ID.

 In the above error message, the expected package ID is `42541MyCompany.MyAwesomePwa` - go to PWABuilder and rebuild your package with the correct package ID: <br> <img src="/images/updated-package-id.png" width="200px" />

## "This package's manifest uses a display name that you have not reserved"

<img src="/images/not-reserved.png" />

This means the app name you used when generating your app package on PWABuilder doesn't match the app name reserved in Partner Center.

The app name in Partner Center...

<img src="/images/app-name.png" width="200px" />

...must match the app name you used on PWABuilder:

<img src="/images/app-name-pwabuilder.png" width="200px" />

## Need more help?

We're here to help. You can [open an issue](https://github.com/pwa-builder/pwabuilder/issues) and we'll help walk you through it.