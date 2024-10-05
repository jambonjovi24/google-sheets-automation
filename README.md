# google-sheets-automation
test 2
# n8n Workflow Projects

## Project Title: Google Sheets Automation

### Description
This workflow automatically sends an email notification when a new task is added to a Google Sheet. It is designed to streamline task management by notifying users immediately when updates occur.

### Setup Instructions
1. Create a Google Sheet with columns for Task, Status, Deadline, and Assigned To.
2. Import this workflow into n8n using the provided JSON file.
3. Ensure you have authenticated the Google Sheets and Gmail nodes with the correct API credentials.
4. Activate the workflow to start monitoring for new entries in the Google Sheet.

### Node Overview
- **Google Sheets**: Monitors the spreadsheet for new rows added.
- **Function**: Processes the data from Google Sheets to format it for the email.
- **Gmail**: Sends email notifications with the task details.

### Challenges and Solutions
- Encountered issues with API authentication; resolved by ensuring the Gmail API was enabled and correctly authenticated in the Google Cloud Console.

### License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
