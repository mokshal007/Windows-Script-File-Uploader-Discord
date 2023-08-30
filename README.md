# Discord Webhook File Uploader and System Interaction Script

This repository contains a Python script that demonstrates the interaction with system elements and the ability to upload files to a Discord webhook. Please use this script responsibly and adhere to ethical and legal considerations.

## Features

- **System Interaction:** The script interacts with the Windows system by locking input devices and minimizing windows to show the desktop.
- **Window Management:** It hides visible top-level windows and modifies window styles to make them minimizable.
- **File Uploading:** The script is capable of uploading files to a specified Discord webhook.
- **File Searching:** It searches for files in various directories on available drives, considering specified criteria.
- **Concurrency:** The script utilizes threading to perform file searches in parallel across multiple drives.
- **File Type Validation:** The script validates files based on allowed extensions to ensure proper uploading.

## Setup

1. Clone this repository to your local machine.

2. Open the script in a Python editor or IDE.

3. Replace the placeholder `WEBHOOK_URL` with the URL of your Discord webhook. If you don't have a webhook yet, follow the steps below to create one.

## Creating a Discord Webhook

1. **Access Your Discord Server:**
   Log in to your Discord account and navigate to the server where you want to add the webhook.

2. **Server Settings:**
   Click on the server name to open the drop-down menu, then select "Server Settings."

3. **Integrations:**
   In the left sidebar, click on "Integrations."

4. **Webhooks:**
   Scroll down and click on the "Webhooks" section.

5. **Create Webhook:**
   Click the "Create Webhook" button.

6. **Webhook Setup:**
   - **Name:** Give your webhook a name. This is the name that will appear as the sender when the webhook posts.
   - **Channel:** Choose the text channel where the webhook messages will be sent.
   - **Webhook Avatar:** You can set an avatar image for the webhook (optional).

7. **Copy Webhook URL:**
   After setting up the webhook, a webhook URL will be generated. This URL is unique and acts as the endpoint for sending messages to the webhook.

8. **Replace URL:**
   Go back to the script and replace the `WEBHOOK_URL` placeholder with the URL you copied.

9. **Review and Run:**
   Review and customize the `BLACKLISTED_DIRS` list to exclude directories during file searches. Once everything is set, run the script.

10. **Usage Considerations:**
   - Always use this script responsibly and with proper authorization.
   - Ensure you adhere to ethical and legal standards when using this script.
   - Uploading files to a Discord webhook without consent may raise ethical and legal concerns.

## Disclaimer

The creators of this repository do not endorse or encourage any malicious activities. The script is provided for educational purposes and to demonstrate certain functionalities. Any use of this script should be in line with ethical and legal guidelines.

Always prioritize privacy, security, and responsible use of technology.

