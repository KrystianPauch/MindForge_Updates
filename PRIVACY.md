# MindForge — Privacy Notice

**Version:** 1.0 — 20 November 2026

## 1. Controller and Contact

The controller of personal data processed through MindForge's optional cloud functionality is **Krystian Pauch**.

**Contact:** pauchkrystian@gmail.com

## 2. Data Processed

MindForge stores notes, mind maps, collections, and settings locally on your device.

If you register an account or enable optional cloud synchronization, the service processes:

- **Account information:** Your email address, account identifier, and authentication-related information.
- **Synchronized content:** Notes, mind maps, collections, settings, and associated metadata included in your synchronized workspace.
- **Workspace metadata:** User identifier, revision number, JSON workspace snapshot, and last modification timestamp.
- **Technical information:** Operational, connection, and security logs processed by the cloud provider as necessary to operate and protect its services.

Users are encouraged to avoid storing highly sensitive personal information in cloud-synchronized content unless they understand the associated privacy implications.

## 3. Purposes and Legal Bases

Personal data is processed for the following purposes:

- **Account management and synchronization:** To provide optional cloud functionality requested by the user, based on Article 6(1)(b) GDPR where processing is necessary to provide the service.
- **Security and abuse prevention:** To maintain service security and prevent unauthorized access, where applicable based on legitimate interests under Article 6(1)(f) GDPR, subject to the relevant balancing assessment.
- **Legal compliance:** To satisfy applicable legal obligations where necessary, under Article 6(1)(c) GDPR.

MindForge can be used locally without registering a cloud account.

## 4. Service Provider and Data Location

MindForge uses **Supabase** for email-based authentication and optional cloud synchronization.

The primary database is configured in the **London (eu-west-2), United Kingdom** region.

The United Kingdom is covered by an adequacy decision of the European Commission for relevant personal data transfers.

Supabase and its authorized subprocessors may process certain technical, support, and operational information in other locations, subject to applicable contractual and legal safeguards.

For additional information, see:

- [Supabase Privacy Policy](https://supabase.com/privacy)
- [Supabase Data Processing Addendum](https://supabase.com/legal/customer-resources/data-processing-addendum)

## 5. Data Retention and Account Deletion

### Account and Workspace Data

Cloud account information and synchronized workspace data are generally retained while the user's account remains active, unless the user requests deletion or applicable law requires otherwise.

### Account Deletion Requests

MindForge currently does not provide an in-app account deletion feature.

To request deletion of your account and synchronized data, contact:

**pauchkrystian@gmail.com**

Requests should preferably be submitted from the email address associated with the MindForge account.

After verifying the request, the Controller will arrange deletion of the corresponding authentication account and synchronized workspace records without undue delay, generally within **14 days** of successful verification.

Requests will be handled within the time limits required by applicable data protection law. Where an extension is legally permitted and necessary, the user will be informed accordingly.

### Technical and Security Logs

Supabase's Free plan provides a standard **24-hour retention period** for API, database, and authentication audit logs available through its logging services.

Other operational records, backups, and technical information may be subject to separate retention periods and policies maintained by Supabase or its subprocessors.

### Local Data

Data stored locally on a user's device remains under the user's control.

Deleting a cloud account does not automatically delete:

- Locally stored notes and mind maps.
- Files exported by the user.
- Backups independently created by the user.

## 6. User Rights

Subject to applicable law, users may have the right to:

- Access their personal data.
- Request correction of inaccurate information.
- Request deletion of personal data.
- Restrict certain processing.
- Receive personal data in a portable format where applicable.
- Object to processing based on legitimate interests.
- Lodge a complaint with a competent supervisory authority.

In Poland, the relevant supervisory authority is the **President of the Personal Data Protection Office (UODO)**.

[UODO Official Website](https://uodo.gov.pl/)

To exercise your rights, contact **pauchkrystian@gmail.com**.

## 7. Data Security and Backups

MindForge uses Supabase authentication and database row-level security (RLS) policies.

The synchronized workspace table is configured to restrict authenticated users to records associated with their own user identifiers.

Reasonable measures are taken to protect personal data. However, no software application, storage system, or synchronization service can guarantee absolute security or uninterrupted availability.

Users are strongly encouraged to maintain independent backups of important notes, mind maps, and other content.

## 8. Changes to This Privacy Notice

This Privacy Notice may be updated to reflect changes in MindForge, its cloud services, or applicable legal requirements.

Material changes will be communicated where required by law.

The current version will be made available through the official MindForge distribution repository.
