# Facebook Messenger Bot

A Node.js based Facebook Messenger bot that responds to different types of messages including text, stickers, images, audio, and video.

## Features

- Handles various message types:
  - Text messages
  - Stickers/Reactions
  - Images
  - Audio messages
  - Video messages
- Auto-ping mechanism to keep the application running
- Webhook verification and security
- Built with Express.js and Botly

## Prerequisites

- Node.js
- Facebook Page and App
- Hosting platform (e.g. Render)

## Environment Variables

The following environment variables are required:

```env
PAGE_ACCESS_TOKEN=your_page_access_token // EAAxxx....
VERIFY_TOKEN=your_verify_token // ABCD
APP_SECRET=your_app_secret