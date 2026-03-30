# Privacy Policy — SprintLens

**Last updated: March 30, 2026**

## Overview

SprintLens ("the App") is a Forge app built on Atlassian's platform by Ashish Sharda / SprintLens Labs. This Privacy Policy explains how the App collects, uses, and protects information when installed on your Atlassian Jira instance.

## Data We Access

SprintLens accesses the following data from your Jira instance to provide its features:

- **Sprint and board data** — sprint names, dates, and status to render Gantt charts
- **Issue data** — issue summaries, statuses, assignees, story points, and update timestamps to detect stale issues and overallocation
- **User data** — display names and avatar URLs to show assignee information in dashboards

## Data We Store

SprintLens uses Atlassian Forge's built-in key-value storage to store:

- **App configuration** — thresholds, notification settings, and display preferences you set in the Settings panel
- **Notification state** — records of which stale/overallocation alerts have been sent, to prevent duplicate notifications

All stored data is scoped to your Atlassian site and managed through Atlassian's Forge infrastructure. We do not store your Jira data on any external servers.

## Data We Do Not Collect

- We do not collect or store issue content or descriptions
- We do not collect personal information beyond what Jira provides for display purposes
- We do not sell, share, or transfer any data to third parties
- We do not use cookies or tracking technologies

## Third-Party Services

If you enable Slack notifications in the Settings panel, SprintLens will send alert messages to the Slack webhook URL you provide. This data transmission is entirely optional and controlled by you. We do not store your Slack webhook URL beyond your Forge app configuration.

## Data Retention

Configuration data stored by SprintLens persists until you uninstall the app or manually clear it through the Settings panel. Notification state records expire automatically after 30 days.

## Security

SprintLens operates entirely within Atlassian's Forge sandboxed environment. All API calls are made server-side using Atlassian's secure `api.asApp()` mechanism. No credentials or tokens are exposed to the browser.

## Your Rights

You may request deletion of any data stored by SprintLens by uninstalling the app from your Jira site. This will remove all configuration and notification state data associated with your installation.

## Changes to This Policy

We may update this Privacy Policy from time to time. Updates will be reflected in the app listing on the Atlassian Marketplace.

## Contact

For privacy-related questions or concerns, contact:

**Ashish Sharda**
Email: sharda.ashish26@gmail.com
