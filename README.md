# Awesome Flex Plugins 🚀

This is a list of Flex Plugins that I have gathered along the way, based on common customers' questions.

It can be used as a first place to take a look before starting building a Plugin as it could be that someone else already has built it.

## Flex Plugins

### Flex Station Selector

- **What is is:** A plugin that changes allows Agents in Flex to receive the calls not on Flex UI but, instead, on his/her own cellphone, for example. It is good for cases when the internet connection of the Agent is not so good. SIP Softphone is also possible.

- **Resources:** [Github repo](https://github.com/jlafer/plugin-station-selector) and [Demo video](https://www.loom.com/share/c441e0e4cb6f4b7696ae46f5dbf5e73a)

- Hashtags for easy finding: `charlie`, `contact_uri`

### Put Agents Offline

- **What is is:** A plugin that puts the Agents offline every day at 21:00. Good for customers based on Per Hour pricing model on Flex, avoiding expenses that run overnight just because an Agent forgot to put himself/herself offline after work.

- **Resources:** [Github repo](https://github.com/bruno222/twilio-flex-plugin-set-agents-to-offline)

### Integration with a custom CRM

- **What is is:** This plugin shows in a primitive way how to embed Flex into any CRM. I used the SAP as a CRM example but there is no element of SAP there, it is purely an example of integration of Flex into any other website and this Plugin can be used as a starting point to integrate Flex into your website.

- **Resources:** [Github repo](https://github.com/bruno222/twilio-flex-sap-c4c-integration)

### Post-call after a bad Survey

- **What is is:** This plugin is an example of how your system can create an outbound call for a Customer, showing some information on the Agent's screen before the call happens. Use-case is when your customer went to your website, bought something, and at the end, there is a survey about the process this customer just faced - for all the bad NPS scores on this survey, you can immediately generate a task for the next available agent to call this customer to know more about the bad experience this customer had, and try to revert this.

- **Resources:** [Github repo](https://github.com/bruno222/twilio-flex-plugin-survey)

## Scripts

### Delete Agents after 30 days of inactivity

- **What is is:** This is a Script that should run every night, looking for Agents who haven't logged into Flex for more than 30 days. Good for customers based on Per Seat pricing model on Flex, avoiding extra expenses for Agents who are not in the company anymore.

- **Resources:** [Github repo](https://github.com/bruno222/twilio-flex-delete-workers-after-x-days)

- Hashtags for easy finding: `sso`, `github actions`
