# Publish a new app to the Store

This guide shows how to publish your PWA as a new app in the Store. If you already have an app in the Store, you should instead [update your existing app](/update-existing-app.md).

## Enroll in Windows developer program

Login to [Windows Partner Center](https://partner.microsoft.com/dashboard) with your Microsoft account.

Then, go to your [dashboard](https://partner.microsoft.com/en-us/dashboard/home) to see your enrolled programs. If `Windows & Xbox` is listed, great, you're already enrolled. If not, choose `Add program`: <br> <img src="/images/add-program.png" width="350px" />

Then, under `Windows & Xbox`, choose `Get started`: 

<img src="/images/enroll-apps.png" width="350px" /> 

## Create your app

Now that you're enrolled in the Windows developer program, on the left-side nav bar, under `Windows & Xbox`, choose [`Overview`](https://partner.microsoft.com/en-us/dashboard/windows/overview), and click `Create a new app`:

<img src="/images/create-app.png" width="350px"/>

## Start a new submission

If you haven't yet generated your Windows app package through PWABuilder, do that first; you now have everything you need to generate your app package.

Once you've done that, follow the steps below.

Click `Start a new Submission`:

<img src="/images/start-submission.png" width="350px" />

## Add packages

On the submission details page, you'll see your most recent app submission. Click `Packages` to upload your app packages:

<img src="/images/packages-new.png" />

On the packages screen, click `Browse your files`. When browsing for your files, **choose both package files**, `*.msixbundle` *and* `*.appxbundle`.

> 💁🏾‍♂️ *Heads up*
>
> Once your packages finish uploading, you may see warnings about restricted capabilities: <br><img src="/images/full-trust-package-man.png" /><br><br>
> These warnings can be safely ignored.


> 💁‍♂️ *Other errors*
>
> If you're getting other errors when uploading your packages, see [fixing package errors](/package-errors.md).

Once you upload both package files, you should see something like this, with both packages listed:

<img src="/images/both-packages.png" />
<br>

> 💁🏽‍♀️ *Heads up*: 
> 
> Your classic app package has a lower version than the main app package. So if you packaged your PWA as version 2.0.0, the classic app package will be version 1.9.0. This way you can submit both packages as a single app.

Lastly, in the platforms support list, choose `Windows 10 Desktop` and uncheck all other platforms:

<img src="/images/win10-desktop-only.png" width="350px" />
<br>
<br>

> 💁🏿‍♀️ *Heads up*
> 
> While your PWA will run on Windows 10 desktop today, we expect Xbox support to land in 2021. 😎

Click `Save` to save your packages and return to the  submission details screen.

## Complete remaining options

You should now see the submission status. Fill out any incomplete statuses:

<img src="/images/not-started-status.png" width="350px" />

> 💁🏼‍♀️ *Heads up*
>
> In `Submission options`, you may receive a warning about restricted capabilities: <br> <img src="/images/full-trust-restricted.png" width="350px" /><br><br>
> You can write, "Needed for PWA Hosted App model, created by pwabuilder.com"

Complete all such statuses, then click `Submit to the Store` when finished.

## Need more help?

If you're having trouble with your app store submission, be sure to read [fixing package errors](/package-errors.md).

If you're still hitting issues, we're here to help. You can [open an issue](https://github.com/pwa-builder/pwabuilder/issues) and we'll help walk you through it.