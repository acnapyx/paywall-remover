Paywall Remover
=======
> A proof of concept that no media paywall is impenetrable, and some of the existing content protection solutions are hopelessly inadequate.



## Project Overview
Quite a few media companies put some kind of paywall, or requirement to register to access content, or any form of "Disable Adblock" nag that is destined to persuade you that you need to support their web projects by allowing ads or, in worse cases, allow crypto miners. The problem is that most of those are simply JavaScript pop-up added to the website, while the underlying content is public. 

Most of those solutions are insecure and can be circumvented by filtering or disabling scripts that check for Adblock and/or incognito browsing and trigger on certain events. I'm not sure if those media owners really understand what's going on with their content and they **assume** it's securely protected.

In an effort to demonstrate the state of some of these apps simply subscribe to the list below using AdBlock.



## Subscribing to the List
Copy the subscription link, `https://raw.githubusercontent.com/acnapyx/paywall-remover/master/paywall-remover-list.txt`, into your AdBlock browser plugin options. You're done.


### How It Works
The text file in this project contains a curated list of filters for some of paywall apps I've seen. When you subscribe to the list, the filters are added to your AdBlock settings. As long as the you're subscribed to the list, you'll be blocking the pop-up overlays from appearing, exposing the content underneath.


### Blocked Apps
* Piano(Tinypass)
* SentryLogin
* MyMemberspace
* MembershipWorks
* Wired.com
* Salon.com
* BusinessInsider
* Boston Globe
* MIT Technology Review
* Webcafe.bg


### Disclaimer
This project isn't aimed at promoting content theft by any means. It's promoting the idea of making the web a more secure place, forcing developers to think of better solutions to protect users, and calling out companies that are misrepresenting products and solutions for content protection.

### Contribute
Submit new apps and filters as [issues](/issues).
