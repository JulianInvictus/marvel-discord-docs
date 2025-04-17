---
sidebar_position: 2
sidebar_label: Onboarding
---

# Onboarding
Onboarding is a tool released by Discord in March 2023 to give servers the tools to allow users to pick their own roles and channels that they want to see, by answering questions. A very powerful tool, Onboarding is customarily linked in text chat by typing `<id:customize>`. Users can either be prompted to answer questions *before* joining the server (as an unavoidable pop-up) or after joining by navigating to `"Channels & Roles"` at the top of their channel sidebar. 

At any time while being a member of the server, a user can change their answers to the questions posed, and hide/show certain channels they have access to.

## Managing Onboarding
Onboarding is a remarkably powerful asset for administrators. It can effectively replace reaction-roles, or other channel-based role systems, almost entirely[^1]. While this guide will seek to be semi-comprehensive, a suscinct FAQ is written on Discord.com regarding the use of Onboarding [here](https://support.discord.com/hc/en-us/articles/11074987197975-Community-Onboarding-FAQ). 
The three most important details are:
  1) '[Community](https://support.discord.com/hc/en-us/articles/360047132851-Enabling-Your-Community-Server)' **must** be enabled to use Onboarding;
  2) There are three modules of Onboarding management: Default Channels, Questions, and Server Guide.
  3) Some changes to Onboarding setups do **not** effect users that have already gone through the initial join process. Notably, changing 'default channels' will not change them for users already in the server.

### Default Channels
Default Channels are effectively channels that will be enabled and in-view of users who join the server for the first time. For a channel to be allowed to be a 'default channel' it **must** be accessible (read & write) by @everyone.[^2] To utilize Onboarding you __must__ have at least 7 Default Channels.

### Questions
There are two types of questions in Onboarding: pre-join and post-join[^3]. Pre-join questions have largely been seen as containing the most important questions for a user joining a server--they help guide a users experience and often can give them access to topic-specific channels that they would want to know exist. Another valuable question to include in the pre-join category involves ping-roles; asking users if they want to opt-in (or opt-out) of certain ping roles (e.g. "server news", "event ping", "polls", etc.) enables them to make choices about how they want to interact with the server prior to joining it.

Post-join questions encompass everything else! Some servers like to utilize pronoun roles, interest roles, or other personal information (favorite [x], region of residence, etc.) as post-join questions to give users the opportunity to further customize the way they present themselves on the server. 

Best practice is to use pre-join questions as the category of questions that will shape the way the *user* interacts with the server, and post-join questions to shape the way the *server* interacts with the user[^4]

### Server Guide
Server Guide is colloquiolly the forgotten child of Onboarding. [Here](https://support.discord.com/hc/en-us/articles/13497665141655-Server-Guide-FAQ) is the Discord-written FAQ on Server Guides. Server Guide is intended to be, literally, the guidepost for which users (new and old) can reference at any moment. It is permanently visable when activated to all users, and can only be hidden by deactivating it. It is not required to be activated when Onboarding is enabled, but can be toggled on/off without effecting the rest of Onboarding.

TODO https://discord.com/channels/281648235557421056/1330728006670352444

[^1]: There is a maximum number of answers a single question can have, and therefore some servers choose to not utilize onboarding if they have a question with more than 50 possible answers.
[^2]: Default channels can be *disallowed* for users with a role. E.g. I can disallow users from seeing [x] default channel after they have a certain role.
[^3]: Pre-join questions are still visable via `"Channels & Roles"` after joining the server.
[^4]: Subject to change.
