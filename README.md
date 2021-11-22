
# Aerex Bot Privacy Policy
*Last Updated: 11/22/2021*

> **⚠️ Privacy Policy Refactor ⚠️**
> We have re-worded our data collection sections to make them clearer to the end user. Nothing new has been added and this policy covers the same materials as it did before.

## Introduction:
Welcome to Aerex's privacy policy! In this policy, we will go over what data the bot collects, how data is retained in our systems, how we get rid of our data, and how you can request data removal. If you have any questions, please [join our Discord server](https://discord.gg/BYuUvE4) and we'll be glad to help you out.

## Data Access:
Before we begin discussing data collection, it's important to note that very few Aerex staff members have access to your data. Only bot administrators and bot owners can view this material and all data we collect is encrypted and protected via forms of authentication. In order for a bot administrator to access your data in particular, they must log into a dedicated data server with an approved username and password, and authenticate themselves with a form of two-factor authentication (2FA). For more sensitive data, this is locked on a physical server (in encrypted form) which requires a 2FA key to access. We regularly purge data as well, which will be covered later in this document.

## Data Collection:
* **User and Server IDs:** This information helps us determine if you or your server is blacklisted as well as checking if you or your server have been flagged by our antispam, which will not allow the command you requested to be executed. We only store blacklisted user and/or server IDs. Antispam information is automatically removed after the ratelimit is completed, but blacklist information cannot be removed unless you appeal successfully.
* **Message Content:** Message content is collected when you delete a message for both modlogs (if the server has it set up) as well as our `snipe` command (which allows the retrieval of deleted messages). The `snipe` command automatically censors personal identifiable information (email addresses, phone numbers, Discord tokens, etc.) and you can opt-out of the `snipe` system. `snipe` messages are also regularly purged every other hour. However, you cannot opt-out of being logged by the modlog function set up by your server as this option was set up by your server administrator. Please speak with your server administrator if you do not feel comfortable with a message modlog system. Message content is also collected when performing the toxicity scanning command (for server moderators only) and the content is only used in comparison to a toxicity ML model. Personal identifiable information is filtered out when being compared to the ML model and the data is immediately deleted after the comparison is complete. 
* **Webhook & Channel IDs:** This data is only collected when you create a global chat, a modlog for your server, or enable the welcome message setting. Both webhook & channel IDs will automatically be deleted if you opt-out and/or delete your modlog/global chat/welcome message.

## Data Purges:
Data purges are periodic automatic removals of your data from our systems. Every month, we remove all stored channel and webhook IDs stored by us and re-fetch them from Discord. We also purge all stored `snipe` content every other hour (every two hours). 

## Data Removal Request:
As stated earlier, you may remove your data by filling out one or more of the forms below. Upon filling out this form, you can expect you or your server's data to be removed within 14 days. The bot may leave your server (if you are requesting server data deletion) and/or may be inaccessible to you if you choose to do so.

**Removal Request Forms:**
* [Snipe Opt-Out Form](https://forms.gle/rJKRvJJ43bkofStd6)
* [Total Data Removal Form](https://forms.gle/rJKRvJJ43bkofStd6)

**Data we remove:**
* `Snipe` command messages
* Your server's stored tags
* Your server's stored games
* Your server's stored items in queue
* Your stored calculations from the `calculate` command
* Your `quartett` command data
* Your `quiz` command results
* Your server's premium status

**Data we will not remove:**
* You or your server's blacklist status
* You or your server's antispam status
* Any stored internal infractions against you or your server

We will not be removing you or your server's blacklist or antispam status for the sole purpose of bot security. You can expect your data to be fully removed within 14 days.

## Assistance:
If you would like clarification or assistance on certain matters, please feel free to [join our support server](https://discord.gg/BYuUvE4). We will be more than happy to help you.

## Policy Updates:
As we add and remove certain features, this privacy policy is guaranteed to be updated at times. For larger updates, we will most likely notify you through our [support server](https://discord.gg/BYuUvE4) (in our #announcements channel), but it is mainly your responsibility to keep checking back on this policy to see if it updates. We will be posting a "last updated" date to show that we updated our policy. For larger updates, we will be posting a notice at the top of this policy stating the larger changes we have made.
