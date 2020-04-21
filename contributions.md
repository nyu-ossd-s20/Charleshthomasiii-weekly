---
layout: page
title: My Open Source Contributions
permalink: /contributions/
---

<!--
Type of the contribution should be "Wikipedia edit", "OpenStreet Map feature", "Documentation", "Course website", "Blog",
"Browse Add-on", etc.

The description should include a brief summary of what you did.

Replace the first row with your own contribution. 

-->





 | 3 Feb 2020 |
|---|
 |https://github.com/dessalines/lemmy/issues/501  |  
 | Dev environment setup clarification   | 
 | Local development does not require a proxy server (Nginx) for most usage. The pictshare server and lemmy server must be hosted on different ports. Without Nginx as a proxy, all http requests to pictshare fail. After discovering this, the README.md was updated to explain this requisite.|
 
  | Mar 2020 |
|---|
 | WireGuard Related Developments 1/2| 
 | Attempting and failing to implement a WireGuard (open source project) server has yielded two interesting results. The first result is that my router blocks port forwarding on 51820. While inconsequential to the implementation of WireGuard, (I just used a different port), it's a massive breach of trust, user rights, and ownership. After spending countless hours researching this problem, I have some direct evidence (and mountains of circumstantial evidence) that comcast is blocking it. There are few places that I can make an impact with this information, but I made a (well-received) post on the WireGuard subreddit detailing the problem.|
 
 | Mar 2020 |
|---|
 | WireGuard Related Developments 2/2| 
 | The second WireGuard related development has to do with setting up the server. There is a CLI suite that allows the user to quickly spin up a server using wg-quick commands. Within the script there was a field hard-coded for the port number, https://manpages.debian.org/unstable/wireguard-tools/wg-quick.8.en.html . This is problematic for usage because each user should not be expected to change the hardcoded value in the bash script if needed, but instead edit the config file. After reaching out to the maintainers, I discovered I was incorrect about an assumption I had made about the bash script. Nevertheless, the assumption was an easy one to make, and a maintainer agreed that further clarification was warranted.|
 
| Apr 2020 |
|---|
| https://github.com/LemmyNet/lemmy/issues/625|
 | Lemmy Coding Technical Debt| 
 | Our group spent significant time researching an issue related to restructuring large portions of code. After much discussion, we asked the developers for clarification on how to proceed. We were advised to not attempt to fix the issue at this point in time for unrelated reasons. While we made no direct contribution (other than public discussion), we learned a significant amount about how the code itself is structured. (API endpoints, idiomatic rust, proper module scope, rust struct structure)|
 
| Apr 2020 |
|---|
|https://github.com/LemmyNet/lemmy/pull/640|
 | Unit Testing Dependency| 
 |After attempting to run a script that executed a number of united tests, we discovered that there was a required dependency called ab - Apache HTTP server benchmarking tool. I made a quick fix in the bash script that checked if it was there before executing commands, and if not then alerts the user. The pull request was quickly merged. |

