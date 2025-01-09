# MicroG
MicroG is an **open source re-implementation of Android Google services and libraries** that respects your privacy and all you have to do is **installing .apk files from** [the website](https://microg.org/download.html). It is so easy! Also, **Huawei** devices can use MicroG!
## Who Is MicroG For?
- MicroG is for everyone who wants to **de-google** their lives and/or for everyone who wants to **increase the privacy against Google** as much as possible.
- If you're using a **stock ROM**, which means the operating system environment you have preinstalled after buying your phone, you **shouldn't** use MicroG because stock ROMs already have official Google services and libraries unless you're **not** using a **Huawei** phone.
- In other words, to be able to use MicroG, you have to either use a **Huawei** phone or you have to install a **custom ROM** on your phone.
  - However, if you want to use MicroG on **a custom ROM**, you should take a look at [this article](https://github.com/microg/GmsCore/wiki/Signature-Spoofing), otherwise, MicroG **won't work** on your custom ROM!!!
### What Are the Benefits of Using MicroG
MicroG simply lets you use your Google account and services like safety net, push notifications, location etc. with the most privacy possible. It doesn't provide 100% privacy but it increases the privacy on a drastic level. Also, MicroG consumes way less resources which helps with **longer battery life**. If you'd like to find out about MicroG more, you can check [their website](https://microg.org/).
### What Are the Disadvantages of Using MicroG
- Google auto contact sync feature is not working.
- WhatsApp restoring backup issues.
- WhatsApp's live location feature is not working.
- Push notifications feature is sometimes showing notifications delayingly.
- Some apps can't log in using Google account.
## Post Installation Steps
- After installing MicroG from the website, you should change **microG Settings app's** battery optimization to `Unrestricted`.
  - Next, simply log in your Google account inside the app and open your system's **Settings** app.
    - After opening settings, go to `Passwords, passkeys & autofill` and click on your google account. Next, go to `Account preferences` and enable the two options you see.
  - Now go back to **microG Settings app** and **enable** `Google device registration, Cloud Messaging and Google SafetyNet.`
    - For Location modules, you need to install `Nominatim` from **F-Droid**. This is mandatory to be able to use maps.
    - For the network-based geolocation module, you should install `Apple UnifiedNlp Backend` and `Local NLP Backend` from **F-Droid**. After installing, go back to **microG Settings app** and go to `Location modules`, next, enable `Nominatim`, `Local NLP Backend` and `Apple Wi-Fi`.
      - Apple UnifiedNlp Backend is **proprietary** but as you might know, maps are not joke. So, we have to search for the best option possible. Apple's option is the only viable one in this case. But it's okay because Apple will only have your map data, not your personal data.
 - The last step after configuring MicroG is installing a **store app**. My suggestion is [Aurora Store](https://auroraoss.com/), it's an **open source Play Store alternative** and it **doesn't send any telemetry to Google**.
## Conclusion
This guide was about how to install and configure MicroG. I hope it has been useful for you. Have a nice day! 🐧
