# Facebook & LinkedIn Autopost

Automatically publish media to Facebook and images to LinkedIn, with a Telegram notification when a Facebook post is published.

## Features

- Publish photos and videos to Facebook.
- Publish images to LinkedIn.
- Receive a Telegram notification after a Facebook photo or video post is published.

## How to use

1. Configure the app with the credentials and permissions it needs to access your Facebook Page, LinkedIn account, and Telegram bot/chat. Keep credentials private; do not commit them to the repository.
2. Choose the platform you want to post to.
3. Select your media:
   - **Facebook:** choose a photo or video.
   - **LinkedIn:** choose an image.
4. Add any post text or caption supported by the app, then submit the post.
5. After a Facebook post is published, check your configured Telegram chat for the notification.

## Requirements and setup

You will need accounts on the platforms you want to use, authorization for the relevant Facebook and LinkedIn publishing features, and a Telegram bot and destination chat for notifications.

**Setup commands and configuration names are not documented yet.** The repository currently contains only this README, so it does not include application code, installation instructions, or an example configuration. Add those details here as the app implementation is added; until then, the workflow above describes the intended use rather than a runnable setup.

## Security

- Store access tokens and other secrets in environment variables or a private secrets manager.
- Never share or commit access tokens, bot tokens, or private credentials.
- Grant only the permissions the app needs, and revoke credentials you no longer use.
