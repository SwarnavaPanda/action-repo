# action-repo
"Create a new repository action-repo to deal with GitHub actions using webhooks..." "...Also create another repository webhook-repo for the endpoint..."

This repository is used to trigger GitHub webhook events such as:

- ✅ Push
- ✅ Pull Request
- ✅ Merge (via PR)

These events are sent to the webhook endpoint hosted in [webhook-repo](https://github.com/YOUR_USERNAME/webhook-repo), which saves them to MongoDB and displays them on a polling UI.

## Purpose

This repo is part of the Developer Assessment Task. It simulates developer activity to test webhook integration.

## Usage

1. Clone this repository.
2. Perform the following actions:
   - Make a commit and push to trigger a `push` event.
   - Open a pull request to trigger a `pull_request` event.
   - Merge a pull request to trigger a `merge` event.
3. The webhook will receive and process the events in real-time.

