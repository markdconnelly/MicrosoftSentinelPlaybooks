# Alert-Response-NotifyUserWorkflow

> This is a Logic App that can be attached to Microsoft Sentinel to automate the workflow of reaching out to users and getting activity confirmation

> This Logic App was create by Mark Connelly and can be freely used and modified as needed

### Step 1 - Someone does something phishy
![Phishy Activity](https://github.com/markdconnelly/MicrosoftSentinelAutomation/blob/main/AlertResponse-NotifyUserWorkflow/01-MaliciousActivity.png)

### Step 2 - Sentinel gets an incident with an account entity attached to it
![Sentinel Incident](https://github.com/markdconnelly/MicrosoftSentinelAutomation/blob/main/AlertResponse-NotifyUserWorkflow/02-Sentinel-IncidentWithAccount-Triggered.png)

### Step 3 - Playbook executes
![Playbook](https://github.com/markdconnelly/MicrosoftSentinelAutomation/blob/main/AlertResponse-NotifyUserWorkflow/03-Sentinel-RunPlaybook.png)

### Step 4 - Email gets sent to user asking them if they did that
![Email Alert](https://github.com/markdconnelly/MicrosoftSentinelAutomation/blob/main/AlertResponse-NotifyUserWorkflow/04-Email-AlertNotification.png)

### Step 5 - If they confirm in email, they will get a response like this
![Email Confirm](https://github.com/markdconnelly/MicrosoftSentinelAutomation/blob/main/AlertResponse-NotifyUserWorkflow/05-Email-ActivityConfirmed.png)

### Step 6 - If they confirm in email, a comment like this will go into the sentinel incident
![Email Confirm Comment](https://github.com/markdconnelly/MicrosoftSentinelAutomation/blob/main/AlertResponse-NotifyUserWorkflow/06-Email-SentinelComment-ConfirmedActivity.png)

### Step 7 - They may see the notification in teams first
![Teams Notify](https://github.com/markdconnelly/MicrosoftSentinelAutomation/blob/main/AlertResponse-NotifyUserWorkflow/07-Teams-AlertNotification.png)

### Step 8 - Whether they get email or teams first, they can confirm either way
![Teams Confirm](https://github.com/markdconnelly/MicrosoftSentinelAutomation/blob/main/AlertResponse-NotifyUserWorkflow/08-Teams-ActivityConfirmed.png)

### Step 9 - In teams, they will get a policy tip letting them know their response was submitted instead of a confirmation email
![Teams Policy Tip](https://github.com/markdconnelly/MicrosoftSentinelAutomation/blob/main/AlertResponse-NotifyUserWorkflow/09-Teams-Alert%20Notification-PolicyTip.png)

### Step 10 - If they confirm in teams, a comment like this will go into the sentinel incident
![Teams Confirm Comment](https://github.com/markdconnelly/MicrosoftSentinelAutomation/blob/main/AlertResponse-NotifyUserWorkflow/10-Teams-SentinelComment-ConfirmedActivity.png)

### Step 11 - If they reject the prompt via email, they will get a response like this
![Email Reject](https://github.com/markdconnelly/MicrosoftSentinelAutomation/blob/main/AlertResponse-NotifyUserWorkflow/11-Email-ActivityRejected.png)

### Step 12 - If they reject the prompt via email, the incident will get a comment like this
![Email Reject Comment](https://github.com/markdconnelly/MicrosoftSentinelAutomation/blob/main/AlertResponse-NotifyUserWorkflow/12-Email-SentinelComment-RejectedActivity.png)

### Step 13 - If they reject it in teams, they will get a policy tip like this
![Teams Reject](https://github.com/markdconnelly/MicrosoftSentinelAutomation/blob/main/AlertResponse-NotifyUserWorkflow/13-Teams-ActivityRejected.png)

### Step 14 - If they reject it in teams, the incident will get a comment like this
![Teams Reject Comment](https://github.com/markdconnelly/MicrosoftSentinelAutomation/blob/main/AlertResponse-NotifyUserWorkflow/14-Teams-SentinelComment-ActivityRejected.png)

> As you can see

> This automation workflow can quickly get user feedback to aid in an investigation

> Feel free to grab this code to use in your environment 