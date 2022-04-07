# GoPhish Templates

This repository includes several GoPhish templates that I have utilized throughout various engagements and retired from use. 

When learning how to setup and use GoPhish I found that there was a lack of publicly available phishing templates and landing pages. This repository is my go to give back to the InfoSec community and provide examples of templates that I've used throughout generic phishing engagements. 

## Clicking = Fail & Other Thoughts
When launching a campaign with GoPhish my goal is to always try and obtain credentials from the user. While attacks can be executed from a user clicking an email (looking at you BeEF), 9/10 when I'm on a penetration test, credentials are what I am hoping for. These campaigns are best paired with a good landing page or document. 

I highly recommend when tailoring these pretexts and landing pages to your client. That means you should definitely clone a login portal from their website or create a convincing landing page. Remember, we potentially only need to land one successful phish to go crazy.

However, I do want to state that users who click an email still provide me with some interesting information:
1. The email address is valid.
2. I know that the user has received the email and it has bypassed any protections in place.
2. I know that the user is active and can be targeted in additional campaigns. 

## GoPhish 
Gophish is a powerful, open-source phishing framework. [GoPhish](https://getgophish.com) is avaialble for free.
