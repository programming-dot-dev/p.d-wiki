# Automation Guidelines
These are guidelines to follow when using any form of automation on an account hosted on Programming.Dev ("programming.dev", "we", "us", "our") sites or in communities hosted on the site from federated instances. When using automation within communities on other instances make sure to follow their specific guidelines in addition to these if they exist.

Failure to follow these guidelines may result in the account using the automation being banned from the instance.

> Guidelines marked with (C) can be overriden by community mods while ones marked with (A) can be overriden by a instance admin if they give permission to you.

## 1. General Guidelines
This are guidelines that aren't specific to one form of automation and should be followed regardless of the type of automation you are doing.

### 1.1. Use Mentions as a Prefix
If the automation includes the usage of commands such as help, contact, remindme, generate, etc. it should use the mention of the account as the prefix as opposed to something such as ! or ?. This allows multiple automations to use the same commands without interfering with each other and ensures people are using the one they intended to use.

### 1.2. No Trigger Overlap (C)
Do not make triggers fill the same niche as an already established one in the community you are posting in. For example if theres already a tldr bot posting tldrs for news posts there doesn't need to be a second one in the comments. (Can be overriden by the community mods)

### 1.3. No Vote Manupulation
Automation should not be used to affect the voting system in the instance. The vote it will automatically do on the accounts own posts are fine but it should not be used to automatically vote on other people's posts or comments.

## 2. Bots
These guidelines are specific to bot usage. This means accounts that exist solely to be automated to do things (tldr bot, remindme bot, reply bots, etc.) or that do specific things without any form of human intervention in the chain

> Examples of things in this category:
> - Automatically posting things from an rss feed
> - Automatically generating tldrs of articles posted to a community
> - Automatically posting a link to an alternate frontend for a site when theres a link to the site

### 2.1. Mark Bots as Bots
Bot accounts should be marked that they are a bot using the checkbox in the user settings

### 2.2. Put Contact Info
The owner of the bot and some way to contact them must be in the bot’s bio

### 2.3. Don't Spam (A)
Bots should not spam posts or comments. Automatically making posts or comments is fine but it should not drown out non automation content. When looking at the last 20 posts in a community, at least 75% should be human created (your specific bot should take less than the 25% for bots since other bots exist to share that with). There are some cases where having a community with mostly or only bot content makes sense (e.g. daily programming quotes, a challenge community that auto posts daily challenges from another site) and in that case you should reach out to an instance admin to get it approved (and you should be one of the mods for that community). When admin approved it still should not drown out human posts in the local feed in the instance.

### 2.4. Allow Mods to Opt In (A)
Before using a bot in a community allow the mod to opt in to the bots.

If a bot is deemed to be a well behaving bot that brings net good to the instance it can override this rule as long as it has been approved by an admin. If this happens mods should still be able to opt out of use of your bot.

## 3. Tools
These guidelines are for tool usage for semi-automated actions or things that don't affect other users.

> [!note] 
> Examples of things in this category:
> - Scheduling posts
> - Monthly/Weekly repeated thread posts in a community
> - Auto marking posts with certain keywords as read for you (this one is more automated but only affects your own account)

### 3.1. Mark That You Use Automation
As some software doesn't have this built in currently you can just put the information in your bio. This could be something such as "Some actions in this account are automated", "Cyborg account", or "Uses some automation tools". You could also put what specific things you use if you want but it is not required. If the software supports marking an account as a cyborg you can use that instead.

## Do we Make Updates to these Automation Guidelines?
We may update the Automation Guidelines from time to time. When we do the date at the bottom of the page will change to indicate the date of the most recent changes. In addition, clicking on that date will bring you to the commit in the code repository that shows who edited it, and what was changed. If we make changes we may notify you by posting a notice of such changes in our meta community on the programming.dev site, in the updates account on the bytes.programming.dev site, in the news community in our discord server, and in the news community in our matrix server. We encourage you to review the Automation Guidelines periodically for any modifications.

## Contact Us
If you have questions or concerns about these Automation Guidelines you should contact us at info@programming.dev.

