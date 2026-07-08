# Privacy Policy

**Last Updated:** July 9, 2026

This Privacy Policy describes how the **WhatsApp Message Sending Service** ("the Service", "the App") collects, uses, processes, and protects personal data in connection with the WhatsApp Business Platform/Cloud API. 

This Service is developed and operated by **[Your Organization Name]** ("we", "us", "our").

---

## 1. Scope and Purpose (Internal Use Only)
The Service is an **internal-only organizational tool** designed to facilitate communication between our organization and our customers, clients, or users ("Recipients") who have consented to receive communications via WhatsApp. 
* **No Public Access:** The Service does not provide public registration, public accounts, or general public access. Access to the Service dashboard, API, and admin controls is strictly restricted to authorized employees and representatives of our organization.
* **Review Context:** Because this App is strictly for internal business operations and direct integration with our backend systems, there is no public-facing interface for end-users to register or log in.

---

## 2. Personal Data We Process
To facilitate messaging via the WhatsApp Business Cloud API, the Service processes the following categories of data:
* **Recipient Contact Information:** Phone numbers of message recipients.
* **Message Content:** The text, media, templates, and interactive selections contained within messages sent to or received from recipients.
* **Metadata and Status Logs:** Webhook event data received from Meta (such as message delivery status, read receipts, message timestamps, and unique message identifiers).
* **System Credentials:** Secure API keys and tokens used by internal systems to authenticate with this Service (these do not contain personal data of end-users).

---

## 3. How We Use the Data
We use the processed data solely for the following purposes:
* **Message Delivery:** Transmitting text, media, and templates to recipients via the Meta WhatsApp Business Cloud API.
* **Webhook Monitoring:** Processing status updates (sent, delivered, read) and inbound customer replies to update our internal customer records and ensure message delivery.
* **Operational Logging:** Creating temporary debug logs to monitor system health, verify webhook signatures, and resolve technical issues.

We do not sell, rent, lease, or share personal data with third parties for marketing or promotional purposes. All transmission of data is strictly to Meta Platforms, Inc. (as the provider of the WhatsApp Business Platform) to execute the messaging actions requested by our internal systems.

---

## 4. Data Sharing and Third-Party Services
Our Service integrates directly with the **Meta Developer Platform (WhatsApp Business Cloud API)**. By using this service, data is processed in accordance with Meta’s own terms and policies.
* **Meta Platforms, Inc.:** Data is transmitted securely via HTTPS to Meta’s Graph API endpoints.
* **No Other Third Parties:** We do not share recipient data with any other third-party services, analytics networks, or data brokers.

---

## 5. Data Retention
We retain personal data (such as phone numbers and message status logs) only as long as necessary to fulfill the business purposes outlined in this policy or as required by applicable laws and regulations. Debug logs are set to rotate and clear automatically.

---

## 6. User Rights and Data Deletion Instructions
Under Meta Platform Terms and applicable data protection regulations (such as GDPR, CCPA, etc.), individuals have the right to request access to, correction of, or deletion of their personal data.

### How to Request Data Deletion
If you are a recipient of messages sent via our WhatsApp Service and wish to request the deletion of your contact details or message log history, you may do so through one of the following methods:
1. **Email Request:** Send a request to our privacy team at **[Your Contact Email]** with the subject line "WhatsApp Data Deletion Request" and specify the WhatsApp phone number in question.
2. **Opt-Out Message:** Send the word **"STOP"** (or local equivalent) directly to our WhatsApp Business phone number. Our system is designed to stop sending automated messages and flag your record for deletion.

Upon receiving a valid request, we will delete your personal data (including phone number and associated message logs) from our Service databases within **30 days**, unless we are legally required to retain it for compliance or financial auditing purposes.

---

## 7. Security Measures
We implement appropriate technical and organizational measures to secure data, including:
* **HTTPS/TLS Encryption:** All outbound API requests and inbound webhooks are encrypted in transit.
* **Access Control:** The API is protected by Bearer token authentication, and Firestore databases (if configured) are protected by strict security rules.
* **Token Safety:** Credentials (like access tokens and private keys) are stored in secure environment variables and are never hardcoded.

---

## 8. Changes to This Policy
We may update this Privacy Policy from time to time to reflect changes in our practices or operational requirements. Any updates will be posted to this page with an updated "Last Updated" date.

---

## 9. Contact Us
For any questions regarding this Privacy Policy or our data practices, please contact us at:
* **Email:** [Your Contact Email]
* **Website:** [Your Organization Website]
