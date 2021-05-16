# Zendesk Guide Subscriber with Github Actions

The GitHub Actions for subscribing Zendesk Guide articles to notify updates to Slack.

With ease:

- Get a list of updated Guide articles every 60 mins by Github Actions
- Push the list to Slack

## Get Started

1. Fork this repository to your repository
2. Register the following required actions secrets in your folked repo

NOTE: An initial run may be failed because this action require a previou action execution time to get a diff

## Required Actions Secrets

Register

- `SLACK_WEBHOOK`: Create your Incoming Webhook with creating a new app from https://api.slack.com/apps
- `ZENDESK_EMAIL`: Your Zendesk Email for the api access. 
- `ZENDESK_SUBDOMAIN`: Your Zendesk Subdomain. Ex. https://<ZENDESK_SUBDOMAIN>.zendesk.com/
- `ZENDESK_TOKEN`: Zendesk API Token to be used for pulling Zendesk Guide Article.  See [this article](https://support.zendesk.com/hc/en-us/articles/226022787-Generating-a-new-API-token-) to generate.

## Output Example

![](https://t.gyazo.com/teams/treasure-data/0b0a86bd04ef2885744b65758d87adbe.png)
