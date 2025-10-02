Cyber Security Internship - Task 7: Identify and Remove Suspicious Browser Extensions
1. Objective
The objective of this task was to learn to spot and remove potentially harmful browser extensions in a web browser. This exercise aims to raise awareness of browser security risks and best practices for managing browser extensions.



2. Tools Used
Web Browser: Google Chrome 

Operating System: Windows 11

3. Step-by-Step Process and Analysis
The following steps were taken to review the installed extensions, as outlined in the mini-guide :

Accessed the Extensions Manager: Navigated to chrome://extensions to view all installed extensions.

Reviewed Extensions: Two extensions were found: "Dark Theme - Dark mode for Chrome" and "Google Docs Offline."

Analyzed "Dark Theme - Dark mode for Chrome":

Permissions Found: This extension requested access to "Read your browsing history" and "Allow this extension to read and change all your data on websites that you visit" (on all sites).

Suspicion Rating: High. These permissions are excessive for a simple theme/dark mode utility and pose a severe security risk, as the extension could steal credentials or inject malicious code on any webpage.

Action: Removed immediately.

Analyzed "Google Docs Offline":

Permissions Found: This extension requested to "read and change your data on sites," but its access was limited to https://docs.google.com/* and https://drive.google.com/*.

Suspicion Rating: Low. The permissions are appropriately scoped and necessary for the official function of allowing offline document access.

Action: Kept.


Performance Check: Restarted the browser to confirm that the removal of the suspicious extension did not cause any instability and potentially improved performance.

4. Deliverables: List of Suspicious Extensions Found and Removed
Extension Name	Action Taken	Reason for Removal / Security Risk
Dark Theme - Dark mode for Chrome	Removed	High Risk: Requested blanket access to all sites and browsing history. This privilege is highly exploitable for tracking, credential theft, and injecting malware/ads.
Google Docs Offline	Kept	Not Suspicious: Legitimate, official extension whose permissions were appropriately limited to only Google Docs and Drive domains.

Export to Sheets
5. Research on Malicious Extensions
(This section fulfills the requirement to "Research how malicious extensions can harm users" and prepares for the Interview Questions .)


Malicious browser extensions can pose significant security risks by:


Data Theft: Using overly broad permissions to monitor user activity, record keystrokes (passwords, credit cards), and scrape data from secure websites.

Adware/Hijacking: Changing the browser's default search engine or injecting unwanted advertisements into websites (adware).

Unauthorized Activity: Running malicious code in the background to perform actions on the user's behalf, such as clicking on links or making purchases.

To install extensions safely, users should:

Only install extensions from 

official, reputable stores (like the Chrome Web Store).


Carefully review the permissions requested, and reject any that are not strictly necessary for the extension's function (e.g., a simple weather extension shouldn't need "all data on all sites").

Check the extension's 

user reviews, number of users, and developer reputation.
