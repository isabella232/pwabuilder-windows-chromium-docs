# Update an existing app in the Store

This guide shows how to publish your PWA as an update to an existing app in the Store. If you don't have an app in the Store yet, you should instead [publish a new app](/publish-new-app.md).

## Choose the app you want to update

Login to [Windows Partner Center](https://partner.microsoft.com/dashboard), then go to `Windows & Xbox` -> `Overview`. Your existing apps will be listed:

<img src="/images/existing-apps.png" />

Click the name of the app you want to update, and you'll be taken to the app details page.

## Add a new submission

On the app details page, you'll see your most recent app submission. Click `Update` to add a new submission:

<img src="/images/add-submission.png" />

On the submission details page, choose `Packages`:

<img src="/images/packages.png" width="250px" />

On the packages screen, click `Browse your files`:

<img src="/images/browse-for-package.png" />

When browsing for your files, **choose both package files**, `*.msixbundle` and `*.appxbundle`.

> 💁🏾‍♂️ *Heads up*
> Once your packages finish uploading, you may see the following warning about full trust: <br><img src="/images/full-trust.png" />
> This warning can be safely ignored.


> 💁‍♂️ *Other errors*
> If you're getting other errors when uploading your packages, see [fixing package errors](/package-errors.md).

Once you upload both package files, you should see something like this, with both packages listed:

<img src="/images/both-packages.png" />
<br>
<br>

> 💁🏽‍♀️ *Heads up*: 
> 
> Your classic app package has a lower version than the main app package. So if you packaged your PWA as version 2.0.0, the classic app package will be version 1.9.0. This way you can submit both packages as a single app.

Lastly, in the platforms support list, choose `Windows 10 Desktop` and uncheck all other platforms:

<img src="/images/win10-desktop-only.png" />
<br>
<br>

> 💁🏿‍♀️ *Heads up*
> 
> While your PWA will run on Windows 10 desktop today, we expect Xbox support to land in 2021. 😎

Click `Save` to save your packages and return to the  submission details screen.

## Complete remaining options

You should now see the submission status. Fill out any `in progress` or `incomplete` settings:

<img src="/images/remaining-options.png" />

In the above image, `Age ratings` is `In progress` and `Submission options` is `Incomplete`.

> 💁🏼‍♀️ Heads up
> In `Submission options`, you may receive a warning about full trust capability: <br> <img src="/images/full-trust-restricted.png" />
> You can write, "Needed for PWA Hosted App model, created by pwabuilder.com"

Complete all such statuses, then click `Submit to the Store` when finished.

## Need more help?

If you're having trouble with your app store submission, be sure to read [fixing package errors](/package-errors.md).

If you're still hitting issues, we're here to help. You can [open an issue](https://github.com/pwa-builder/pwabuilder/issues) and we'll help walk you through it.