# Alert-ticket
Use a playbook to respond to a phishing incident

## Objective
In this activity, you will respond to a phishing incident that involves a malicious file hash. This is the same SHA256 file hash that you investigated and verified as malicious in the <a href="https://github.com/CoachKosik/Pyramid-of-Pain/blob/main/README.md?plain=1">Pyramid of Pain</a> activity. You'll follow playbook instructions to investigate and resolve the incident's alert ticket.

## Project description
You are a level-one security operations center (SOC) analyst at a financial services company. Previously, you received a phishing alert about a suspicious file being downloaded on an employee's computer. After investigating the email attachment file's hash, the attachment has already been verified malicious. Now that you have this information, you must follow your organization's process to complete your investigation and resolve the alert.

Your organization's security policies and procedures describe how to respond to specific alerts, including what to do when you receive a phishing alert. 

In the playbook, there is a flowchart and written instructions to help you complete your investigation and resolve the alert. At the end of your investigation, you will update the alert ticket with your findings about the incident.


## Skills Learned
  * **Incident Response Playbook Adherence:** Ability to follow a predefined playbook to guide incident response actions.
  * **Alert Triage and Prioritization:** Evaluating the severity and potential impact of security alerts.
  * Threat Assessment:** Determining the nature and scope of a security incident based on available information.
  * **Decision-Making:** Making informed decisions about escalating incidents or taking corrective actions.
  * **Documentation and Reporting:** Accurately documenting incident details and response actions.
  * Communication:** Effectively communicating incident information and recommendations to relevant stakeholders.

## Tools Used
* **Alert Ticket Template:** A standardized template for documenting incident details, status, and resolution.
* **Phishing Incident Response Playbook:** A detailed guide outlining the steps to be taken during a phishing incident investigation.
* **Incident Handler's Journal:** A personal journal to record notes, observations, and findings during the investigation.
* **Email Analysis Tools:** Tools to analyze email headers, attachments, and URLs for malicious content.

## Steps
### Step 1: Access the template
To use the template for this course item, click the link below and select Use Template.
  * Link to template: <a href="https://docs.google.com/document/d/1IYXkQCagblu4xgnnZcv8N9N7M5bHTBDw/edit">Alert Ticket</a>

### SStep 2: Access supporting materials
The following supporting materials will help you complete this activity. Keep them open as you proceed to the next steps. 
  * Link to supporting materials: <a href="https://docs.google.com/document/d/1axad16ZrozrsNVVQD5nJxk5bzAeIMFvV/edit?usp=sharing&ouid=105064495821226407439&rtpof=true&sd=true">Phishing Playbook (with flowchart)</a>

### Step 3: Review the playbook and flowchart
Before you begin investigating the alert, take a moment to review the playbook and flowchart because you'll be using them throughout the investigation.

The Phishing Playbook instructions provide detailed, written instructions about each step represented in the flowchart.

The Phishing Flowchart provides a high-level overview and visual representation of the sequence of steps and substeps you'll take to respond to a phishing alert.

*Note: The steps in this playbook are not a definitive guide to responding to a phishing incident. Organizations have their own sets of policies, standards, and procedures that determine the expected response actions to incidents.*

### Step 4: Update the alert ticket status
In the Alert ticket template, begin the investigation by updating the Ticket status dropdown list to Investigating.
  * ![alert ticket 1](https://github.com/user-attachments/assets/3ecd24fd-7646-4d98-9893-ead6380c18af)

### Step 5: Evaluate the alert
For this exercise, begin with the second step in the playbook, Evaluate the alert, because you've already received and accessed the phishing alert ticket. 

As a security analyst, you'll want to gain a complete understanding of why the alert was triggered. Create a new entry in your incident handler's journal to record the details of this security incident and gather your thoughts. You'll refer to these notes as you progress through the steps in the playbook. 

Then, evaluate the contents of the Alert ticket, including the content in the Additional information section. Here are some examples of elements to examine when you are evaluating the alert ticket details:

  * **Alert severity:** According to the playbook instructions, an alert severity of Medium or High is a good indication that a ticket might require escalation.

  * **Sender details:** Analyzing the sender details of an email is important because it can reveal inconsistencies that can indicate a phishing attempt. Often, phishing emails try to impersonate trusted entities. For example, if there is a mismatch between the sender's email address and the sender's name, this is a good indication that the email might be a phishing email.

  * **Message body:** It's important to analyze the message body (and subject line) of an email because phishing emails often contain grammatical errors, which can be an indication of a phishing attempt.

  * **Attachments or links:** Phishing emails contain malicious links or attachments that are used to steal sensitive information or download malicious software or code on the recipient's device. Check to see whether a file has been attached to this email.

After you've evaluated the contents of the alert ticket, answer the 5 W's of this incident to gather the information you need to understand the nature of the alert. The 5 W's are:

  * Who caused the incident?
  * What happened?
  * When did the incident take place?
  * Where did the incident occur?
  * Why did it happen?

At the end of this step, you should have 2-3 reasons on why you believe the phishing alert is or isn't legitimate.

### Step 6: Determine whether the alert should be escalated
After evaluating the alert details, use the Phishing Playbook's Step 3.0 and Step 3.1 to determine whether the email contains links or attachments and whether these links or attachments are malicious. Remember you've already determined that the email contains an attachment that has been verified as malicious through its file hash. 

Proceed to the Phishing Playbook's Step 3.2 if you've determined that the alert should be escalated. If you've determined that the alert should not be escalated, proceed to the Phishing Playbook's Step 4.

### Step 7: Update the alert ticket status
Now that you've examined the email details, complete the final step of the playbook and update the alert ticket in the activity template. Depending on whether you want to escalate or close the alert:

Under the Ticket status column of the alert ticket template, update the status of the ticket to either Closed or Escalated.

Under the Ticket comments column of the alert ticket template, use the details you've found to explain the steps taken and why you chose to escalate or close the ticket. Include 2-3 reasons as to why you believe this alert should be escalated or closed.



### Summary
A phishing incident was detected where an employee received a suspicious email with a malicious attachment. The email displayed several red flags, including a mismatched sender name and email address, grammatical errors, and a suspicious attachment name. The employee unfortunately downloaded and opened the attachment, potentially compromising their system.

Upon further analysis, the file hash was confirmed to be malicious. Due to the severity of the incident, it was escalated to a level-two SOC analyst for a more in-depth investigation and appropriate response actions.
