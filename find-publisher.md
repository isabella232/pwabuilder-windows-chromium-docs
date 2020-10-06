# Finding your Windows Publisher ID

In order to publish your PWA in the Microsoft Store, you'll need your `Publisher ID`.

To find this, go to [Windows Dev Center](https://partner.microsoft.com/dashboard) and login with your Microsoft account. Click `⚙` -> `Developer Settings`

<img alt="Developer settings in Windows Dev Center" src="/images/devsettings.png" /> 

> 💁🏾‍♀️ *Heads up*: 
> 
> Don't see `Developer Settings`? Follow [these steps](#i-dont-see-developer-settings-or-windows-publisher-id) to enroll in the Windows Developer program.

Once in Developer Settings, choose `Account Settings`, and in `Account Details`, you'll find your `Windows Publisher ID`:

<img alt="Publisher ID details in Windows Dev Center" src="/images/publisherid.png" /> 

This is your Publisher ID (publisher common name), which you'll need when generating your Windows app on PWABuilder.

Copy the Windows publisher ID (the full string starting with `CN=`). Then, when generating your app package on PWABuilder, put the publisher ID into PWABuilder's Windows package options:

[placeholder here, will show screenshot when we have stuff]

## I don't see `Developer Settings` or `Windows publisher ID`

If you don't see `Developer Settings` in the dropdown menu, or don't see `Windows publisher ID` in your account settings as described above, then you'll likely need to enroll in the Windows Developer Program.

To do that, in the Dev Center landing page, choose `Add Program`:

<img alt="Adding an enrollment" src="/images/addprogram.png" /> 

Then choose `Windows & Xbox` -> `Get Started`:

<img alt="Enrolling in Windows and Xbox developer program" src="/images/enrollapps.png" /> 

Follow the prompts to enroll in the Windows & Xbox developer program. Once you do, you should be able to copy your `Publisher ID` as described above.

## Need more help?

Having trouble with your `Publisher ID` or having problems publishing to the Microsoft Store? We're here to help. You can [open an issue](https://github.com/pwa-builder/pwabuilder/issues) and we'll help walk you through it.