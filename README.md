# Steam-News-Fetcher
Service for Fetching Games' news on Steam and Sending them trough Webhook to your Discord Server

## Getting Started

### Prerequisites

You'll need to have your webhook URL - If you have no idea what webhook is, check out this [official page about webhooks](https://support.discordapp.com/hc/en-us/articles/228383668-Intro-to-Webhooks)

### First start
Just open [index.html](index.html) and paste in your Webhook URL. Then click Check News. Your news should appear in channel where the webhook is.

`Submitted webhook will be stored in your local storage, so you don't have to copy it everytime you want the news :)`
### Games
If you want to change the games which are covered. Simply put their appID into games array in [index.js](index.js)
> appID can be found in steam store link (store.steampowered.com/app/**413150**) or using third party site like [steamdb](steamdb.info)
