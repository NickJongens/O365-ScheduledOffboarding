# Office 365 / Azure AD User Scheduled Offboarding
Code designed to allow an automatic offboarding of a user at a specific time using Azure Functions.

Required Outcomes:

- Disable the user.
- Convert the mailbox to a shared mailbox.
- Remove the license on the user account.
- Rename the account to include 'ARCHIVED - ' in the display name.
- Scheduling the task for the future must be possible.
- Reporting must be sent for manual review later on.

Ideas:

- Potentially integrate into a PSA e.g Datto Autotask.
- Hook into Microsoft Power Automate for approval of offboarding to the original requester.
- Use Microsoft Teams Webhooks for notification.
- Delegate Mailbox access to the original requester. 
- Automate me out of 1/4 of a job, but retain the code rights to ensure this doesn't replace me.

Technologies:

- Azure AD
- Azure Functions.
- Powershell.
- Secure Application Model.
- Webhooks.
- API (PSA).

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3a%2f%2fraw.githubusercontent.com%2fNickJongens%2fO365-ScheduledOffboarding%2fmaster%2fAzureFunction%2ftemplate.json)

