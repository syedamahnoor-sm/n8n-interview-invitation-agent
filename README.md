# Interview Invitation Draft Agent

A simple email automation workflow created using n8n.

## Workflow

Gmail Trigger → IF → Create a Draft

## How It Works

1. Gmail Trigger detects a new incoming email.
2. The IF node checks whether the email subject contains "Interview".
3. If the condition is true, Gmail automatically creates a response draft.
4. If the condition is false, no draft is created.

## IF Condition

Subject contains:

`Interview`

## Tools Used

- n8n
- Gmail
- Gmail Trigger
- IF Node
- Gmail Create Draft

### Workflow Screenshot
<img width="1008" height="541" alt="image" src="https://github.com/user-attachments/assets/481711e1-5fd7-481c-b85a-e46fff1563b8" />



### Generated Draft
<img width="1316" height="260" alt="image" src="https://github.com/user-attachments/assets/f89d10d0-632c-4e74-a4ac-70847ce290a8" />

