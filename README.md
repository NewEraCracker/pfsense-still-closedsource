# pfsense-closedsource
The only purpose of this repository is to document the false advertising of the so-called "open-source" pfSense®™ project. Brought to you courtesy of Netgate/Rubicon Communications LLC/ Electric Sheep Fencing LLC.

In case someone naively thinks that https://github.com/pfsense/FreeBSD-src contains the pfSense®™ source code - that is not the case. You cannot build pfSense®™ 2.4.x from source code. No, not even with the [official tools](https://github.com/pfsense/pfsense/tree/master/tools) - those will just sabotage you. The repository claimed to be "FreeBSD src with pfSense changes" does not contain the source code of the kernel shipped with pfSense®™ 2.4.x, and other changes done to FreeBSD code are also being selectively ommited from that repository.

Of course, such details cannot stop Netgate from plastering their websites and every single piece of their marketing material with "open source":
***
![False advertising](https://github.com/doktornotor/pfsense-closedsource/blob/master/screenshot_pfsense_org_website_01.png)
***

Open-source labeling of course helps even when you are in business of [selling overpriced networking gear](https://store.netgate.com/):
***
![False advertising helps to sell overpriced gear, too..](https://github.com/doktornotor/pfsense-closedsource/blob/master/screenshot_netgate_store_oss.png)
***


Not providing the source code for the actual product naturally cannot stop Netgate from falsely advertising that ["those who wish to review the source code in full detail, the changes are all publicly available on GitHub"](https://www.netgate.com/blog/pfsense-2-4-1-release-now-available.html) in their release notes either:
***
![BS release notes](https://github.com/doktornotor/pfsense-closedsource/blob/master/screenshot_relnotes_241.png)
***

__No, you cannot review the source code in full__. But of course when you put enough open-source claims on your website, [there is no need to provide the source code](https://forum.pfsense.org/index.php?topic=138822.msg759561#msg759561), so do not bother with requesting it.

If you don't follow the above advice, Netgate's CEO will eventually [accuse you](https://forum.pfsense.org/index.php?topic=137636.msg754001#msg754001) of being [OPNsense](https://opnsense.org/)/[Franco's](https://github.com/fichtner) agent. Even [if you have nothing in common](https://forum.pfsense.org/index.php?topic=138822.msg758739#msg758739) with [OPNsense project](https://github.com/opnsense) in fact contributed thousands of commits to pfSense®™, even if you are not competing with pfSense®™/Netgate at all, even if you are not in business of selling routers/firewalls, you still are the prime suspect, being accused of trying to [gain advantage](https://forum.pfsense.org/index.php?topic=138804.msg759343#msg759343). __Paranoia is a serious mental disorder.__

While Mr. Thompson is soooo full of his pfSense®™ intellectual property and trademarks that he does not hesitate to claim any usage of "pf" or "sense" in combination with whatever else to be infringing - see [Can I sell pfSense](https://doc.pfsense.org/index.php/Can_I_sell_pfSense) [(PDF)](https://github.com/doktornotor/pfsense-closedsource/blob/master/Can%20I%20sell%20pfSense%20-%20PFSenseDocs.pdf) - or trying to teach people how to use English - see [pfSense Trademark Usage Guidelines](https://www.pfsense.org/trademarks.html) [(PDF)](https://github.com/doktornotor/pfsense-closedsource/blob/master/pfSense%20Trademark%20Usage%20Guidelines.pdf) - this is his take on other people's IP:

***
![Lets recycle the LEGO idea...](https://github.com/doktornotor/pfsense-closedsource/blob/master/Gonzo%20(a.k.a.%20SmallWorks)%20recycles%20the%20LEGO%20idea%2001.png)
***

Shockingly, LEGO decided to [sue gonzo's ass](https://dockets.justia.com/docket/connecticut/ctdce/3:2015cv00823/108470) (also see [PDF1](https://github.com/doktornotor/pfsense-closedsource/blob/master/Lego%20vs.%20Rubicon%20Communications%20-%2001.pdf), [PDF2](https://github.com/doktornotor/pfsense-closedsource/blob/master/Lego%20vs.%20Rubicon%20Communications%20-%2002.pdf)). Ooops...

### The older I get, the less patience for bullshit I have. Dear [@Jim Thompson](https://twitter.com/gonzopancho):
***
![Message for Jim...](https://github.com/doktornotor/pfsense-closedsource/blob/master/allergic-to-your-bullshit.png)
***

I have closed all my remaining [pull](https://github.com/pfsense/FreeBSD-ports/pulls?utf8=%E2%9C%93&q=is%3Apr%20is%3Aclosed%20author%3Adoktornotor%20) [requests](https://github.com/pfsense/pfsense/pulls?utf8=%E2%9C%93&q=is%3Apr%20is%3Aclosed%20author%3Adoktornotor%20) - definitely to gain the advantage of no longer contributing to a project that keeps lying to its users and customers. Oh, and thanks for locking my [issue tracker](https://redmine.pfsense.org/projects/pfsense/) account. I only reported couple hundreds of issues, many of them with PRs to fix the bugs. Not a big deal either.

P.S. A final advise, Jim. Reading [the FTC's advertising guideliness](https://www.ftc.gov/tips-advice/business-center/guidance/advertising-faqs-guide-small-business) and actually following them might spare you quite a bit of trouble in future. [False/misleading advertising is illegal.](https://www.ftc.gov/news-events/media-resources/truth-advertising)

In case people still decide to buy products from Netgate - kindly do yourself a favor and download the factory firmware image within the first year and keep it somewhere safe. If you need to reinstall the firmware, their "unencumbered by traditional annual contracts" claims won't exactly help you with that task:

***
![No annual licensing fees...](https://github.com/doktornotor/pfsense-closedsource/blob/master/screenshot_no_annual_licensing_fees.png)
![... except if you need to reinstall.](https://github.com/doktornotor/pfsense-closedsource/blob/master/screenshot_no_annual_licensing_fees_orly.png)
***
