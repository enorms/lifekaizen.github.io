---
layout: default
permalink: /assistant/privacy/
id: personal_assistant_privacy
---

# Eric Personal Assistant — privacy policy

Last updated: October 15, 2026

Eric Personal Assistant is a private, personal-use integration operated by Eric Norman. It connects only accounts that the account owner explicitly authorizes. This policy describes the assistant integration; other websites linked from norman.zone have their own practices.

## Google data accessed

With read-only authorization, the assistant can retrieve Gmail messages and threads, including senders, recipients, subjects, dates, labels and message text, and Google Calendar information such as event titles, times, attendees, descriptions and locations. The workflow initially reviews recent inbox and sent conversations and upcoming events. It can revisit relevant conversations when tracking an unresolved task. Automated attachment downloads are not part of the current workflow.

## How data is used

Data is used to track replies and commitments, identify items needing attention, prepare for calendar events, and produce private summaries and proposed next actions. Classifications and suggested dates may be incorrect and remain subject to Eric's review. Retrieved messages cannot authorize new actions or change the assistant's permissions.

## Processing and sharing

Google data is retrieved directly from Google APIs by software on Eric's computer. OpenClaw coordinates the workflow. Relevant content is sent to configured OpenAI models for analysis and summarization; it is not accurate to describe this assistant as entirely offline. OpenAI processing is subject to the applicable account settings and service terms.

The integration does not sell Google user data, use it for advertising, or intentionally publish it on this website. It does not use Google user data to develop or train a generalized AI model. Private records are not exposed through the public app-information pages. Any added provider or materially different use requires review and an update to this policy before use.

Eric Personal Assistant's use and transfer of information received from Google APIs will adhere to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including its Limited Use requirements.

## Storage and retention

Google authorization credentials are stored in the computer's macOS Keychain. Working notes, checkpoints, summaries, and execution history are stored on the assistant computer and may appear in its backups or authorized administration tools. Records are retained while useful for personal follow-through or until removed by the operator. Revoking Google access stops future authorized retrieval but does not automatically delete existing notes, transcripts, provider-held records, or backups.

## Control and deletion

The account owner can revoke the integration through [Google Account connections](https://myaccount.google.com/connections). Eric can pause the workflow, remove locally stored credentials, and delete local records and backups. Requests or questions about access or deletion can be sent to [eric@norman.zone](mailto:eric@norman.zone). Data held by a model provider is also subject to that provider's retention and deletion controls.

## Changes

This policy will be updated when the integration's data practices materially change. Additional access, including any ability to send email or modify calendars, requires separate authorization.

[App information](/assistant/) · [Use and limitations](/assistant/terms/)
