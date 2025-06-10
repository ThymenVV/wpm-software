# Social Media Scheduler

This repository will house the code for a social media scheduling tool. The application aims to let users manage multiple social media accounts in a single dashboard, schedule posts across platforms, and receive analytics reports each month.

## Planned Features

- **Supported Platforms**: Facebook, X (Twitter), LinkedIn, Instagram, TikTok, and any other platform that offers API access via OAuth.
- **Authentication**: Users can create accounts with email/password or use Google, Microsoft, or Apple sign‑in.
- **Roles**:
  - **Admin**: Full access to manage all users, configure branding, and view analytics.
  - **Manager**: Add and manage client accounts, schedule posts, and view analytics.
  - **Client**: Approve scheduled content and view reports.
- **Scheduling & Posting**: Cross‑platform content calendar with options to post immediately or schedule for later. Posts may include text, images, or video depending on the platform.
- **Analytics**: Monthly email reports with engagement metrics. Users will be able to customize which metrics appear in these reports.
- **White‑label Branding**: Configure custom colors, logos, and email templates so the tool appears under your own brand.
- **Notifications**: Email notifications for post approvals, failures, and monthly analytics reports.

## Running Locally

The MVP will start as a simple Node.js application with a PostgreSQL database. To run it locally:

1. Install [Node.js](https://nodejs.org/) and [PostgreSQL](https://www.postgresql.org/).
2. Clone this repository and install dependencies:
   ```bash
   git clone <repo-url>
   cd wpm-software
   npm install
   ```
3. Create a `.env` file for environment variables such as database credentials and API keys.
4. Run database migrations (placeholder):
   ```bash
   npm run migrate
   ```
5. Start the development server:
   ```bash
   npm start
   ```

## Deployment

For production, you can deploy the application on a VPS. Configure a process manager (e.g., PM2 or systemd) and secure your database. Future documentation will include step‑by‑step deployment guides.

## Further Documentation

The following sections will be expanded as development progresses:

- **API Rate Limits**: Reference limits and policies for each social platform.
- **Analytics Configuration**: How to customize metrics and generate reports.
- **OAuth Setup**: Steps for configuring each provider (Google, Microsoft, Apple, etc.).

