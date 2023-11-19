# CCArmory
CCArmory is an Android app to securely store credit card information and easily track reward cycles.

NOTE THIS IS IN DEVELOPMENT AND THE BELOW REFLECTS THE PLANNED MVP

### Pitch
Many financial institutions that offer credit cards do not allow looking up the full information present on a credit card, even in official webapps or mobile apps. Some allow you to get the card number, but not the expiration or CVV/CVC. If you've ever needed to make a purchase that requires re-validating credit card information, especially when you don't have the physical card with you, you can see why an app like this would be helpful.

Furthermore, given the rotating rewards offered by various credit cards, it's convenient to quickly assess the best value by entering reward period details. You can also set reminders for the end of the reward period to make sure you activate the next reward category.

While Google Wallet / Google Pay exist as options, neither are open source and tie information to your Google account. Many users may be running de-googled operating systems, and would rather have a fully managed offline solution. 

### Security
If you have previously been capturing credit card information using the default camera app, it is strongly advised to delete these photos as other apps could potentially access the media. While Moreover, finding those photos later might be challenging unless you remember to tag them.

CCArmory follows the same standard of security as the [Aegis](https://github.com/beemdevelopment/Aegis) project.

The app has no network access. Information is encrypted at rest. Backups are encrypted.

### Planned Features
* Completely offline - The app has no network permissions to guarantee safety
* Store an unlimited number of full credit card information
* Top level at-a-glance best card to use for certain categories *NOT MVP
* Reminder/Calendar integration for reward cycle periods
* Secure locking/unlocking including convenience options such as Biometrics Unlock following the same standard as [Aegis](https://github.com/beemdevelopment/Aegis)
* Import/Export encrypted backups following the same standard as [Aegis](https://github.com/beemdevelopment/Aegis)
