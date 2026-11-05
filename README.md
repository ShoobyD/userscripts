# userscripts

Personal userscripts for [Tampermonkey](https://www.tampermonkey.net/) / [Greasemonkey](https://www.greasespot.net/) that tweak and automate various sites.

## Scripts

| Script | Site(s) | What it does |
| --- | --- | --- |
| [BlenderFilter.js](BlenderFilter.js) | blender.co.il | Range-slider filters (duration, price, rate) for the loan market table. *Currently disabled.* |
| [BypassAdblockRedirect.js](BypassAdblockRedirect.js) | themarker.com, globes.co.il | Bypasses the redirect triggered when an adblocker is detected. |
| [Duolingo.js](Duolingo.js) | duolingo.com | Auto-practice: reads the session data and answers challenges automatically. |
| [Facebook-CloseBtn.js](Facebook-CloseBtn.js) | facebook.com (groups, events) | Adds a × button to each feed post to hide it. |
| [Gmail-Agora.js](Gmail-Agora.js) | mail.google.com, agora.co.il | Keyboard shortcuts for going through Agora notification mails (`0` random mail, `1` open item, `2` delete), and auto-closes unavailable items. |
| [Meetup_Filter.js](Meetup_Filter.js) | meetup.com | Filters events on the Find Events page by a group blacklist. |
| [Meetup_Filter_blacklist.html](Meetup_Filter_blacklist.html) | — | Helper page that uploads the blacklist used by `Meetup_Filter.js`. |
| [MobileRedirect.js](MobileRedirect.js) | Wikipedia, Facebook, 9GAG, AliExpress, and more | Redirects mobile / AMP pages to the desktop version. |
| [MyLink_Bypass.js](MyLink_Bypass.js) | KickassTorrents mirrors | Unwraps `mylink` redirect links into direct links. |
| [ShittySites.js](ShittySites.js) | loveroms.com | Blocks annoying site behavior. |
| [SivanCensored.js](SivanCensored.js) | web.whatsapp.com | Just for fun: censors the name "סיוון" in WhatsApp Web messages. |
| [Vimeo_Downloaer.js](Vimeo_Downloaer.js) | player.vimeo.com | Adds a download button (video + captions) to the Vimeo player. |
| [VueMastery_DownloadBtn.js](VueMastery_DownloadBtn.js) | vuemastery.com | Adds a "Download Video" button to lessons (1080p). |
| [WhatsApp_DeleteBtn.js](WhatsApp_DeleteBtn.js) | web.whatsapp.com | Quick delete button for messages. *Work in progress.* |
| [Zap-SliderFilter.js](Zap-SliderFilter.js) | zap.co.il | Adds a range slider to numeric multiple-choice filters. |

## Installation

1. Install [Tampermonkey](https://www.tampermonkey.net/) (or another userscript manager).
2. Open the script you want, copy its contents, and paste it into a new script in the manager's dashboard.

Some scripts load helpers via `@require` from [shoobyd.github.io](https://shoobyd.github.io/) (`shoobyd.js`, `mutation-summary.js`).

## Disclaimer

These are personal scripts. Sites change their markup often, so some scripts may no longer work.
