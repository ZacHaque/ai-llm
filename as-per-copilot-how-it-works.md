# How Microsoft Copilot Works

## Overview

Microsoft Copilot is an AI-powered assistant that helps users generate content, answer questions, summarize information, analyze data, and automate tasks across Microsoft applications and services.

When you ask a question, Copilot combines large language models (LLMs) with information that you are authorized to access, then generates a response based on the relevant context.

---

## Step-by-Step: What Happens When You Ask a Question?

### 1. You Enter a Prompt

You type a question, request, or instruction into Copilot.

**Examples:**

- "Summarize my emails from last week."
- "Create a presentation about cloud security."
- "What are my upcoming meetings today?"

---

### 2. The Prompt Is Sent for Processing

Your prompt is securely sent to Microsoft's AI services for analysis.

The service:

- Understands your intent.
- Identifies relevant information sources.
- Determines whether organizational data is needed.
- Sends the request to the AI model for processing.

---

### 3. Copilot Retrieves Relevant Information

Depending on the Copilot product you're using, it may retrieve information from various sources.

#### Microsoft 365 Copilot

Can access content that you already have permission to view, such as:

- Outlook emails
- Teams chats
- Teams meetings
- Word documents
- Excel workbooks
- PowerPoint presentations
- OneDrive files
- SharePoint sites

#### Copilot Chat

May use:

- Microsoft Graph data (when available)
- Organizational information
- Web information (when enabled)

---

### 4. Permission Checks Are Applied

Before any information is returned:

- Copilot checks your existing permissions.
- It only retrieves data you are authorized to access.
- It cannot bypass security settings.
- It cannot access private files, emails, or chats that you do not have permission to view.

This means Copilot follows the same security boundaries as Microsoft 365.

---

### 5. AI Generates the Response

The AI model:

1. Reads your prompt.
2. Reviews retrieved context.
3. Understands the relationships between the data.
4. Generates a natural-language response.

Examples:

- Email summaries
- Meeting recaps
- Document drafts
- PowerPoint slides
- Data analysis
- Action items

---

### 6. The Response Is Returned

The generated response is displayed back to you in:

- Copilot Chat
- Outlook
- Word
- Excel
- PowerPoint
- Teams
- Other Microsoft applications

---

# Where Does My Question Go?

When you submit a prompt:

1. The prompt is transmitted to Microsoft's cloud services.
2. The service processes the request.
3. Relevant data may be retrieved from Microsoft 365 sources.
4. The AI generates a response.
5. The response is returned to your application.

Simplified flow:

```text
User
  |
  v
Copilot Interface
  |
  v
Microsoft AI Services
  |
  +--> Microsoft Graph
  |       |
  |       +--> Outlook
  |       +--> Teams
  |       +--> SharePoint
  |       +--> OneDrive
  |
  v
AI Model
  |
  v
Generated Response
  |
  v
User
```

---

# Does Copilot Use My Data?

## Microsoft 365 Commercial Customers

Microsoft states that:

- Customer data remains within Microsoft's service boundary.
- Existing security and compliance controls continue to apply.
- Prompts and responses are not used to train foundation AI models.
- Organizational data remains governed by Microsoft 365 permissions.

---

# Can Copilot See All My Files?

**No.**

Copilot can only access:

- Files you already have permission to open.
- Emails you are authorized to read.
- Chats and conversations you can access.
- SharePoint and OneDrive content available to your account.

If you cannot access a file manually, Copilot generally cannot access it on your behalf.

---

# Can My Manager See My Copilot Prompts?

Usually, **no**.

Managers do not automatically receive access to your Copilot conversations.

However, organizations may have:

- Data retention policies
- Compliance monitoring
- Auditing controls
- eDiscovery capabilities
- Legal hold requirements

Depending on organizational policies, administrators or compliance personnel may be able to access certain records.

---

# Example Scenario

### User Prompt

> "Summarize my emails about
