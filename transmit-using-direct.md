---
layout: default
title: Transmitting Data Using the Direct Protocol
---

# Transmitting Data Using the Direct Protocol

Two sentences describing what transmit is. Two sentences describing what the Direct protocol is.

## Workflow

### Patient Portal

Storyboard describing flow.

Patient Logs In. Patient clicks Share. Patient enters Direct address. Check if always want to send. Patient clicks Send.

Ability to login and revoke access.

### EMR / Provider Side

Storyboard describing flow.

Patient provides consent to Provider. Provider uses EMR. Goes to Patient Record. Clicks Share. Check if always want to send. Enters a Direct Address. Clicks send.

Ability to stop sending.

Way 1, in-person.
Way 2, clipboard consent.

## Technical

### Payload

Should be CCDA/MU-2 for health data. Should be YYY for claims data.

### Direct Protocol

The Direct Protocol is used to send health data securely from Point A to Point B.

Description of Direct Protocol

Image outlining how it works.

Technical image outlining how it works.

Certificate Exchange
Pointers to "Trusted" Whitelist.
Must be able to refer to multiple whitelists.
Must pull from whitelists at X frequency.

Certificate Discovery - Using DNS and LDAP
Link to more detailed spec.

Links to Sample Code

Links to Direct Spec

### Automation

Sending frequency. Triggers.

## Privacy & Security

Guidance - It's okay to use publically discoverd certificates to send a Direct message initiated by the consumer. This ensures everything transmitted is encrypted. 

(The certificates do not need to be exchanged.)

A patient should be able to send their files to any Direct address.

Link to Letter/Guidance from ONC/OCR.

Best Practice / Suggestion - Show a lock. Show a signature icon too.