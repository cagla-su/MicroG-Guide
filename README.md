# MicroG
MicroG is an **open source re-implementation of Android Google services and libraries** that respects your privacy and all you have to do is **installing .apk files from** [the website](https://microg.org/download.html). It is so easy! Also, **Huawei** devices can use MicroG!
## Who Is MicroG For?
- MicroG is for everyone who wants to **de-google** their lives and/or for everyone who wants to **increase the privacy against Google** as much as possible.
- If you're using a **stock ROM**, which means the operating system environment you have preinstalled after buying your phone, you **shouldn't** use MicroG because stock ROMs already have official Google services and libraries unless you're **not** using a **Huawei** phone.
- In other words, to be able to use MicroG, you have to either use a **Huawei** phone or you have to install a **custom ROM** on your phone.
  - However, if you want to use MicroG on **a custom ROM**, you should take a look at [this article](https://github.com/microg/GmsCore/wiki/Signature-Spoofing), otherwise, MicroG **won't work** on your custom ROM!!!
### What are the benefits of using MicroG?
MicroG simply lets you use your Google account and services like safety net, push notifications, location etc. with the most privacy possible. It doesn't provide 100% privacy but it increases the privacy on a drastic level. Also, MicroG consumes way less resources which helps with **longer battery life**. If you'd like to find out about MicroG more, you can check [their website](https://microg.org/).
### What are the disadvantages of using MicroG?
- Google auto contact sync feature is not working so you have to manually import your contacts.
- WhatsApp restoring backup issues.
- Some apps can't log in using Google account.
## Post Installation Steps
- After installing MicroG from the website, you should change **microG Settings app's** battery optimization to `Unrestricted`.
  - Open **microG Settings app** and go to `Google Accounts`
    - Add your Google account and make sure `Trust Google for app permissions`, `Allow apps to find accounts`, and `Authenticate with device registration` options are enabled.
  - Now go back and **enable** `Google device registration, Cloud Messaging and Google SafetyNet.`
  - Next, go to `Location` and enable all the options you see, when you're asked which online location service you want to use, you can try **Positon** as the suggested one. However, **BeaconDB** worked better for me, it's totally up to you.
 - The last step after configuring MicroG is installing a **store app**. My suggestion is [Aurora Store](https://auroraoss.com/), it's an **open source Play Store alternative** and it **doesn't send any telemetry to Google**.
## Conclusion
This guide was about how to install and configure MicroG. I hope it has been useful for you. Have a nice day! 🐧
