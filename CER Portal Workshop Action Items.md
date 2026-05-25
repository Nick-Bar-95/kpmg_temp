# CER Portal Workshop — Action Items

**Source:** Workshops held on 12 May 2026 (Day 1) and 13 May 2026 (Day 2)  
**Parties:** KPMG (vendor/implementation) and QUT (client)

---

## Ways of Working

- Send a list of KPMG team members (Madhuri, Nic, and others) who need access to the QUT Jira instance so they can start creating tasks and test cases. **[KPMG]** *(Day 1)*
- Grant KPMG team members (Madhuri, Nic) access to the Word requirements documents via SharePoint/Teams site. **[QUT]** *(Day 1)*
- Add design notes and assumptions fields to each user story in the Word document, then import them into Jira (Quinn to verify field mapping is correct). **[KPMG]** *(Day 1)*
- Quinn to confirm that design notes and assumptions fields import correctly as standard Jira fields, or create custom fields if needed. **[QUT]** *(Day 1)*
- Create technical user stories for environment creation and security roles for Kerry and Cici to track progress; discuss scope with Kerry separately. **[KPMG]** *(Day 1)*
- Schedule a separate technical session between Cici (KPMG), Kerry (QUT architect), and Rafa to discuss environment setup and technical requirements. **[KPMG/QUT]** *(Day 1)*
- Confirm contract structure (time and materials vs. fixed price) and finalise the contract so the project timeline, UAT schedule, and resourcing can be locked in. **[QUT]** *(Day 1)*
- Once the contract is finalised, put together the full project timeline including UAT dates and confirm UAT resourcing. **[QUT]** *(Day 1)*
- After workshops, review all transcripts and recordings, add KPMG's notes/design changes to the Word documents with track changes, and tag Amy Brutton for review. **[KPMG]** *(Day 2)*
- Create a master Excel document with a field list (mandatory/optional fields, statuses) covering all modules, to be shared with QUT for confirmation. **[KPMG]** *(Day 2)*
- Ensure eDiscovery team is available during UAT to validate the document export/retrieval test scripts. **[QUT]** *(Day 2)*
- Prepare UAT test cases and test scripts for the eDiscovery/document export workflow. **[KPMG]** *(Day 2)*
- Finalise the effort estimation and cost after incorporating all workshop notes and updates to the Word document. **[KPMG]** *(Day 2)*

---

## Business Process

- Update the business process flow diagram to reflect: (a) "submitted" status instead of "not retrieved" post-document upload; (b) payment process moved to occur before the review mechanism dissatisfied path; (c) decision box for "further underpayment identified" after review outcome; (d) former-staff-only label on payment process; (e) loop-back from QUT HR advice to KPMG SSR review step. **[KPMG – Madhuri]** *(Day 1)*
- Clarify and confirm which specific cohorts (currently expected: 2, 4, and 5) will receive an initial findings correspondence before the final outcome, and update the business process flow and requirements accordingly. **[QUT]** *(Day 1)*
- Confirm whether correspondence/outcome letters will be issued from the portal or from an external system; if from the portal, determine how personalised PDF attachments (entitlement details per staff member) will be prepared, stored, and attached to the outcome email. **[QUT/KPMG]** *(Day 1)*
- Draft the outcome correspondence letter template, with data fields to be sourced from Prenesh's team; confirm whether it will be a single letter or include a separate attachment table. **[QUT – HR team/Rachel]** *(Day 1)*
- Confirm whether preliminary/initial findings emails will follow the same format as the final outcome email and whether they will require attachments. **[QUT]** *(Day 1)*
- Confirm the decision on whether payment details must be submitted before the review mechanism is accessible, or whether both modules are displayed simultaneously with instructional text prompting users to also complete payment details. **[QUT]** *(Day 1)*
- Add UI text to clearly instruct former staff that they need to complete both payment details and the review mechanism; design the wording. **[KPMG – Cici]** *(Day 1)*
- Clarify the process for staff who are current at the time of the outcome but subsequently leave QUT (become former) mid-CER; confirm that QUT HR will update current/former status on the whitelist before each cohort's communications are sent (not between rounds). **[QUT]** *(Day 2)*
- Confirm which cohorts will have access to the document upload module (and which will not), and finalise the start/end dates for each module per cohort before cohort one goes live. **[QUT]** *(Day 2)*
- Confirm that the document upload module will remain open for cohorts 2, 4, and 5 across both the initial review and initial findings periods (not closed between the two), and note this in the requirements. **[QUT]** *(Day 2)*
- Clarify and document the process for supervisor document submission: supervisors will submit documents via email to QUT, who will pass them to KPMG (not through the portal) — confirm this workflow and ownership. **[QUT]** *(Day 2)*
- Confirm the process by which QUT HR validates and formally approves CER outcomes and correspondence before outcomes are loaded into the system and correspondence is triggered. **[QUT]** *(Day 2)*
- Confirm the approach for when the payment system will pay former staff whose review takes more than 30 days (two separate payments vs. a single combined payment) and ensure this is reflected in the outcome notification wording. **[QUT]** *(Day 2)*

---

## Review Mechanism

- Add a line to the eligibility user story confirming that staff members are allowed to submit multiple review requests (no restriction on number). **[KPMG – Cici]** *(Day 1)*
- Discuss offline the best approach for handling a staff member who is in multiple cohorts and wants to submit a review request that spans cohorts; determine whether to allow multi-cohort selection or default to single-cohort selection with a free text field. **[KPMG/QUT]** *(Day 1)*
- Provide KPMG with the complete list of mandatory fields required for the review request form. **[QUT]** *(Day 1)*
- Provide KPMG with all email templates for every notification in the review mechanism (request confirmation, additional information request, outcome notifications — both underpayment identified and no underpayment identified), including dynamic fields to be populated from the record. **[QUT]** *(Day 1)*
- Confirm the final list of review outcome statuses and sub-statuses (e.g., resolved/underpayment identified; resolved/no underpayment identified; withdrawn/staff-initiated; withdrawn/timeout; cancelled/error; out of scope) and provide to KPMG. **[QUT]** *(Day 1)*
- Send QUT a recommended list of review status and sub-status reasons; QUT to review and confirm or add additional scenarios. **[KPMG]** *(Day 1)*
- Confirm whether the review outcome notification email for "underpayment identified" will follow the same format and attachment structure as the initial outcome email. **[QUT]** *(Day 1)*
- Confirm the number of QUT HR users who will need access to the review mechanism queue (currently anticipated at approximately 3–4 users). **[QUT]** *(Day 1)*
- Confirm and agree on the review mechanism SLA parameters: acknowledge within 2 business days, resolve within 30 calendar days; confirm that the acknowledgement can be automated. **[QUT]** *(Day 1)*
- Confirm whether a notification email to QUT HR is required when a case is routed to them, or whether daily dashboard monitoring is sufficient; if notification is needed, configure a simple automated notification. **[KPMG, pending QUT confirmation]** *(Day 1)*
- Review the FWO (Fair Work Ombudsman) reporting requirements for the review mechanism and confirm what data fields/dates need to be captured for each six-monthly report (submission date, reactivation date, resolution date, summary of review sought, summary of outcome, status). **[QUT]** *(Day 1)*
- Confirm the likely number of KPMG SSR assessors available at launch and confirm the peak resourcing plan (approximately 4 users initially). **[KPMG]** *(Day 1)*
- Confirm the desired pre-configured views for the review mechanism admin interface (e.g., by status, awaiting action, newly raised, re-submitted, cancelled/timed out); provide KPMG with view names, columns, filter criteria, and sort order. **[QUT]** *(Day 2)*
- Confirm whether QUT HR notification for new cases routed to their queue should be a simple automated email or whether daily dashboard monitoring is sufficient. **[QUT]** *(Day 2)*
- Determine and confirm the number and names of specific user roles to be created in the system (QUT tech admin, QUT HR admin, KPMG assessor, KPMG tech admin) and the access permissions for each role; provide to KPMG. **[QUT]** *(Day 2)*
- Confirm the desired list of pre-configured admin views for each module (review mechanism, document upload, payment details) including columns, filter criteria, and sort order so KPMG can configure them; alternatively, QUT to create their own views after training. **[QUT]** *(Day 2)*
- Confirm whether the SLA timer and colour-coded escalation indicator (highlighting records approaching the 30-day deadline) should be treated as a standard requirement or a "nice to have"; confirm it is likely out-of-box configuration. **[KPMG, to confirm cost]** *(Day 2)*

---

## Comms and Reporting

- Provide KPMG with all email templates for outcome correspondence across all modules (including format, from/subject fields, static text, and dynamic/personalised fields to be pulled from the record). **[QUT]** *(Day 1/Day 2)*
- Confirm the audit field list for each entity/table (which specific fields should have auditing enabled) so KPMG can configure auditing without enabling it on the entire entity. **[QUT]** *(Day 2)*
- Confirm the requirement for an audit trail of CSV data exports at user level (system tracks each user's own export history); walk QUT through the out-of-box export audit during UAT/training. **[KPMG]** *(Day 2)*
- Check whether an audit log can be created for the document export (who exported, when, what data scope) and report back to QUT. **[KPMG]** *(Day 2)*
- Walk QUT through how to create custom views, apply filters, and export CSV data during UAT/training. **[KPMG]** *(Day 2)*
- Confirm the data retention/deletion policy and whether a full audit trail export is required at the conclusion of the CER before records are deleted from the system. **[QUT]** *(Day 2)*
- Add a field "attachment exists: yes/no" to the supporting document and review mechanism entities to enable that data to appear in CSV exports. **[KPMG]** *(Day 2)*
- Confirm the approach for UniSuper and self-managed super fund export: create a filtered view/export so QUT HR can extract these records separately; cover in training. **[KPMG]** *(Day 2)*

---

## Landing and Authentication

- Review the out-of-box session timeout warning behaviour in Microsoft Entra External ID and advise QUT on whether a pre-timeout warning message is feasible and what the associated effort is. **[KPMG]** *(Day 2)*
- Confirm the OTP (one-time passcode) retry limit behaviour with Kerry (QUT architect) and standard security guidance from Microsoft Entra External ID. **[KPMG/QUT]** *(Day 2)*
- Show QUT the standard Entra ID authentication page/email template during the development phase and agree on branding (QUT logo, styling) at that point. **[KPMG]** *(Day 2)*
- Confirm the error message wording to display when an email/date-of-birth combination does not match the whitelist (anticipated to direct users to the FAQ page and/or the CER hotline). **[QUT]** *(Day 2)*
- Confirm and document the process for maintaining the whitelist: contact records (name, email, date of birth) to be managed in Entra External ID by the QUT tech team; cohort membership to be editable by QUT HR in the portal UI; document the process once the backend is accessible. **[KPMG]** *(Day 2)*
- Update the whitelist (contact records in Entra ID) when a staff member advises a change of email address via the existing online update form. **[QUT tech team]** *(Day 2)*
- Update the current/former staff status on the whitelist before each round of cohort outcome communications; confirm this as the agreed process. **[QUT HR]** *(Day 2)*
- Confirm whether QUT HR can self-manage the whitelist via the portal UI or whether this should be escalated to the QUT DBS tech support team for data management. **[QUT – Amy/Kerry]** *(Day 2)*
- Discuss the SharePoint/document export storage location and security approach with Kerry (QUT architect) in the separate technical session to resolve the file transfer method for KPMG eDiscovery. **[KPMG/QUT]** *(Day 2)*
- Finalise cohort configuration (start dates per module) in the system before cohort one goes live; QUT HR to supply the dates and KPMG to enter them; confirm that cohort dates for subsequent cohorts can be entered on a rolling basis. **[QUT to supply dates; KPMG to configure]** *(Day 2)*
- Confirm the decision on module display: whether ineligible modules should be hidden entirely or shown as disabled/greyed out — agreed as "hidden" but confirm this is the final position. **[QUT]** *(Day 2)*
- Design the review mechanism cohort-selection UX for staff who are in multiple cohorts (allow multi-cohort selection or single cohort with free text); confirm with QUT before build. **[KPMG]** *(Day 2)*

---

## Document Upload

- Confirm the final list of cohorts for which the document upload module will be enabled, including any cohorts with an initial findings correspondence round (anticipated: cohorts 2, 4, and 5). **[QUT]** *(Day 2)*
- Confirm the final approved file types for document upload (anticipated: PDF, Word, Excel, images, email .msg/.eml files, zip files) and maximum file size per upload (currently proposed at 20 MB per file). **[KPMG]** *(Day 2)*
- Confirm the character limit for the optional free text/contextual information field in the document upload module (currently proposed at 1,000 characters). **[QUT]** *(Day 2)*
- Confirm whether notifications to staff about the opening of the document upload window will be sent from outside the portal, and define the channel/process for sending those notifications. **[QUT]** *(Day 2)*
- Add UI instructional text to the document upload module warning users that documents must be submitted (not just uploaded) and that unsubmitted files will be deleted when form access closes. **[KPMG]** *(Day 2)*
- Confirm with Kerry (QUT architect) and QUT security the approved method for transferring exported document packages from SharePoint to KPMG eDiscovery (OneDrive, Azure Blob, KPMG secure transfer tool, or another approved method). **[QUT – Kerry to investigate and confirm]** *(Day 2)*
- Agree on the final SharePoint folder structure for document exports (proposed: retrieval date > staff ID and cohort ID folder > file upload instance > files, plus a summary CSV at the top level). **[KPMG – Cici and David/eDiscovery]** *(Day 2)*
- Confirm the agreed process: bulk export at the close of each cohort's document upload window (not on an ongoing basis), with a manual record kept by the eDiscovery team when files are retrieved. **[KPMG – eDiscovery team]** *(Day 2)*
- Clarify whether the document upload module is only for the initial review phase (staff voluntarily uploading timesheets etc.) and that review mechanism documents stay in SharePoint and are not exported to eDiscovery; confirm this understanding is correct. **[KPMG/QUT]** *(Day 2)*
- Confirm whether QUT needs to be able to view uploaded staff documents (as opposed to just KPMG); determine access permissions for QUT HR on the SharePoint document library. **[QUT]** *(Day 2)*

---

## Payment Details

- Confirm the payment system/platform that will be used to process former staff payments (not yet decided at time of workshops); once confirmed, determine whether payment file integration can be automated or will be a manual export/upload process. **[QUT]** *(Day 1)*
- Confirm the retention/deletion rules for payment detail records after payment is processed; agree on what fields should be retained in an audit log versus fully deleted. **[QUT]** *(Day 1)*
- Provide KPMG with the payroll system codes needed for the super reason code field and the additional super reason column (for populating the pay file), noting these codes may change over time. **[QUT]** *(Day 2)*
- Confirm the expected inactivity timeout period for the payment detail form (proposed: 2 hours; same as other modules) and confirm that partially entered data should be retained (not deleted on timeout) given the move to persistent sessions via Entra ID. **[QUT]** *(Day 2)*
- Confirm the wording and legal compliance requirements for the tax declaration statement displayed on the payment form (staff must agree before submission). **[QUT]** *(Day 2)*
- Confirm email wording/templates for all payment-related notifications: initial payment notification with personalised PDF attachment, rework/failure notification (dynamic field identifying which section to rework — bank, tax, or super), and reminder notifications. **[QUT]** *(Day 2)*
- Confirm the frequency and maximum number of payment reminder emails (current position: maximum of two reminders; no further reminders after the request is closed due to inactivity). **[QUT]** *(Day 2)*
- Confirm the country field in the bank details form: agree to use a standard country drop-down (NAB/AP standard list, excluding sanctioned countries) rather than free text. **[QUT to confirm final list; KPMG to implement]** *(Day 2)*
- Confirm the approach to the "notify payee of successful payment" notification (NF5 — payment confirmation email): QUT's current position is to remove this notification as the detail is captured on a payslip; confirm this is the final decision. **[QUT]** *(Day 2)*
- Add sub-statuses for each payment section (bank details, tax, super): waiting to be processed / processed / error waiting to be processed — confirm with QUT this structure is sufficient. **[KPMG – Cici]** *(Day 2)*
- Confirm process and ownership for exporting payment data to the payroll system (the system generates the pay file automatically; confirm who triggers the downstream payment execution and via which payroll system). **[QUT]** *(Day 2)*
- Confirm that payment detail data will be retained in the system for the duration of the CER, then exported and deleted at the conclusion of the year; confirm this retention/deletion approach with QUT governance/privacy team. **[QUT]** *(Day 2)*
- Demonstrate the UniSuper and self-managed super fund filtered views/exports to QUT HR during UAT/training so QUT can verify they can extract those records independently. **[KPMG]** *(Day 2)*
