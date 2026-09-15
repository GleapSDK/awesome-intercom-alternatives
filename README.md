# Awesome Intercom Alternatives

A comparison of customer support tools you can use instead of Intercom: help desks and messengers, open source projects, standalone AI agents, and in-app bug reporting widgets.

Every row is checked against the vendor's own pricing and docs pages. If something is wrong or out of date, open a pull request. Corrections are merged quickly.

> Maintained by the team at [Gleap](https://gleap.io). Gleap is on the list, in alphabetical order, with the same yes/no rules as everyone else.

## How to read this list

Three questions decide most of the choice:

1. **Do you need a full help desk or only an AI layer?** The first table lists complete replacements. The AI agent table lists products that sit on top of a help desk you already run.
2. **Where do your customers talk to you?** If they are inside a mobile app, look at the mobile SDK column. WebView embeds and links to a hosted chat page do not count.
3. **What has to arrive with the message?** For SaaS and app teams, a bug report without a screenshot, console log and session replay costs an engineer a round trip. The last table covers tools that capture that context.

Legend: ✅ yes, ❌ no, ➖ not verified.

- **Free plan**: a permanent free hosted plan, not a trial.
- **AI agent**: answers customers from your knowledge base on its own. Rule-based chatbot builders do not count.
- **Mobile SDKs**: native iOS and Android SDKs for the customer-facing chat or widget.
- **Session replay**: a recording of what the customer saw, attached to the conversation or report.
- **Bug reports**: an in-app widget that captures screenshots plus technical context such as console logs, network requests and device data.
- **Flat pricing**: the bill does not grow with agent seats, conversations or resolutions. Tiers with included limits count, per-seat and per-usage meters do not.

## Help desks and messengers

Full replacements for the Intercom inbox, messenger and help center.

Product | Open source | Free plan | AI agent | Mobile SDKs | Session replay | Bug reports | Flat pricing | Pricing model
--- | --- | --- | --- | --- | --- | --- | --- | ---
[Intercom](https://www.intercom.com) (reference) | ❌ | ❌ | ✅ | ✅ | ❌ | ❌ | ❌ | Per seat, plus $0.99 per Fin resolution
[Chaport](https://www.chaport.com) | ❌ | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ | Per seat
[Chatwoot](https://www.chatwoot.com) | ✅ MIT | ✅ | ✅ | ➖ React Native and Flutter only | ❌ | ❌ | ❌ | Per agent, plus AI credits
[Crisp](https://crisp.chat) | ❌ | ✅ | ✅ | ✅ | ❌ | ❌ | ✅ | Flat per workspace, extra seats
[Customerly](https://www.customerly.io) | ❌ | ❌ | ✅ | ✅ | ❌ | ❌ | ❌ | Per seat, plus per AI conversation
[Freshchat](https://www.freshworks.com/live-chat-software/) | ❌ | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | Per agent, plus per AI session
[Front](https://front.com) | ❌ | ❌ | ✅ | ✅ | ❌ | ❌ | ❌ | Per seat, plus per AI resolution
[Gleap](https://gleap.io) | ❌ | ❌ | ✅ | ✅ | ✅ | ✅ | ✅ | Flat per plan with unlimited seats, AI usage billed separately
[Gorgias](https://www.gorgias.com) | ❌ | ❌ | ✅ | ❌ | ❌ | ❌ | ❌ | Per ticket, plus per AI resolution
[Help Scout](https://www.helpscout.com) | ❌ | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | Per seat, plus per AI resolution
[HelpCrunch](https://helpcrunch.com) | ❌ | ❌ | ✅ | ✅ | ❌ | ❌ | ❌ | Per seat, plus AI conversation packs
[HubSpot Service Hub](https://www.hubspot.com/products/service) | ❌ | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | Per seat, plus AI credits
[JivoChat](https://www.jivochat.com) | ❌ | ✅ | ✅ | ✅ | ➖ | ❌ | ❌ | Per seat, AI agent per seat
[Kustomer](https://www.kustomer.com) | ❌ | ❌ | ✅ | ✅ | ❌ | ❌ | ❌ | Per seat or per conversation, plus AI
[Lime Connect](https://connect.lime-technologies.com) (formerly Userlike) | ❌ | ✅ | ✅ | ➖ | ❌ | ❌ | ❌ | Per seat, AI agent add-on
[LiveAgent](https://www.liveagent.com) | ❌ | ❌ | ✅ | ❌ | ❌ | ❌ | ❌ | Per agent
[LiveChat](https://www.livechat.com) | ❌ | ❌ | ✅ | ✅ | ❌ | ❌ | ❌ | Per seat
[Olark](https://www.olark.com) | ❌ | ❌ | ✅ | ❌ | ❌ | ❌ | ❌ | Per seat, AI agent flat fee
[Plain](https://www.plain.com) | ❌ | ❌ | ✅ | ➖ | ❌ | ❌ | ❌ | Per seat, plus AI usage
[Pylon](https://usepylon.com) | ❌ | ❌ | ✅ | ✅ | ❌ | ❌ | ❌ | Per seat, AI agent add-on
[Smartsupp](https://www.smartsupp.com) | ❌ | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | Per seat, AI agent add-on
[tawk.to](https://www.tawk.to) | ❌ | ✅ | ✅ | ❌ | ❌ | ❌ | ✅ | Free core, paid add-ons
[Tidio](https://www.tidio.com) | ❌ | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | Per conversation, plus Lyro AI usage
[Zendesk](https://www.zendesk.com) | ❌ | ❌ | ✅ | ✅ | ❌ | ❌ | ❌ | Per agent, plus per automated resolution
[Zoho SalesIQ](https://www.zoho.com/salesiq/) | ❌ | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ | Per operator

## Flat pricing

Tools where adding a teammate or a busy month does not change the invoice. Useful when support is shared across engineers, product and founders.

Product | What the flat price covers | Where it stops being flat
--- | --- | ---
[Bugasura](https://bugasura.io) | Unlimited users and projects per workspace | Enterprise add-ons
[Chatbase](https://www.chatbase.co) | Workspace tier with included message credits | Extra message credits
[Crisp](https://crisp.chat) | Workspace with included seats and AI credits | Seats beyond the included pack
[Gleap](https://gleap.io) | Unlimited seats and projects, all channels | AI usage is prepaid separately
[tawk.to](https://www.tawk.to) | Chat, ticketing and knowledge base for free | Branding removal and AI Assist add-ons
[Tiledesk](https://tiledesk.com) | Per project with included conversations | AI tokens
[Userback](https://userback.io) | Seats included per plan tier | Feedback project limits per tier
[Ybug](https://ybug.io) | Projects and team members included per tier | Next tier when limits are hit

## Open source

Self-hostable projects. "Hosted plan" means the maintainers sell a hosted version.

Product | License | Hosted plan | AI agent | Mobile SDKs | Notes
--- | --- | --- | --- | --- | ---
[Chaskiq](https://github.com/chaskiq/chaskiq) | AGPL-3.0 with Commons Clause | ❌ | ➖ | ➖ | Paid support plans only
[Chatwoot](https://github.com/chatwoot/chatwoot) | MIT | ✅ | ✅ | React Native, Flutter | Largest community on this list
[FreeScout](https://github.com/freescout-help-desk/freescout) | AGPL-3.0 | ❌ | ➖ | ❌ | Help Scout style shared inbox, paid modules
[Libredesk](https://libredesk.io) | AGPL-3.0 | ❌ | ✅ | ❌ | Single binary, Go
[Papercups](https://github.com/papercups-io/papercups) | MIT | ❌ | ❌ | ❌ | Maintenance mode
[Rocket.Chat](https://www.rocket.chat) | MIT | ✅ | ➖ | ❌ | Team chat first, omnichannel add-on
[Tiledesk](https://github.com/Tiledesk/tiledesk) | MIT | ✅ | ✅ | ✅ | Flat per project, plus AI tokens
[Zammad](https://zammad.com) | AGPL-3.0 | ✅ | ❌ | ❌ | Ticketing first, AI for triage rather than answers

## AI agents on top of your help desk

These answer customers but expect you to keep Zendesk, Intercom, Salesforce or another inbox as the system of record.

Product | Free plan | Pricing model | Notes
--- | --- | --- | ---
[Ada](https://www.ada.cx) | ❌ | Per conversation, sales-led | iOS, Android and React Native SDKs
[Chatbase](https://www.chatbase.co) | ✅ | Flat tiers, plus message credits | Fastest to try, weakest inbox
[Decagon](https://decagon.ai) | ❌ | Per conversation or per resolution, sales-led | Mobile via WebView embed
[Sierra](https://sierra.ai) | ❌ | Per resolution, sales-led | Native mobile SDKs, Apache-2.0

## In-app bug reporting and feedback widgets

For teams whose "support" is mostly bug reports from inside a product. Live chat marks tools where the same widget also carries a two-way conversation.

Product | Free plan | Mobile SDKs | Session replay | Console and network logs | Live chat | Flat pricing | Pricing model
--- | --- | --- | --- | --- | --- | --- | ---
[Bugasura](https://bugasura.io) | ✅ | ❌ | ✅ last 20 s | ✅ | ❌ | ✅ | Flat per workspace
[BugHerd](https://bugherd.com) | ❌ | ❌ | ➖ reporter-recorded video | ❌ | ❌ | ❌ | Per seat
[Gleap](https://gleap.io) | ❌ | ✅ | ✅ | ✅ | ✅ | ✅ | Flat per plan, unlimited seats
[Jam](https://jam.dev) | ✅ | ❌ | ✅ | ✅ | ❌ | ❌ | Per creator seat
[Luciq](https://www.luciq.ai) (formerly Instabug) | ❌ | ✅ | ✅ | ✅ | ✅ | ❌ | Per daily active user, plus seats
[Marker.io](https://marker.io) | ❌ | ❌ | ✅ | ✅ | ❌ | ❌ | Per seat, reporters free
[Shake](https://www.shakebugs.com) | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | Per app, tiered by SDK installs
[Userback](https://userback.io) | ✅ | ✅ | ✅ | ✅ | ❌ | ✅ | Flat per plan
[Usersnap](https://usersnap.com) | ❌ | ✅ | ➖ reporter-recorded video | ✅ | ❌ | ❌ | Per seat
[Ybug](https://ybug.io) | ✅ | ❌ | ✅ | ✅ | ❌ | ✅ | Per project

## Detailed comparisons

Longer write-ups with current list prices, seat rules and workflow differences, written by the Gleap team:

[Intercom](https://gleap.io/alternatives/fairly-priced-alternative-to-intercom) ·
[Zendesk](https://gleap.io/alternatives/alternative-to-zendesk) ·
[Freshdesk](https://gleap.io/alternatives/alternative-to-freshdesk) ·
[Crisp](https://gleap.io/alternatives/alternative-to-crisp) ·
[Front](https://gleap.io/alternatives/alternative-to-front) ·
[Help Scout](https://gleap.io/alternatives/helpscout-alternative) ·
[HelpCrunch](https://gleap.io/alternatives/alternative-to-helpcrunch) ·
[HubSpot](https://gleap.io/alternatives/alternative-to-hubspot) ·
[Gorgias](https://gleap.io/alternatives/alternative-to-gorgias) ·
[Kustomer](https://gleap.io/alternatives/alternative-to-kustomer) ·
[Pylon](https://gleap.io/alternatives/alternative-to-pylon) ·
[tawk.to](https://gleap.io/alternatives/tawk-to-alternative) ·
[Tidio](https://gleap.io/alternatives/tidio-alternative) ·
[Zoho SalesIQ](https://gleap.io/alternatives/alternative-to-zoho-salesiq) ·
[Decagon](https://gleap.io/alternatives/alternative-to-decagon) ·
[Sierra](https://gleap.io/alternatives/alternative-to-sierra) ·
[Instabug](https://gleap.io/alternatives/alternative-to-instabug) ·
[Shake](https://gleap.io/alternatives/alternative-to-shakebugs) ·
[Userback](https://gleap.io/alternatives/alternative-to-userback) ·
[Usersnap](https://gleap.io/alternatives/alternative-to-usersnap) ·
[Marker.io](https://gleap.io/alternatives/alternative-to-marker-io) ·
[BugHerd](https://gleap.io/alternatives/alternative-to-bugherd) ·
[Bugasura](https://gleap.io/alternatives/alternative-to-bugasura) ·
[Jam](https://gleap.io/alternatives/alternative-to-jam) ·
[Ybug](https://gleap.io/alternatives/alternative-to-ybug)

## Contributing

Add a product, fix a cell or update a price. See [CONTRIBUTING.md](CONTRIBUTING.md). Rows stay alphabetical, every change links to a public vendor page, and no product gets a column it does not ship.

## License

[CC0 1.0](LICENSE). Use the data however you like.
