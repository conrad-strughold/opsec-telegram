

# Telegram Security Best Practices — Officer's Blog
source: https://officercia.mirror.xyz/i9-pRa_r9Of1RNf-tnkhJLO9ho3gwhBK-4ARHNFtmvM
In this note, I’ll give you some quick tips that will help you sleep better at night when using Telegram!

> *Photo by [Dimitri Karastelev](https://unsplash.com/@dkfra19?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/photos/EhNLOlxlOXI?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText).*

The lightweight chat client Telegram is one of the most common methods of [communication in crypto](https://medium.com/immunefi/how-not-to-get-hacked-on-telegram-2db2b93a5fa2), and there’s a good reason for that. This app is also frequently used for work and [communication](https://docs.google.com/spreadsheets/d/1-UlA4-tslROBDS9IqHalWVztqZo7uxlCeKPQ-8uoFOU/edit?usp=drivesdk), so it stands to reason that scammers and hackers would also look for victims there.

***Let’s figure out how not to be a victim! Let’s get started!***

---

## Basic Tips

Beware of [impersonators](https://medium.com/immunefi/how-not-to-get-hacked-on-telegram-2db2b93a5fa2) (*carefully check out Telegram bio as the scammer may insert any nickname to his bio and leave his own nickname blank*), fake [notifications](https://medium.com/immunefi/how-not-to-get-hacked-on-telegram-2db2b93a5fa2) about logging into Telegram (*[check](https://hacken.io/discover/top-7-social-engineering-frauds-in-crypto/) out them carefully, they should come into the official [telegram](https://www.androidpolice.com/top-tips-using-telegram-safely-securely/) news & tips channel*) with a phishing link, fake bots (*yep, bots — **not** user accounts — **may DM first***) [and so on](https://twitter.com/officer_cia/status/1569951983271907328?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E1569951983271907328%7Ctwgr%5Eb80f078d6f5711b3dd78b8429b80fc0a99e98d68%7Ctwcon%5Es1_&ref_url=https%3A%2F%2Fofficercia.mirror.xyz%2Fdlf6ZEXq3FLE21ZY2jeJ0cBDyuZu8XIF9DEJAQ07nk8)!

> ***NONE of the telegram chats are E2E encrypted not 1:1, not groups — only TLS. Only the [secret chat](https://www.androidpolice.com/top-tips-using-telegram-safely-securely/) one iirc.***

### Settings:

- Phone Number → Who can see my phone number — Nobody;
- Data and Storage → Auto Download Media → Toggle off;
- Phone Number → Who can find me by my number — My Contacts;
- Last Seen & Online → Who can see my timestamp — Nobody;
- Profile photo → Who can see my profile photo — My Contacts;
- Calls → Who can call me — My Contacts (or Nobody, if you prefer);
- Calls→ Peer-to-peer — My contacts (or Nobody, if you prefer not to share your IP address with chat partners);
- When you start the call, you will see four emojis at the top right corner — ask the person you are calling to name them and compare them to yours (they should be the same as yours). This is protection from MitM;
- Forwarded Messages → Who can add a link to my account when forwarding my messages — My Contacts;
- Never add contacts to Telegram (if there are any — erase them), and always use [VPN](http://officercia.mirror.xyz/x91hTIDFrAL0lgqICRgWU7fLouuCMgvopQ9ZRvRXCLg);
- Groups & Channels → Who can add me — My Contacts;
- Set up a 2FA (cloud password);
- Set up a cloud [email](https://mirror.xyz/0xdc519466f1cda17e8ae6735bB8652F47c0533CBe/n9utNq5mnJ14hscmONhOzBTsTcuWfWMXExummuLti8k) 2FA!;
- More about 2FA [core.telegram.org/api/srp#email-verification](http://core.telegram.org/api/srp#email-verification) & [this](https://telegram.org/faq#q-how-does-2-step-verification-work);
- Disable sticker loop animation! Animated Stickers = danger;
- Disable auto-[downloading](https://www.techbloat.com/stop-auto-download-on-telegram-methods-android-ios-desktop.html) (**both wi-fi and cellular**): Privacy & Security → Data Settings ❗️;
- Disable P2P calls for everyone as it may expose your [IP](https://n0a.pw/telegram-get-remote-ip/)! **Same with secret chats!** End-to-End encryption means that your [IP](https://www.securitylab.ru/news/541831.php) will become known to the person you’re chatting with. [And vice versa](https://mothership.sg/2023/01/circles-life-esim-swap-fraud/);
- Disable link & image previews in secret chats (scroll down in a Privacy and Security section);
- [Disable autoplay GIFs](https://www.csa.gov.sg/singcert/Advisories/ad-2022-013);
- You can now buy Telegram Premium subscriptions (also — [numbers](https://fragment.com/numbers) & [usernames](https://fragment.com/)) with TON: [fragment.com/premium](https://fragment.com/premium);
- [Dutch Police Can Access Hidden Telegram Numbers - Use a burner number!](https://cyberwarzone.com/dutch-police-can-access-hidden-telegram-numbers/)
- Never activate (via **/start**) any [telegram](https://www.cqcore.uk/telegram-osint-vm-part-2/) bot! Do not even touch telegram bots (only public chat bots are considered safe, you can operate them in a public chat via commands), never DM a Telegram bot! (any button can contain a SQLi vulnerability or even worse);
- If you have to open a PDF (CV for example), use [dangerzone.rocks](https://dangerzone.rocks/) or google drive preview regime (ask to upload);
- Watch out active session! [Terminate inactive sessions!](https://innovation-village.com/ncc-warns-a-new-malware-steals-telegram-users-data-without-two-factor-authentication/) Watch out [session stealers](https://www.zdnet.com/article/telegrab-malware-hijacks-telegram-chat-sessions/);
- If you receive a message about logging into your account — **check that it is on a legitimate [telegram](https://www.cqcore.uk/telegram-osint-vm-part-2/) notification & news channel.** Scammers can impersonate this notification channel to force you to give them the OTR code from the SMS;
- Check out [Telegram FAQ](https://telegram.org/faq);
- [To sign in to Telegram, use a different](https://securitypilgrim.com/7-tips-to-make-your-telegram-account-secure/) phone number — or even a virtual phone number — rather than your actual mobile number. However, if you use a one-time number, someone else may [obtain](https://www.androidpolice.com/top-tips-using-telegram-safely-securely/) access to your account. To [conceal](https://securitypilgrim.com/7-tips-to-make-your-telegram-account-secure/) your IP address, use a [VPN](https://securitypilgrim.com/what-is-a-vpn-and-advantages-of-a-vpn/) (which Telegram can provide, for example, at the [request](https://securitypilgrim.com/7-tips-to-make-your-telegram-account-secure/) of law enforcement officials);
- [Check out this list](https://telegra.ph/How-to-configure-Telegram-security-and-privacy-07-21) & follow [Telegram Tips](https://t.me/TelegramTips);
- It is necessary to have a separate secure device with an account-logged in application;
- It is necessary to regularly check the work of the application logged into the account and the chat with service notifications. At least once every five days;
- The more devices logged into the account - the higher the risk of account compromise. Also, a logged-in device is a tool in ensuring the security of a Telegram account;
- [This project describes Telegram limitations!](https://github.com/tginfo/Telegram-Limits) | [Link 2](https://crowdin.com/project/telegram-limits);

**Stay safe!**

---

## It appears that I’ve been banned… So, what should I do?

- Anyone can become a victim of mass-abusing. You should send a letter to [abuse@telegram.org](mailto:abuse@telegram.org) / contact support agent **+42470** (add this phone to contacts);
- But also you [should](https://www.alphr.com/telegram-why-is-my-number-banned/#:~:text=You%20can%20contact%20Telegram%20through%20their%20Twitter%20account%20or%20the%20%40smstelegram%20account%20if%20your%20account%20is%20banned.%20Just%20send%20them%20a%20message%20explaining%20your%20situation%2C%20and%20they%20may%20be%20able%20to%20help%20you.) re-read [FAQ](https://telegram.org/faq#q-what-is-mtproto) section for any information you may be lacking;
- You should also check if it is a temporary (account will be restored after 5 minutes), or permanent ban;
- If it is a permanent ban — unfortunately, there is nothing you can do to recover the account other than creating a new one;
- However, if it is temporary — you should try logging out of all devices and logging in again after the ban period is over;
- You can also try clearing the cache of the app and reinstalling it.

Stay vigilant and secure your Telegram account by following these guidelines and regularly reviewing your settings.

---

## Further Reading

- [Telegram security and privacy settings](https://telegram.org/faq#q-what-is-mtproto)
- [How to stay safe on Telegram](https://medium.com/immunefi/how-not-to-get-hacked-on-telegram-2db2b93a5fa2)
- [Top tips for using Telegram safely and securely](https://www.androidpolice.com/top-tips-using-telegram-safely-securely/)

*Photo by [Dimitri Karastelev](https://unsplash.com/@dkfra19?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/photos/EhNLOlxlOXI?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText).*
