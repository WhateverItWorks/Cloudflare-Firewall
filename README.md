### Cloudflare-Firewall

A look into protecting your website with Cloudflare Free Plan

## Firewall Rules: 

Rule Name | File Name | Action | What For
---- | ---- | ---- | ----
General | [rules.ssl](./rules.ssl) | Manually Add | Peformance, User Experience, DDOS Protection, Crawlers<br>
Common Countries | [common-country.rules](./common-country.rules) | Block | Only Allow Country's Who Wont Pass Much Malicous Traffic.<br>
Bad ASN List | [bad-asn.rules](./bad-asn.rules) | Block | Bad ASN List Of Most Known Proxyscraping Sites.<br>
Threat Score | [threatscore.rules](./threatscore.rules) | Block | Block Bad Threats Flagged By Cloudflare<br>
Request Method | [request-method.rules](./request-method.rules) | Block | Block POST & HEAD Request's Only Allow GET Request's Unless Needed.<br>
Block Bots | [blockbots.rules](./blockbots.rules) | Block | Block Bots that won't be in your firewall manager.
Block Bad Bots | [badbots.rules](./badbots.rules) | Block | Block bad bots.
Wordpress Security | [wordpresssecurity.rules](./wordpresssecurity.rules) | Captcha | People that is not from the united states will do a captcha.

## Examples: 
![](https://media.discordapp.net/attachments/819747919581675530/829677841292460042/unknown.png) 
![](https://media.discordapp.net/attachments/819747919581675530/829678093706592276/unknown.png) 
![](https://media.discordapp.net/attachments/819747919581675530/829678478278000650/unknown.png) 
![](https://media.discordapp.net/attachments/819747919581675530/829678903131897906/unknown.png) 

## Wayback Machine

- > https://www.google.com/search?q=wayback+machine+alternative (Look for ways to block these sites, But the main ones that people use is archive.org, archive.is, archive.fo, archive.today, and archive.ph. That means that the cyber stalkers are mainly kids or people that want to pay and give up their personal information to paid archive sites which are lawful and probably has bots as well which can be blocked...)

## Update Bad ASN List:

> To update the [bad-asn.rules](./bad-asn.rules), Go to [bad asn list](https://github.com/brianhama/bad-asn-list/blob/master/bad-asn-list.csv). This list may be 4 years old, But some still works and it is a huge list. There may be some other huge list, Just do your own research.



### Rules

-   [Allow rules](https://github.com/xbdmhq/cloudflare-firewall/tree/main/allow-rules)
-   [Block rules](https://github.com/xbdmhq/cloudflare-firewall/tree/main/block-rules)
-   [Challenge Captcha rules](https://github.com/xbdmhq/cloudflare-firewall/tree/main/challenge-captcha-rules)
-   [Challenge JS rules](https://github.com/xbdmhq/cloudflare-firewall/tree/main/challenge-js-rules)
