# gcp-support-api-email-update-poc

This code is created by Eugene Enclona, If you have any questions about this code reach out to eenclona@google.com

## Overview

The purpose of this POC is to show how to utilize the Support API to modify the email address field of each support case. This can be done through the updateAllEmails() method.

This use case solves the common problem faced by orgs with many support cases needing an update of the email addresses attached to their cases. For example, if an org creates a new email address to track all support cases and it wishes to add this email to all open support cases. This can be done easily in a programmatic way.

In addition to the POC, I also showed how to use the other methods exposed by the API in the code, like listing cases, getting a case, etc. 

## How to get started

1. Make sure you have a support enabled GCP account.
2. Create a service account that has the Organization Viewer and Tech Support Viewer role.
3. Download the service account key
4. run the following command in the terminal: export GOOGLE_APPLICATION_CREDENTIALS=".../[path to service account key/.json"
5. Run the main method of my code and this should list all support cases :)
