# GoPhish Templates

This repository includes several GoPhish templates that I have utilized for various engagements and now retired.

When learning how to setup and use GoPhish I found that there was a lack of publicly available templates and landing pages. This repository is my attempt to give back to the InfoSec community by providing examples that I've used for generic phishing engagements. 

## Clicking = Fail & Other Thoughts
When launching a campaign with GoPhish my goal is to always try and obtain credentials from the user. While attacks can be executed from a user clicking a link (looking at you BeEF), 9/10 when I'm on a penetration test, credentials are what I am hoping for since dropping malware often isn't in scope. These campaigns are best paired with a good landing page or malicious download. 

I highly recommend you tailor these pretexts and landing pages to your client. That means you should clone a login portal from their external environment or create a convincing template relative to ongoing events to be used throughout more sophisticated campaigns. Remember, we potentially only need to win once to go masterhacker mode.

However, I do want to state that users who click an email still provide me with some interesting information:
1. The email address is valid.
2. I know that the user has received the email and it has bypassed any protections in place.
2. I know that the user is active and can be targeted in additional campaigns. 

## GoPhish 
Gophish is a powerful, open-source phishing framework. [GoPhish](https://getgophish.com) is avaialble for free.
