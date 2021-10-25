# [u/profanitycounter](https://www.redit.com/u/profanitycounter) public repo

## Why the new repo?

Working on version 4 of profanitycounter, I was getting tired of the existing codebase. Although I was proud of my work up until the point, the code was just messy. Adding new functionality to the bot was a pain, and cause me to change 3 or 4 lines of code for every new one I added. Tired of wasting my time, I decided to create a new public repo that was clean of the errors of the past. I had wanted to make the code public again, after a long time of it being private, so this is where we are. 


## Contents
* [Description](#description)
* [Usage](#usage)


# Description

[u/profanitycounter](https://www.redit.com/u/profanitycounter`) started as a fun personal project sprung out of sheer boredom. I wanted to solidify my understand of Python at the time, and I thought making this ~~monstosity~~ bot would be a fun thing to do. Lo and behold, over two years later profanitycounter is chugging along just fine, and has become an incredibly popular tool among the Reddit community. 

What the bot does? Well, profanitycounter provides automatic profanity reports to any user, about any user. A simple concept to say the least.


# Usage

Using the bot is as simple as summoning it in a reply to any public post or comment. Note that the bot cannot "see" its summons in communities that are private and that my bot is not a member of. If the bot is banned or restricted in a communtiy it *can* see its summons in, it will send you a private message with the report you requested. 

Current, profanitycounter supports a few modifiers:
* `u/profanitycounter [self]` will check your own profanity no matter where you summon it. 
* `u/profanitycounter [u/<username>]` will check the profanity of the user with the username \<username>.
* `u/profanitycounter [r/<subredditname>]` will check the profanity of the subreddit with the name \<subredditname>.
* `u/profanitycounter [botstats]` will give you some information about the bot itself, like up time and total profanity counter.

These modifiers are bound to change when version 4 releases, so make sure you check back here when it does.