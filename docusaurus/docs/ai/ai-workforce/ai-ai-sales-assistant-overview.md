---
title: AI Sales Assistant – Meeting Automation
sidebar_label: AI Sales Assistant
description: Automate meeting recording, transcription, and CRM logging with the AI Sales Assistant.
tags: [ai-sales-assistant, crm, google-meet, microsoft-teams]
keywords: [meeting recording, crm integration, ai notetaker, internal meetings, google calendar]
---
# Introduction to the AI Sales Assistant

##What is AI Sales Assistant?

The AI Sales Assistant is a meeting automation tool that integrates with Google Meet to automatically join meetings, record them, transcribe the conversation, and log outputs directly into CRM records. It acts as an AI-powered notetaker designed to reduce manual entry and improve meeting follow-up.

## What can it do?

The AI Sales Assistant automatically captures, transcribes, and logs meeting content into your CRM. It functions silently in the background, reducing administrative overhead and ensuring accurate data capture for sales activities.

## Why is it important to have an AI assistant for meetings?

Sales professionals often lose valuable time to manual note-taking and CRM updates. This can lead to missed opportunities and poor data hygiene. The AI Sales Assistant addresses these challenges by automating the capture and processing of meeting information.

### What can the AI sales assistant do?

- Record meeting video and transcribe conversations  
- Push transcripts, recordings, summaries, and insights into CRM  
- Automatically create new CRM contacts if not matched  
- Join meetings not hosted by you with manual invitation  
- View and manage internal meeting activities  

## How to set up the AI assistant

### As an admin:

- Navigate to `Administration > Platform Integrations`  
- Set up the Google Calendar connection  
  demo: https://www.loom.com/share/a4559fa419e24442b4c6d5c72bd40438  

### As a salesperson:

- Go to `CRM > My Meetings`  
- Reconnect using Book Me Now integrations  
  demo: https://www.loom.com/share/6891012de5c44af8be7681dbb4968d98  

### Optional AI employee customization:

Use default employee setting or add a custom knowledge base  
  demos:  
  - https://www.loom.com/share/537dfc72ba1c4414ab3c3e28f339cc98  
  - https://www.loom.com/share/15eba8f6c0174031af74f206fe966cdb  

### Workflow for the meetings not hosted by you:
The AI sales assistant does not automatically join meetings that are  hosted by your clients or anyone outside your company. 

To add the AI sales assistant to such external meetings please use the Atlas bar to add the notetaker to Google Meet or Microsoft Teams meetings not hosted by you. 

Here is a quick demo: https://www.loom.com/share/4eb3a61fd4fd407bbbe982a330d42a04  

## How do I find my meetings?

All meeting summaries, transcripts, and recordings are logged as CRM meeting activities.

- To find external meetings conducted by users in your organization, navigate to `CRM > Activity Feed > Recorded Meetings`. You can search just by the meeting title from your Google Calendar  
- To find an internal meeting, just search using the meeting title or owner (organizer of the meeting)  

## Demos:

- https://www.loom.com/share/8069c437715747ef89cdbb63d72a4f96  
- https://www.loom.com/share/934c592310a142a7970b7e8a2b9aca7c  

## FAQs:
  - Question: "Does the AI Sales Assistant depend on Book Me Now?"
    - Answer: No. Book Me Now is only used to read your calendar; the AI Sales Assistant itself has no other dependency on any specific booking tool or app.

  - Question: "Can I use the AI Sales Assistant if we don’t use Book Me Now?"
    
      - Answer: Absolutely. The AI Sales Assistant works with any calendar-booking solution.

  - Question: "Will the notetaker join meetings not scheduled on my calendar?"
    - Answer: 
      By default, no. It only joins events that appear on your calendar and hosted by you or someone in your organization. If you need it in an ad-hoc meeting, you can manually add the notetaker to the meeting. 

  - Question: "Will the notetaker join meetings hosted by my clients?"
      - Answer: 
      No, the notetaker only joins meetings you host or a company member. For client-hosted meetings, you can add it manually as needed.

  - Question: "Are internal meetings recorded?"
    - Answer: 
      Yes. Internal meetings are recorded, and their meeting details and activities are available in the CRM’s activity feed; however, they aren’t linked to external contacts or companies because they are internal meetings. 

  - Question: "If I record an internal meeting, will more than one notetaker be allowed to join?"
      - Answer: 
      No. Only a single notetaker participates in each internal meeting. Technically one Company or Organization (aka Partner ID) Account shares the AI Assistant’s notetaker for such meetings where there are more than one member of the organization is present.

  - Question: "Does every employee need to enable the AI Sales Assistant?"
    - Answer: 
      No. It’s managed centrally at the Partner-Account or organizational level, individual users don’t have to turn it on. They just need to connect Google Calendar to BookMeNow settings or Platform integrations.

  - Question: "Who can manage AI Sales Assistant settings?"
    - Answer: 
      Only Administrators. AI workforce settings are global or organizational settings, just like Merchant Services or Campaigns.

  - Question: "Should I book all future meetings through Book Me Now?"
    - Answer: 
      No. You can continue booking wherever is easiest; there’s no dependency to use Book Me Now.

  - Question: "How do I manually add the notetaker if it doesn’t appear in a hosted meeting?"
    - Answer:   
      You can manually invite the notetaker to any meeting you host. Sometimes, a temporary technical delay may prevent automatic addition. Demo: https://www.loom.com/share/4eb3a61fd4fd407bbbe982a330d42a04?sid=776dae32-20a9-4593-88cb-9b2c2de8a0ce

  - Question: "What if the notetaker leaves a meeting on their own?"
    - Answer: 
      It won’t stay if the meeting remains silent for more than five minutes after the first ten minutes; it will depart if no one speaks for five consecutive minutes. If it leaves, simply add it back manually.

  - Question: "What meeting platforms do you support?"
    - Answer: 
      For Hosts: We support Google Meet in this version of the product.
      Client Hosted Meetings: On the other hand if a client is hosting a meeting you can manually add the notetaker to a Google Meet or Microsoft Teams meeting.

  - Question: "Where can I find my internal meetings?"
    - Answer: 
      They are found in the activity feed. Since internal meetings happen only with my team members of the Partner Center, we do not add them to contacts unless an internal person is also added as a contact in the CRM.

  - Question: "How do I share a meeting with an internal team?"
    - Answer: >
      https://www.loom.com/share/ad64d70df55b4120a6e580e3459de9c5?sid=adb2e699-df15-46d0-8451-078f9eafe19b

  - Question: "How do I chat with the notetaker live?"
    - Answer: 
      This is powered by the knowledge base of the AI employee
      https://www.loom.com/share/f8fcf7a312f64e2cb8f0e218403c28d3?sid=f4510d6d-8f51-401e-b0b1-6935f1b6f5af

  - Question: "Can I turn off the compliance audio and chat?"
    - Answer: Yes, you can do that from the AI employee settings page. This feature provides Partners/users with greater control over their privacy preferences, ensuring alignment with their organization's compliance requirements. Please note that you can make these changes only once per hour and it affects the entire organization.
      Demo: https://www.loom.com/share/1799a9cdcfa8435db410188ce600dc2b?sid=550a6bdf-5c0a-4754-9cfb-477734f57cbf

  - Question: "Can I rename my notetaker?"
    - Answer: 
      Yes, you can do that from the AI employee settings page. This makes it easier to identify specific Notetakers in multi-user environments with a touch of personalization. Please note that you can make these changes only once per hour and it affects the entire organization.
      Demo: https://www.loom.com/share/1799a9cdcfa8435db410188ce600dc2b?sid=550a6bdf-5c0a-4754-9cfb-477734f57cbf

